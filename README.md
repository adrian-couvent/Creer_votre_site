# Objectif création de site web pour le projet

Première question: Avez vous vos ordinateurs?

## Pourquoi un site web quand on a GitHub

Pour cela on va réaliser une carte mentale en rapport avec un site web (son objectif par rapport au projet, par rapport au financeur, ses fonctions) (**-> 10-15 minutes**)

Bien comprendre la différence entre GitHub et un site web (**-> 20-25 minutes d'échanges**)

- Réflexion en groupe sur ce que permet GitHub qu'un site ne permet pas
- Inversement ce qu'un site permet et que GitHub ne permet pas

Echange et obtention d'une liste de différnece entre GitHub et Site web

Conclusion: (**10 minutes**)

- Le site permet de partager de l'information aux personnes totalement extérieur au projet. Ces informations ne seront pas technique mais une vulgarisation. Au même titre qu'en entreprises, il est intéressant d'y présenter: les objectifs du projets, l'équipe, les dernières réalisations et le plus important la possibilité de vous contacter.
- Pour un projet, l'utilisation d'un site est donc un bon moyen pour: mettre en avant les différents développement réalisés et renseigner des indicateurs permettant de juger de vos résultats (nommé KPI).
- GitHub est l'allier idéal pour un partage des informations techniques relative au projet mais ce n'est pas celle-ci que vous présenterez "au public" en général.
- Par contre votre site doit s'appuyer sur GitHub permettant ainsi de mettre vos travaux en valeurs et de montrer l'avancement de votre projet. Si Github est un indispensable technique pour le partage de code, la remonter d'erreur et la réalisation de test unitaire. Un site web "vitrine" est une quasi obligation quelque soit votre projet avec ou sans nécessité technique. Un site web est comme un local ouvert sur le monde entier, pour vous faire connaître c'est un outils nécessaire.

## Créer votre site web grâce à github

L'objectif ici est de créer un site web "vitrine" de votre projet. Ce site a pour objectif de réaliser une présentation de votre projet et de l'équipe de ce dernier. Vous pourrez l'utiliser le jours de l'oral si vous le désirez.

De manière général, nous allons voir rapidement l'achitecture d'un site web et la mise en oeuvre dans notre cas.

### Principe rapide d'un site web

Un **site web** est un ensemble de pages web et de ressources reliées entres elles par des hyperliens. Le site est accessible par **une adresse web nommée URL**. Afin de fonctionner il a besoin **d'un serveur web** qui est en fait un ordinateur connecté à internet sur lequel un ou des sites web sont hébergés. Les ordinateurs, smartphones ou tablettes s'y connectant pour le consulté sont des **client**

![Schématisation du site web](https://i0.wp.com/www.playhooky.fr/wp-content/uploads/2019/10/Playhooky.fr-Du-serveur-au-navigateur.png?resize=1024%2C385&ssl=1)

Si différentes technologie de server web existent nous allons faire simple en utilisant github qui regroupe toute ce dont nous aurons besoin pour vos projet. Github inclut une solution nommée [GitHub Pages](https://pages.github.com/). Cette solution permettra de créer une page web statique. Et vous n'aurez pas besoin de plus pour votre projet. Cette méthode peut être utilisée aussi pour vous créer une page web personnelle.

### Créer votre site web avec Github:

Pour cela rien de plus simple. Vous créez une nouveau projet sur votre dépôt Github. Juste faites attention **votre projet doit se nommer: username.github.io**

![Exemple du projet à créer pour une page web github](https://cdn.kastatic.org/ka-perseus-images/c6725e26e2668e6072d0905232e28dc24e34c069.png)

Une fois votre projet créé, clonez le sur votre ordinateur comme lors de [notre premier TP](https://github.com/jmtrivial/tp-git).

Maintenant vous allez y ajouter un site dont le design est issu du site: [https://html5up.net/](https://html5up.net/)

Décompressez le design qui vous plaît dans le dépôt local sur votre ordinateur puis décompressez le.

### Modifier le design choisi

#### Utiliser VS Code + Live Server pour créer votre site GitHub

Visual Studio Code (VS Code) est l’éditeur que nous utilisons pour modifier les fichiers de notre site web.  
L’extension **Live Server** permet d’afficher le site dans un navigateur web avec une mise à jour automatique à chaque sauvegarde.

##### Principe

- VS Code sert à **écrire et modifier** les fichiers du site (HTML, CSS, images, etc.).
- Live Server sert à **voir le rendu réel du site** dans un navigateur, comme s’il était déjà en ligne.
- À chaque sauvegarde, la page se recharge automatiquement.

Cela permet de travailler de manière **visuelle (WYSIWYG)** tout en gardant un code propre et compatible avec GitHub Pages.

---

##### Mise en place

1. Installer **Visual Studio Code**  
  https://code.visualstudio.com
  
2. Installer l’extension **Live Server**
  
  - Ouvrir l’onglet Extensions dans VS Code
  - Rechercher *Live Server*
  - Cliquer sur Installer
3. Ouvrir le dossier du site dans VS Code
  
4. Ouvrir le fichier `index.html`
  
5. Clic droit → **Open with Live Server**
  

Le site s’ouvre alors dans votre navigateur (exemple : `http://127.0.0.1:5500`) et se met à jour automatiquement.

---

##### Pourquoi c’est idéal avec GitHub Pages

- Le site affiché avec Live Server est **exactement le même** que celui publié sur GitHub Pages.
- Vous pouvez :
  - Modifier le contenu
  - Vérifier le rendu
  - Puis publier avec `git push`

VS Code + Live Server permet donc de travailler **localement, visuellement et proprement** avant de publier votre site en ligne.

Voilà maintenant vous pouvez réaliser un site dédié à votre projet.

Pour rappel sur site, on s'attend à trouver:

1. Une description du projet
2. Une description de votre équipe
3. Des liens vers votre dépôt github pour les différents documents

Ne tiens qu'à vous d'ajouter encore plus de choses!

### Conclusion

Pour mettre en valeur, un site web sera attendu. L'objectif est de faire une page simple incluant une description du projet, de l'équipe et des réalisations votre niveau de maturité sur le projet.
