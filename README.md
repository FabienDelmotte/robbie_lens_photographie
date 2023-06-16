# Robbie Lens Photographie

## Maîtrisez les bases de HTML5

### Créez votre première page web en HTML

Pour cet exercice, vous allez devoir partir de votre fichier `index.html` que vous venez de créer pour :

- y insérer la structure de base HTML ;
- changer le contenu de la balise `<title> </title>` pour avoir “Accueil – Robbie Lens Photographie” ;
- écrire un commentaire dans `<body> </body>`.

### Organisez votre texte

La photographe Robbie Lens nous a demandé de lui faire un site web pour mettre en avant son travail. Mais il va lui falloir également une page pour se présenter. Pour l'occasion, nous avons donc ajouté du contenu dans le fichier index.html et créé une nouvelle page :a-propos.html.
Vous allez :

- créer le titre dans la page `a-propos.html` : "À propos de Robbie Lens" ;
- créer le paragraphe associé : "Photographe depuis plus de 5 ans, je réalise des reportages aux photos dynamiques et pertinentes pour vos projets de communication. Créativité, qualité, et sérénité pour vous ! Je gère tout, depuis la direction artistique, la réalisation du reportage, jusqu’à la livraison de vos photos retouchées, prêtes à l’emploi." ;
- créer un titre de niveau 2 pour ajouter une section nommée : "Services" ;
- créer une liste non ordonnée pour lister les spécialités de Robbie Lens :
  - Portrait seul ou à plusieurs,
  - Shooting mode,
  - Retouches sur mesure,
  - Développement.

### Créez un lien hypertexte en HTML

Vous allez maintenant pouvoir mettre en pratique ce que vous venez d'apprendre sur les liens. Exceptionnellement pour cet exercice, la page `a-propos.html` a été déplacée dans un dossier `dossier-demo` afin que vous puissiez tester votre compréhension des liens relatifs.
Pour cet exercice, votre mission, si vous l'acceptez, est de :

- créer sur la page d'accueil un lien vers la page "À propos" (sans déplacer les fichiers) ;
- créer sur la page `a-propos.html` un lien vers la page d'accueil (sans déplacer les fichiers) ;
- ajouter les liens vers les réseaux sociaux (qui s'ouvrent dans un nouvel onglet) sur la page d'accueil et la page "À propos" :
  - pour Twitter, vous redirigerez vers <https://twitter.com/>,
  - pour Instagram, le lien pointe vers <https://www.instagram.com/>.

### Insérez des images

Vous allez maintenant pouvoir enrichir le portfolio de Robbie Lens. Pour cela, vous devrez :

- remplacer les liens Twitter et Instagram en bas des pages "À propos" et "Accueil" par les icônes correspondantes ;
- insérer l'image de Robbie Lens sur la page d'accueil (le fichier s'appelle `robbie-lens.png`) ;
- afficher tout en haut et tout en bas de la page le logo qui renvoie sur la page d'accueil grâce à un lien.

## Mettez en forme vos pages web avec CSS3

### Intégrez le CSS dans la page HTML

Ici, vous allez :

- créer un fichier CSS commun `style.css` ;
- appliquer la couleur `black` à l'ensemble des liens ;
- mettre le logo et les liens de navigation en haut des pages "Accueil" et "À propos" dans une balise `div` ;
- mettre les différents logos en bas des deux pages dans une autre `div` ;
- sur la page d'accueil, dans le paragraphe d'introduction, vous allez appliquer le style suivant : `color: #A5B4FC;` au mot "professionnalisme" et au mot "passion". Pour l'instant, vous utiliserez un `<span>`, mais nous le modifierons dans le prochain chapitre pour utiliser `<em>`.

### Changez l'apparence du texte

Vous allez :

- importer les deux polices principales du projet avec Google Font : Montserrat et Manrope ;
- assigner les propriétés de polices suivantes :
  - les titres H1 :
    - `3.5em` ;
    - en couleur `#A5B4FC` ;
    - police Montserrat ;
  - les paragraphes :
    - `1.1em` ;
    - police Manrope ;
  - les listes :
    - `1em` ;
    - police Manrope ;
  - les liens :
    - enlever le soulignement ;
    - `1em` ;
    - police Manrope ;
- remplacer les `<span class="important"></span>` par des éléments `em` tout en gardant le même style.

### Ajoutez de la couleur et un fond

Vous devrez :

- changer les couleurs de fond pour que :
  - la `div`dans laquelle on a les liens en haut des pages, et le pied de page, aient un fond blanc ;
  - le cœur de la page ait un fond correspondant à `#1F2039` ;
- et les couleurs de texte pour que :
  - les liens en tête et pied de page soient de couleur `#242424` ;
  - les paragraphes, les listes et les titres H2 soient de la couleur `#F9F8FF` (sur fond bleu foncé).

Vous trouverez également des liens hypertextes qui ont été ajoutés : "Un projet ? Écrivez-moi" et "Voir mon portfolio". Vous devrez leur ajouter un dégradé qui passe de la couleur `#8E86B5` à la couleur `#ACAEED` et les mettre dans la police Montserrat, en blanc.

C'est normal si votre couleur de fond a une petite marge, nous corrigerons cela plus tard.
