# Contexte
```
Objet : Retour réunion Learn@Home
De : Thomas
À : Vous

Hello, 

Comme promis je t’envoie plus d’informations, suite à la réunion que nous avons eue hier avec Learn@Home. 

Learn@Home souhaite travailler avec nous sur toute la conception de son site web. 

Notre première étape est de bien définir les besoins client, avant de démarrer le développement logiciel pur. Nous avons prévu une nouvelle réunion dans quelques semaines, l’objectif est que tu leur présentes les éléments suivants : 

1. Les diagrammes de cas d’usage pour chacune des fonctionnalités majeures de chaque page (connexion, chat, calendrier, gestionnaire de tâches, tableau de bord), pas besoin d’utiliser l’UML.
2. Les user stories avec critère(s) d’acceptation pour chacune des fonctionnalités, partagées dans un format standard (PDF, DOCX, XLSX).
3. Les maquettes du site avec un design simple et au moins une maquette par page (tu peux utiliser Figma ou Sketch et il faudra que tu expliques la navigation entre les pages pendant le meeting).
4. Un Kanban découpant le projet, de manière macro (détails techniques exclus) en blocs de fonctionnalités et sous-fonctionnalités pour le développement. J’ai démarré le découpage dans ce kanban sur Notion, à toi de finir de compléter la colonne ”ANALYZE” sur le même modèle. Tu peux travailler sur Notion, Trello ou GitHub.
____________________________________________________

Je t’envoie un document dans lequel j’ai synthétisé les attentes du client. Tu y trouveras nos prises de notes et quelques croquis. Bien sûr, il faudra fournir les maquettes pour desktop et mobile.

Pour les délais, pas de stress, on a réussi à négocier avec le client pour que tu aies suffisamment de temps pour concevoir tous les documents et préparer ta réunion.

Si tu as des questions, n’hésite pas !

Thomas 
```
- [Tableau Kanban](https://www.notion.so/Dev4U-projet-Learn-Home-972828849f7947289c23756d323a6335)

- [Notes de réunions](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P8+-+Gestion+de+projet/Notes+-+Re%CC%81union+Learn%40Home.pdf)



## La page de connexion
```
La page de connexion doit permettre à un élève ou à un bénévole de se
connecter. Toutes les autres pages ne sont accessibles qu’une fois connecté à un compte. Cette page doit intégrer :
____________________________________________________

- Un système de récupération de mot de passe oublié
- Un lien vers une page de création de compte
```

## Le tableau de bord
```
Cette page servira de page principale et devra donc regrouper un récapitulatif de toutes les informations récentes et importantes en provenance des autres pages :chat, calendrier, gestion des tâches. 
La page affichera :
____________________________________________________

- Un récapitulatif des tâches (to-do list) issu de la page de gestion des tâches (5.)
- la liste des événements prochains, issue de la page calendrier (4.)
- Un compteur de messages non lus.
```

## L’interface de chat
```
L’interface de chat de Learn@Home est à une page de chat classique, intégrant un système de discussion instantané entre élèves et bénévoles. Elle doit aussi permettre d’accéder à l’historique des conversations, et d’ajouter ou supprimer un contact.
D’autres éléments doivent être ajoutés :
- La photo de profil de l’expéditeur, à côté de chaque message
- Un indicateur permettant de visualiser si un message a été lu ou non.
- L’horodatage des messages
```


## Le calendrier
```
La page de calendrier de Learn@Home correspond à une page de calendrier classique, sur laquelle s’affichent les différents événements, rendez-vous de l’utilisateur.
```


## La gestion des tâches

```
L’interface de cette page doit permettre de créer des tâches pour soi-même ou pour un autre utilisateur.
● L’élève ne peut créer des tâches que pour lui-même.
● Le bénévole peut créer des tâches pour les élèves qu’il suit.
```

# Livrables 

- Un document PDF contenant les diagrammes de cas d’usage.
- Un document PDF contenant les user stories avec critère(s) d’acceptation.
- Un document PDF contenant les maquettes du site.
- Un document TXT contenant le lien vers le tableau Kanban (Notion, Trello, or GitHub).