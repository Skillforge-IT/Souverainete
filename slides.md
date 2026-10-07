---
theme: default
css: unocss
title: "Souveraineté des données — niveau reconversion"
class: text-center
highlighter: shiki
lineNumbers: false
background: flutie8211-cyber-security-8819383_1920.jpg
---

# Souveraineté des données

## Comprendre, vérifier, aider




---

# Bienvenue : on part de votre expérience

- Pas besoin de tout savoir aujourd’hui.
- On avance avec des exemples du quotidien.
- Les questions sont les bienvenues.

> **Objectif :** savoir poser les bonnes questions quand une donnée est créée, envoyée ou stockée.



---

# Plan de formation

<div class="grid grid-cols-2 gap-8 mt-8">
<div>

### Partie 1 — Comprendre

- Les bases : donnée, Internet, cloud
- La souveraineté en mots simples
- Les règles principales
- Des situations de support

</div>
<div>

### Partie 2 — Agir

- Une recherche guidée, étape par étape
- Une décision expliquée simplement
- Une restitution en petit groupe
- La check-list du support

</div>
</div>



---

# Nos objectifs

À la fin, vous pourrez :

- expliquer ce qu’est une donnée et où elle peut aller ;
- utiliser une analogie pour parler de souveraineté ;
- reconnaître les grands repères : **RGPD, Cloud Act, Data Act, Schrems II, SecNumCloud** ;
- chercher une information avec une méthode simple ;
- savoir quoi vérifier, noter et transmettre en support.

> On ne vous demande pas de devenir juriste : on vous demande de **repérer et d’escalader** au bon moment.

---

# Partie 1 - Comprendre la souveraineté 
# Mise à niveau 1 — C’est quoi, une donnée ?

Une **donnée** = une information que l’on peut garder, lire ou transmettre.

Exemples :

- nom, adresse e-mail, numéro de téléphone ;
- photo, ticket support, mot de passe ;
- fiche de paie, dossier client, journal de connexion.

**Analogie :** une donnée, c’est comme une feuille dans un dossier.


---

# Mise à niveau 2 — Internet, en très gros

**Internet** = un grand réseau qui relie des appareils.

- Votre ordinateur envoie une demande.
- Des équipements la transportent.
- Un autre ordinateur répond.

**Adresse IP** → le numéro qui aide à trouver un appareil sur le réseau.

**Analogie :** Internet ressemble au réseau postal : une adresse, des étapes, un destinataire.


---

# Mise à niveau 3 — Le cloud, en très gros

**Cloud / nuage informatique** → un service qui garde ou fait fonctionner vos fichiers sur des ordinateurs situés ailleurs, accessibles par Internet.

- Vous utilisez le service.
- Le fournisseur s’occupe d’une partie des machines.
- Il faut savoir où sont les machines et qui peut intervenir.

**Analogie :** louer un box de stockage : vos affaires sont ailleurs, mais vous devez connaître les règles d’accès.


---

# Souveraineté : la question simple

**Souveraineté des données** → savoir où sont rangées les données et qui a le droit d’y toucher.

Les 4 questions de base :

1. **Quoi ?** quelles données ?
2. **Où ?** dans quel pays, quel service, quelle sauvegarde ?
3. **Qui ?** quelles personnes ou entreprises peuvent y accéder ?
4. **Selon quelle règle ?** quelle loi ou quel contrat s’applique ?

**Analogie :** où sont rangées vos affaires, qui a la clé et que se passe-t-il si quelqu’un la demande ?

---

# Les mots clés

| Terme | Explication  |
|---|---|
| **Héberger** | garder des données sur un ordinateur ou un serveur |
| **Serveur** | ordinateur qui rend un service à d’autres appareils |
| **Chiffrement** | transformer un message pour qu’il soit illisible sans la bonne clé |
| **Sauvegarde** | copie gardée pour retrouver les données après un problème |
| **Sous-traitant** | entreprise qui réalise une tâche pour une autre |
| **API** | porte d’entrée qui permet à deux logiciels d’échanger |

**Analogie :** un serveur est un entrepôt, le chiffrement une boîte fermée, l’API un guichet entre deux services.

---

# Ce qui peut voyager sans qu’on le voie

Une donnée peut passer par :

- le poste de travail ;
- un serveur ;
- le réseau ;
- le serveur de l'entreprise ;
- un outil de ticketing ;
- un fournisseur cloud ;
- une sauvegarde ou un support technique.

**Flux de données** → trajet d’une donnée d’un endroit à un autre.

**Analogie :** suivre un colis : départ, étapes, entrepôt, livraison.


---

# Pourquoi cela concerne le support ?

Un technicien de support peut :

- afficher une donnée personnelle ;
- envoyer une capture d’écran ;
- donner un accès temporaire ;
- restaurer une sauvegarde.

**Réflexe :** avant de cliquer sur « envoyer », se demander : *qu’est-ce que j’envoie, à qui et où cela va ?*



---

# Le cadre réglementaire : une idée par texte

<div class="grid grid-cols-2 gap-6 text-sm">
<div>

### RGPD
**Règle simple :** protéger les informations personnelles et ne prendre que ce qui est nécessaire.  
**Impact support :** ne pas copier une donnée dans un ticket si elle n’est pas utile ; masquer les mots de passe et captures sensibles.

### Cloud Act
**Règle simple :** une entreprise soumise au droit des États-Unis peut devoir répondre à une demande légale américaine, même si ses serveurs sont ailleurs.  
**Impact support :** ne pas promettre qu’un pays de stockage suffit ; demander au responsable sécurité/juridique en cas de doute.

</div>
<div>

### Data Act
**Règle simple :** faciliter l’accès et le changement de fournisseur pour certaines données produites par des objets ou services connectés.  
**Impact support :** vérifier comment récupérer les données si l’entreprise change d’outil.

</div>
</div>

> Ces repères aident à poser une question. La décision juridique appartient aux personnes compétentes.

---

# Le cadre réglementaire : une idée par texte

<div class="grid grid-cols-2 gap-6 text-sm">
<div>

### Schrems II
**Règle simple :** un transfert de données vers un pays hors UE doit offrir une protection réellement comparable à celle de l’UE.  
**Impact support :** repérer le pays et le fournisseur ; ne pas conclure seul que « c’est autorisé ».

</div>
<div>

### SecNumCloud
**Règle simple :** qualification française de sécurité pour certains services cloud sensibles.  
**Impact support :** vérifier si le cahier des charges demande ce niveau de confiance avant de choisir un service.

</div>
</div>

> Ces repères aident à poser une question. La décision juridique appartient aux personnes compétentes.

---

# Un exemple : le Cloud Act et le RGPD

**Situation :** un prestataire demande une copie d’un fichier contenant des données client.

1. Le **RGPD** nous demande de protéger et limiter les données.
2. Le **Cloud Act** peut créer une obligation pour certains fournisseurs liés aux États-Unis.
3. Le support ne tranche pas seul.

**À faire :**

- vérifier la demande et son destinataire ;
- ne pas transmettre de donnée inutile ;
- conserver la trace ;
- escalader vers sécurité, DPO ou juridique.

**Analogie :** deux règlements de copropriété peuvent s’appliquer à un même local : on demande au syndic avant d’agir.

---

# Grille de lecture 

| Mot clé | Question  |
|---|---|
| **Donnée** | Qu’est-ce qui est enregistré ? Est-ce sensible ? |
| **Lieu** | Où est-ce gardé et sauvegardé ? |
| **Accès** | Qui peut voir, modifier ou demander ? |
| **Continuité** | Comment retrouver la donnée si le service tombe ? |

**Mot métier :** une **cartographie** → un dessin ou tableau qui montre le trajet des données.


---

# Activité 1 — Le ticket support (20 min)

### En binôme, avec la fiche « Grille de lecture »

Situation : *« Mon compte est bloqué. Voici ma capture d’écran et mon mot de passe pour aller plus vite. »*

1. Notez les données présentes.
2. Mentionnez ce qui ne doit pas être demandé ou partagé.
3. Choisissez la réponse la plus sûre :
   - A. demander le mot de passe ;
   - B. utiliser la procédure de réinitialisation ;
   - C. envoyer la capture à tout le service.
4. Expliquez votre choix en une phrase.


---

# Activité 2 — Trouver le bon réflexe (15 min)

Pour chaque cas, choisissez **vérifier**, **limiter**, **tracer** ou **escalader**.

- Un ticket contient une photo de pièce d’identité.
- Une sauvegarde doit être restaurée par un prestataire.
- Un utilisateur demande « qui a lu mon dossier ? »
- Un outil cloud change de pays d’hébergement.

> Plusieurs réflexes peuvent être utiles. L’important est de savoir expliquer pourquoi.

---

# Pause : les trois phrases à retenir

1. Une donnée a un **contenu**, un **trajet** et des **personnes qui y accèdent**.
2. Le cloud est pratique, mais il faut connaître les règles de la location.
3. En support, je **limite, vérifie, trace et demande de l’aide** si nécessaire.





---

# Partie 2 — De la question à la décision

## Une recherche accompagnée

### Question commune
**« Le RGPD interdit-il toujours de stocker une donnée hors de l’Union européenne ? »**

1. comment reconnaître un site institutionnel (CNIL, ANSSI, EUR-Lex) ;
2. chercher les mots importants dans la page ;
3. comment dire ce que la source ne permet pas d’affirmer.


---

# La fiche de guidage — mode d’emploi

1. **Je lis la situation.**
2. **Je souligne les mots inconnus.**
3. **Je transforme la situation en une question.**
4. **Je consulte d’abord une source officielle.**
5. **Je note une preuve courte, sans copier toute la page.**
6. **Je cherche une deuxième source pour comparer.**
7. **Je traduis en conséquence pour le support.**
8. **Je prépare une restitution de 3 minutes.**


---

# Étape 1 — Comprendre la question

Complétez les cases :

- Le service ou l’outil concerné est : …
- La donnée concernée est : …
- La personne qui demande est : …
- Le risque que l’on veut éviter est : …

Puis répondez aux questions :

- Où la donnée est-elle conservée ?
- Qui peut y accéder ?
- Comment la récupérer ou la supprimer ?
- Quelle règle faut-il vérifier ?

---

# Étape 2 — Chercher au bon endroit

### Ordre conseillé

1. **Source officielle :** CNIL, ANSSI, EUR-Lex, Commission européenne.
2. **Documentation du fournisseur :** pays, sécurité, suppression, export.
3. **Article spécialisé :** pour comprendre, pas comme seule preuve.

### Requêtes prêtes à l’emploi

- `site:cnil.fr [mot de la question]`
- `site:anssi.gouv.fr cloud sécurité données`
- `site:eur-lex.europa.eu Data Act données`

**Question fermée :** la page indique-t-elle son auteur et sa date ? Oui / Non / Je ne sais pas.

---

# Étape 3 — Noter une source sans se perdre

Pour chaque source, remplir :

| Objet | Réponse courte |
|---|---|
| Organisme / auteur | … |
| Date | … |
| Lien | … |
| Phrase utile reformulée | … |
| Ce que cela prouve | … |
| Ce que cela ne prouve pas | … |

**Règle :** une source officielle explique mieux la règle ; elle ne répond pas forcément à notre cas précis.

---

# Étape 4 — Questions de vérification

Avant de garder une information, répondre :

- La source parle-t-elle bien de notre sujet ? Oui / Non
- Est-elle assez récente ? Oui / Non / À vérifier
- Confirme-t-elle un fait ou donne-t-elle une opinion ?
- Une autre source dit-elle la même chose ?


---

# Étape 5 — Traduire pour le métier support

Terminez ces phrases :

- **Avant d’agir, je vérifie…**
- **Je ne partage pas…**
- **Je garde une trace de…**
- **J’escalade vers… lorsque…**

Exemple :

> « Avant d’envoyer une capture au prestataire, je masque le mot de passe et je vérifie le canal autorisé. »

**Analogie :** passer du langage du manuel au langage d’un collègue qui appelle au téléphone.

---

# Les sujets proposés aux groupes

<div class="grid grid-cols-2 gap-6">
<div>

### Groupe A — RGPD
Quel réflexe pour un ticket contenant trop d’informations personnelles ?

### Groupe B — Cloud Act / pays
Quelles questions poser sur le fournisseur et les accès légaux ?

### Groupe C — Data Act
Comment préparer un changement d’outil et la récupération des données ?

</div>
<div>

### Groupe D — Schrems II
Que vérifier lors d’un transfert vers un pays hors UE ?

### Groupe E — SecNumCloud
Quand ce niveau de sécurité peut-il être demandé ?

### Groupe F — Sauvegarde
Comment retrouver une donnée sans créer un nouveau risque ?

</div>
</div>

Chaque groupe reçoit **un seul sujet** et la même fiche guidée.

---

# Travail guidé en sous-groupes — 35 min

### Déroulé visible au tableau

- **0–5 min :** lire la situation et répartir les rôles ;
- **5–12 min :** écrire la question et les mots-clés ;
- **12–22 min :** consulter deux sources ;
- **22–28 min :** remplir le tableau « ce que je sais / ce que je ne sais pas » ;
- **28–35 min :** préparer trois phrases et un conseil support.

### Rôles possibles

- lecteur de la consigne ;
- personne qui cherche ;
- personne qui note ;
- rapporteur.

On peut changer de rôle. Aucun rôle ne demande de tout connaître.

---

# La fiche de restitution — 3 minutes

Chaque groupe présente :

1. **Notre situation :** …
2. **Notre réponse simple :** …
3. **Une preuve :** organisme + lien + phrase reformulée.
4. **Notre conseil au support :** …
5. **Notre limite ou question restante :** …

**Format :** une feuille, un tableau ou trois diapositives maximum.



---

# Écouter les autres groupes

Pendant chaque présentation, notez une idée dans chacune des colonnes :

| J’ai compris | Je peux réutiliser | Je veux vérifier |
|---|---|---|
| … | … | … |

Questions autorisées :

- « Pouvez-vous expliquer ce mot autrement ? »
- « Quelle est votre source ? »
- « Que ferait-on concrètement au support ? »


---

# Grille d’évaluation — /20

| Critère ASRC adapté | Points |
|---|---:|
| La situation et les données sont correctement repérées (C21, C22) | 4 |
| Les questions « où / qui / quoi / quelle règle » sont posées | 4 |
| Deux sources sont citées et leur limite est expliquée (C28, C29) | 4 |
| Le conseil support est concret : limiter, vérifier, tracer, escalader | 4 |
| La restitution est claire et le vocabulaire expliqué | 4 |

> Une réponse prudente et bien expliquée vaut mieux qu’une réponse très technique mais incertaine.

---

# Grille de lecture individuelle — mon auto-évaluation

Cochez : **je découvre / je progresse / je peux l’expliquer**

- Je peux définir une donnée avec un exemple.
- Je peux expliquer le cloud avec l’analogie du box.
- Je peux poser les quatre questions de souveraineté.
- Je sais reconnaître une source officielle.
- Je sais quand demander de l’aide.

**Objectif :** repérer le prochain petit pas, pas se comparer aux autres.

---

# La check-list du technicien support

Avant de créer, transmettre ou restaurer :

- [ ] Quelle donnée est concernée ?
- [ ] Est-elle vraiment nécessaire ?
- [ ] À qui vais-je la transmettre ?
- [ ] Où peut-elle être stockée ou sauvegardée ?
- [ ] Quel canal est prévu par l’entreprise ?
- [ ] Ai-je laissé une trace ?
- [ ] Dois-je demander au responsable sécurité, DPO ou manager ?

**Le DPO** → personne qui aide l’organisation à respecter les règles sur les données personnelles.

---

# Quiz de clôture — on réfléchit ensemble

### 1. Une donnée, c’est…
A. seulement un fichier  
B. une information que l’on peut garder, lire ou transmettre  
C. uniquement un mot de passe

### 2. Le cloud, c’est plutôt…
A. un service sur des ordinateurs accessibles par Internet  
B. un lieu sans règles  
C. une sauvegarde automatique garantie

### 3. Si je ne sais pas si je peux transmettre une donnée…
A. je l’envoie vite  
B. je vérifie et je demande de l’aide  
C. je la publie pour avoir un avis

---

# Quiz — correction
- **1 → B :** une donnée peut être un nom, une photo, un ticket ou un journal de connexion.
- **2 → A :** le cloud est pratique ; il faut vérifier ses règles et ses accès.
- **3 → B :** vérifier et demander de l’aide est un bon réflexe professionnel.


---

# Ce qui reste à retenir

### 1. Je regarde le trajet
**Quoi ? Où ? Qui ? Quelle règle ?**

### 2. Je protège les personnes
Je limite les données et je respecte la procédure.

### 3. Je rends mon action vérifiable
Je note, je trace et j’escalade si besoin.


---

# Pour aller plus loin, sans se noyer

### Sources de référence

- CNIL — données personnelles et RGPD : `cnil.fr`
- ANSSI — sécurité informatique et cloud : `cyber.gouv.fr`
- EUR-Lex — textes de l’Union européenne : `eur-lex.europa.eu`
- Documentation officielle du fournisseur utilisé par l’entreprise

### Méthode personnelle

1. Je commence par une source officielle.
2. Je garde le lien et la date.
3. Je reformule en mots simples.
4. Je demande confirmation si l’enjeu est important.

---

# Merci — votre prochain réflexe

Quand vous verrez une donnée dans un ticket, pensez :

> **« Qu’est-ce que c’est, où va-t-elle, qui peut la voir et que dois-je vérifier ? »**

Vous avez maintenant une méthode pour avancer, même quand vous ne connaissez pas encore le mot technique.

