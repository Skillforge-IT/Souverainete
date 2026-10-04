---
theme: default
class: souverainete
highlighter: shiki
lineNumbers: false
mdc: true
transition: slide
---

<style>
:root { --ink:#11212b; --muted:#55707a; --teal:#0d7377; --orange:#ee7b4d; --paper:#f7f3ea; --blue:#dff1ef; }
.slidev-layout { background: var(--paper); color: var(--ink); }
h1 { color: var(--teal); letter-spacing: -.03em; }
h2 { color: var(--teal); }
strong { color: var(--orange); }
.activity { border-left: 6px solid var(--orange); background: #fff8ef; padding: 1rem 1.25rem; border-radius: 0 12px 12px 0; }
.note { color: var(--muted); font-size: .9em; }
.kicker { text-transform: uppercase; letter-spacing: .15em; color: var(--orange); font-weight: 700; font-size: .75em; }
.grid2 { display:grid; grid-template-columns:1fr 1fr; gap:1rem; }
.card { padding:1rem; border:1px solid #cbdedb; border-radius:12px; background:#ffffffaa; }
table { font-size: .78em; }
</style>

---
layout: cover
---

# Souveraineté des données

## Comprendre, questionner, agir

Formation · 2 demi-journées · Apprentis techniciens support

<div class="absolute bottom-10 left-14">
  <span class="kicker">Support technique · conformité · esprit critique</span>
</div>

---

# Le fil rouge

> Une donnée n’est pas seulement « dans un serveur » : elle est aussi soumise à un **contrat**, une **architecture**, une **juridiction** et des **personnes habilitées**.

<div class="grid2 mt-8">
<div class="card"><b>½ journée 1</b><br/>Fondamentaux · droit · modèles techniques</div>
<div class="card"><b>½ journée 2</b><br/>Analyse de sources · cas pratique · pitch</div>
</div>

<div class="activity mt-8"><b>ACTIVITÉ — Positionnement (5 min)</b><br/>À main levée : « Un cloud européen garantit-il automatiquement la souveraineté ? » Notez votre première réponse et ce qui pourrait la faire évoluer.</div>

---
layout: fact
---

# Objectifs pédagogiques

## À la fin, vous saurez…

- expliquer les notions de souveraineté, donnée personnelle, cloud, hébergement et juridiction ;
- distinguer **localisation**, **contrôle**, **accès** et **réversibilité** ;
- repérer les risques d’extraterritorialité et d’exfiltration ;
- comparer des discours de sources aux intérêts différents ;
- contribuer à une décision de migration cloud et la traduire en gestes de support ;
- rechercher, vérifier et synthétiser une source technique, y compris en anglais.

<div class="note mt-6">Méthode : comprendre → questionner → documenter → recommander.</div>

---

# Déroulé des 2 demi-journées

| Temps | Séquence | Production apprenant |
|---|---|---|
| J1 · 1 | Fondamentaux & vocabulaire | carte mentale des notions |
| J1 · 2 | Cadre juridique | tableau « obligation / risque / preuve » |
| J1 · 3 | Architecture & menaces | schéma de flux et matrice de risques |
| J2 · 1 | Analyse critique | grille de lecture de 4 sources |
| J2 · 2 | Cas « migration cloud » | note de recommandation en équipe |
| J2 · 3 | Recherche documentaire | 2 fiches sources, dont 1 en anglais |
| J2 · 4 | Évaluation | pitch de 3 min + checklist support |

---

---
layout: two-cols
---

# Localiser n’est pas contrôler

::left::

**Localisation**

- où les octets résident ;
- où ils sont répliqués ;
- où ils sont sauvegardés.

::right::

**Contrôle**

- qui administre et peut accéder ;
- quelle loi peut contraindre ;
- comment récupérer et sortir.

<div class="note mt-6">Question support : quelle preuve permet de vérifier chaque affirmation ?</div>

---

# 1 · Les mots qui évitent les contresens

<div class="grid2">
<div class="card"><b>Souveraineté des données</b><br/>Capacité à décider et à faire respecter ses règles sur les données : accès, usages, localisation, sécurité, continuité et sortie.</div>
<div class="card"><b>Donnée personnelle</b><br/>Information se rapportant à une personne identifiée ou identifiable : identité, adresse IP, ticket support, logs associés…</div>
<div class="card"><b>Cloud</b><br/>Accès à la demande, via un réseau, à des ressources informatiques mutualisées et pilotables (calcul, stockage, application).</div>
<div class="card"><b>Hébergement</b><br/>Lieu et conditions techniques où une donnée est stockée et traitée : infrastructure, opérateur, sous-traitants, sauvegardes.</div>
</div>

---

# 1 · Juridiction : la question « quelle loi peut s’appliquer ? »

La juridiction dépend notamment de :

- la résidence et l’activité du responsable de traitement ;
- le lieu des personnes concernées et des serveurs ;
- le siège de l’hébergeur et de ses sous-traitants ;
- le contrat, les autorités compétentes et les mécanismes d’accès ;
- le type de donnée et le secteur (santé, défense, finance…).

<div class="activity mt-6"><b>ACTIVITÉ — Cartographie express (10 min)</b><br/>Pour un ticket contenant nom, adresse IP, capture d’écran et historique d’incident : identifiez les données personnelles, les acteurs, les lieux possibles et les questions à poser avant de partager le ticket à un prestataire.</div>

---

# 2 · Réglementations : repères, pas récitation

| Texte / décision | Ce qu’il faut retenir pour le support |
|---|---|
| **RGPD** | Principes, droits, minimisation, sécurité, sous-traitants, transferts hors UE, notification des violations. |
| **Loi Informatique et Libertés** | Cadre français qui complète le RGPD ; rôle et pouvoirs de la CNIL. |
| **Schrems II** | Un transfert vers un pays tiers doit être évalué ; les garanties contractuelles seules peuvent être insuffisantes. |
| **Cloud Act (États-Unis)** | Une entreprise relevant du droit US peut être soumise à une demande d’accès, y compris pour des données détenues à l’étranger, selon le contexte juridique. |
| **NIS2** | Renforce la cybersécurité et la gestion des risques pour de nombreux secteurs et entités ; exigences de gouvernance, incidents et chaîne de sous-traitance. |

<div class="note">Ce tableau est pédagogique : il ne remplace ni l’avis du DPO, ni une analyse juridique actualisée.</div>

---

# 2 · Réflexe RGPD face à un incident

1. **Qualifier** : quelles données, combien, quelles personnes ?
2. **Limiter** : isoler, révoquer, préserver les preuves ; ne pas détruire les logs.
3. **Alerter** : suivre la procédure interne (RSSI, DPO, responsable d’astreinte).
4. **Tracer** : date, faits vérifiés, actions et incertitudes.
5. **Décider** : notification, information, remédiation — par les rôles compétents.

<div class="activity mt-5"><b>ACTIVITÉ — Le bon réflexe (8 min)</b><br/>Un prestataire demande par e-mail un export complet des tickets pour « diagnostiquer ». Quelles vérifications faites-vous avant l’envoi ? Répondez en 5 questions maximum.</div>

---

# 3 · Modèles d’hébergement : qui opère quoi ?

| Modèle | L’entreprise garde surtout… | Vigilance souveraineté |
|---|---|---|
| **On-premise** | matériel, réseau, OS, données | compétences, coûts, accès admin, dépendances matérielles |
| **IaaS** | OS, applications, données | région, hyperviseur, logs, clés, sous-traitants |
| **PaaS** | code, données, configuration | dépendance aux services propriétaires, portabilité |
| **SaaS** | configuration, comptes, données | contrat, export, support, localisation réelle des sauvegardes |
| **Cloud hybride** | une stratégie multi-environnements | flux, identités, cohérence des politiques, points de jonction |

<div class="note">Plus on monte vers SaaS, plus l’opérateur prend en charge — et plus il faut lire le contrat, le DPA et les mécanismes de sortie.</div>

---

# 3 · Localisation ≠ souveraineté

**Localisation** : où les octets sont stockés ou traités.

**Souveraineté** : qui peut décider, accéder, contraindre, modifier ou interrompre le service — et selon quelles règles.

À vérifier :

- régions primaires, réplications, sauvegardes et support ;
- métadonnées, journaux, télémétrie et outils d’administration ;
- sous-traitants et chaînes de support ;
- clauses d’accès gouvernemental et procédure de notification ;
- export dans un format exploitable et délai de restitution.

---

# 3 · Chiffrement & gestion des clés

<div class="grid2">
<div class="card"><b>En transit</b><br/>TLS, certificats, authentification mutuelle selon le besoin.</div>
<div class="card"><b>Au repos</b><br/>Disques, bases, sauvegardes ; attention aux copies et snapshots.</div>
<div class="card"><b>Clés gérées par le fournisseur</b><br/>Simple, mais confiance et contrôle fortement délégués.</div>
<div class="card"><b>BYOK / HYOK</b><br/>Apporter ou conserver les clés peut renforcer le contrôle ; cela ajoute disponibilité, rotation et récupération à gérer.</div>
</div>

> Chiffrer protège le contenu ; cela ne supprime pas les métadonnées, les accès administratifs ni la juridiction.

---

# 3 · Menaces à modéliser

| Risque | Exemple | Réponse support |
|---|---|---|
| **Exfiltration** | export de tickets ou clé d’API volée | moindre privilège, alertes, révocation, traçabilité |
| **Extraterritorialité** | demande d’accès d’une autorité étrangère | clauses, conseil juridique, architecture et chiffrement |
| **Erreur de configuration** | bucket public, sauvegarde non chiffrée | revue, contrôles automatisés, procédure de changement |
| **Ransomware / indisponibilité** | chiffrement des fichiers ou panne fournisseur | sauvegardes testées, plan de reprise, réversibilité |
| **Dépendance fournisseur** | API propriétaire, migration coûteuse | formats ouverts, tests de sortie, clauses SLA |

<div class="activity mt-5"><b>ACTIVITÉ — Flux sensible (15 min)</b><br/>Dessinez le trajet d’un ticket support : poste → outil ITSM → stockage → sauvegarde → prestataire. Ajoutez acteurs, pays, clés, logs et points de contrôle.</div>

---

# 4 · Analyse critique : quatre voix à comparer

Les groupes reçoivent quatre extraits ou pages documentaires et remplissent la même grille :

1. **ANSSI / CNIL** — recommandations, doctrine, risques et conformité ;
2. **Presse généraliste** — mise en récit, enjeux économiques et géopolitiques ;
3. **Hyperscaler AWS ou Azure** — sécurité, régions cloud, certifications, engagements contractuels ;
4. **Acteur européen OVHcloud ou Scaleway** — contrôle européen, localisation, alternatives et limites.

<div class="note">On ne cherche pas « qui dit vrai » en une phrase : on identifie angle, preuves, omissions et conditions.</div>

---

# 4 · Grille d’analyse à remplir

| Critère | Notes du groupe |
|---|---|
| Source, auteur, date, type | … |
| Public visé et intérêt possible | … |
| Thèse / promesse en une phrase | … |
| Faits vérifiables et preuves citées | … |
| Vocabulaire chargé ou ambigu | … |
| Ce qui est reconnu / ce qui est omis | … |
| Hypothèses et limites | … |
| Questions à poser au fournisseur | … |
| Décision support possible | … |

<div class="activity mt-4"><b>ACTIVITÉ — Contradiction utile (20 min)</b><br/>Reformulez le meilleur argument de la source, puis son meilleur contre-argument. Terminez par : « Nous aurions besoin de vérifier… »</div>

---

# 4 · Une publicité n’est pas une preuve

Pour tester une affirmation :

- **Qui parle ?** autorité, journaliste, vendeur, client, chercheur ?
- **De quoi parle-t-on ?** contenu, métadonnées, sauvegardes, support ?
- **Quelle preuve ?** audit, certificat, contrat, architecture, simple promesse ?
- **Quelle date et quel périmètre ?** région, service, version, filiale ?
- **Quelle condition cachée ?** option payante, clé client, configuration, exception ?

> « Hébergé en Europe » peut être exact tout en laissant ouvertes les questions d’accès, de support, de contrôle et de réversibilité.

---

# 5 · TP — « Notre entreprise migre vers le cloud »

**Contexte** : l’entreprise veut migrer l’outil ITSM. Les tickets peuvent contenir des données personnelles et des pièces jointes. La direction veut réduire les coûts et améliorer la disponibilité. L’équipe support doit éclairer le choix.

**Livrable équipe (1 page)**

- données et niveaux de sensibilité ;
- modèle(s) d’hébergement comparés ;
- flux, pays, acteurs et sous-traitants ;
- exigences de chiffrement, identités, logs et sauvegardes ;
- risques prioritaires et mesures ;
- questions contractuelles et test de réversibilité ;
- recommandation conditionnelle : « nous choisissons… si… »

---

# 5 · Recherche documentaire dirigée

Chaque équipe ajoute **2 sources complémentaires** :

- **1 source non française** : anglais recommandé (régulateur, standard, documentation fournisseur, publication universitaire) ;
- **1 source technique** : architecture, guide de configuration, fiche sécurité, rapport d’audit ou documentation API.

Pour chaque source, remettre une fiche :

| Champ | À renseigner |
|---|---|
| Référence, auteur, date | … |
| Langue et type | … |
| Question à laquelle elle répond | … |
| 3 informations utiles | … |
| Limite / biais / périmètre | … |
| Traduction en action support | … |

<div class="activity mt-5"><b>RÈGLE D’OR</b><br/>Une source retrouvée n’est pas une source validée : recoupez une affirmation importante et conservez la date de consultation.</div>

---

# 5 · Plan de travail en équipe

<div class="grid2">
<div class="card"><b>Rôles</b><br/>pilote · documentaliste · architecte · rapporteur</div>
<div class="card"><b>Backlog</b><br/>qualifier les données → cartographier → rechercher → comparer → recommander</div>
<div class="card"><b>Point de contrôle</b><br/>chaque risque doit avoir une preuve, un responsable et une action</div>
<div class="card"><b>Définition de « terminé »</b><br/>note lisible, sources datées, décision conditionnelle, sortie testée</div>
</div>

---

# 6 · Checklist du support technique

Avant de transmettre, configurer ou dépanner :

- [ ] Ai-je minimisé les données visibles et partagées ?
- [ ] Le demandeur et le destinataire sont-ils authentifiés et habilités ?
- [ ] Le canal est-il adapté et chiffré ?
- [ ] Ai-je vérifié environnement, région, sauvegardes et sous-traitants ?
- [ ] Les journaux et preuves sont-ils préservés sans exposer de secrets ?
- [ ] Ai-je révoqué/rotaté les secrets en cas de doute ?
- [ ] L’action est-elle tracée dans le ticket ?
- [ ] Sais-je qui alerter : RSSI, DPO, responsable, fournisseur ?
- [ ] Existe-t-il un plan de retour arrière et de réversibilité ?

---

# 6 · Pitch oral — 3 minutes

**Structure conseillée**

1. **Contexte** (30 s) : quelles données et quel besoin ?
2. **Diagnostic** (60 s) : trois risques, avec preuves.
3. **Choix** (45 s) : recommandation et conditions.
4. **Plan support** (30 s) : deux actions immédiates.
5. **Limite** (15 s) : ce qui doit être vérifié par DPO, RSSI ou juridique.

**Interdit** : « c’est sécurisé » sans préciser *quoi*, *contre quoi*, *par qui* et *avec quelle preuve*.

---

# 6 · Mapping référentiel ASRC

| Compétence | Trace dans la formation |
|---|---|
| **C16 — Conduire des audits de sécurité** | cartographie des flux, contrôle des accès, localisation, clés, preuves |
| **C17 — Élaborer des actions correctives** | matrice risques → mesures, checklist et plan de remédiation |
| **C24 — Rédiger des spécifications techniques** | livrable « migration cloud » : exigences, performance, sécurité, sortie |
| **C25 — Orchestrer un projet informatique** | rôles, backlog, jalons, revue d’équipe et recommandation |
| **C28 — Analyser des contenus de diverses sources** | grille critique, recoupement, synthèse, source en anglais |
| **C29 — Mettre en place une veille** | fiches sources datées, critères de fiabilité, base de connaissances |

<div class="note">Le référentiel fourni formule C16, C17, C24, C25, C28 et C29 ; les activités proposées produisent des traces observables pour chacune.</div>

---

# Évaluation — critères transparents

| Critère | Attendu |
|---|---|
| Exactitude | notions et risques correctement distingués |
| Analyse critique | intérêts, preuves, limites et conditions identifiés |
| Technique | flux, clés, accès, sauvegardes et sortie pris en compte |
| Recherche | 2 sources complémentaires, dont 1 non-française et 1 technique |
| Recommandation | choix argumenté, faisable, conditionnel |
| Communication | pitch clair, vocabulaire support, alertes bien orientées |

**Auto-évaluation** : Je sais expliquer… / Je dois encore vérifier… / Ma prochaine action…

---

# À retenir

## La souveraineté est une décision d’architecture et de gouvernance

- La **localisation** est une donnée de contexte, pas une garantie suffisante.
- Le **contrat** doit préciser accès, sous-traitants, incidents et sortie.
- Le **chiffrement** est utile seulement si les clés, les accès et la disponibilité sont maîtrisés.
- Un technicien support protège aussi par ses **gestes quotidiens** : minimiser, authentifier, tracer, alerter.
- Une bonne recommandation dit aussi ce qu’elle **ne sait pas encore**.

<div class="activity mt-8"><b>Tour de table final</b><br/>En une phrase : « Pour moi, la souveraineté des données signifie désormais… »</div>

---

# Annexe · Lexique minute

**Responsable de traitement** : détermine finalités et moyens. · **Sous-traitant** : traite pour le compte du responsable. · **DPA** : accord encadrant ce traitement. · **Région cloud** : zone géographique annoncée par un fournisseur. · **Clé KMS** : clé gérée par un service de gestion de clés. · **BYOK/HYOK** : apporter/conserver sa clé. · **Réversibilité** : capacité à récupérer données et configurations et changer de solution. · **Exfiltration** : sortie non autorisée de données. · **Extraterritorialité** : application potentielle d’une loi au-delà du territoire où les données sont stockées.

<div class="note mt-8">Support de formation — à compléter par les politiques internes, le DPO/RSSI et les versions réglementaires en vigueur.</div>
