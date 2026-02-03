# Design d'interfaces

Le but de ce cours est de vous donner les bases théoriques, graphiques et les bonnes pratiques en terme de design d'interfaces et d'expérience utilisateur.

Pour cela, nous allons nous pencher sur les divers éléments importants dans une interface ainsi que sur les livrables à utiliser. Ce cours se veut être un guide pratique pour réaliser efficacement des designs pour le web, qu'il s'agisse d'un site ou d'une application.

1. Gamme de couleurs
2. Typographie
3. Layout, grilles, espacements et mise en page
4. Exercices

## 1. Couleurs

Ici, il vous faudra faire preuve de mesure. Dans la plupart des cas, une couleur principale (déclinée) et une couleur d'accent (déclinée également) ainsi qu'une gamme de gris (basés sur votre couleur principale) pour les couleurs neutres suffiront largement. Certaines applications ou sites ont des palettes de couleurs plus étendues mais il est préférable de rester le plus simple possible.

Commencer par choisir une couleur principale en rapport avec votre branding ou qui vous plait. Pour le choix de la couleur complémentaire, des outils peuvent vous aider, comme [Adobe Color CC](https://color.adobe.com/create/color-wheel/) ou [Coolors](https://coolors.co/). Pensez également à aller faire un tour sur [Dribbble](https://dribbble.com/colors/3116EF) et à utiliser l'outil de recherche par couleur pour immédiatement avoir un grand choix de couleurs complémentaires.

Une fois que vous avez vos couleurs complémentaires, vous pouvez utiliser votre application de design favorite et [des techniques reposant sur des layers](https://www.smashingmagazine.com/2017/07/advanced-color-palettes-photoshop-sketch-affinity-designer/) pour démultiplier vos options tout en restant dans la gamme. Il vous reste ensuite à déterminer une gamme de gris contenant votre couleur principale et vous voilà paré.

Une autre méthode efficace pour créer une palette de de couleurs harmonieuse consiste à partir de photos de paysages / de nature. Adobe Color CC possède une fonction qui vous y aidera.

Un dernier conseil, [évitez le noir pur dans vos palettes](https://ianstormtaylor.com/design-tip-never-use-black/). Afin d'être dans la gamme partez plutôt de votre couleur de base et saturez-là pour obtenir une couleur proche du noir mais contenant votre couleur de base. Vous pouvez aussi travailler avec un layer noir sur votre couleur de base en réglant son opacité à 90 ou 95%.

_Exercice: créer une palette de couleurs simple_

## 2. Typographie

Comme le dit fort justement Oliver Reichenstein, [le texte compose 95% d'un site web, d'une application ou d'une interface en général](https://ia.net/topics/the-web-is-all-about-typography-period). La typographie est donc une étape importante dans la conception de tout produit digital.

Il va falloir choisir une ou deux polices et ensuite créer un échelle typographique sur laquelle baser nos interlignes et nos espacements verticaux.

### Choix de polices

En général on travaillera avec un nombre limité de polices et un nombre limité de variantes en termes de graisses et de styles.

_Exercice: Google Font et poids des fichiers de police_

Votre premier choix devra sans doute être la police que vous utiliserez pour votre corps de texte. Il vous faut une police solide et de lisible qui permettra aux autres éléments textuels importants (titres, calls to action) de ressortir. Préférez des polices avec une x-height élevée et peu de fioritures. Soyez également attentif à ce que la police choisie possède plusieurs graisses et variantes (au moins bold et italique). Les polices avec plusieurs graisses sont intéressantes de par la variété potentielle qu'elles proposent. Des polices variables sur plusieurs axes puevent vous donner encore plus de flexibilité.

Si vous vous posez des questions, regardez simplement dans quel but ou contexte la police que vous considérez a été développée, explorez son histoire. Des services tels que Typekit ou Google fonts vous donnerons des renseignements précieux. Ces services possèdent également des spécimens qui vous permettrons de mieux appréhender les caractéristiques des divers fontes proposées. Allez également faire un petit tour du côté des sites tels que [Typewolf](https://www.typewolf.com/), [Fonts in Use](https://fontsinuse.com/) ou [Dribbble](https://dribbble.com/).

Un exercice difficile en typographie consiste à trouver plusieurs polices qui vont fonctionner ensemble dans un design. Une fois votre police de corps de texte choisie, vous avez plusieurs options:

- **Superfamilies**: certaines polices forment une famille de polices et sont conçues comme telles. Elles contiennent souvent des polices différentes (serif et sans-serif par exemple), utilisables à différentes tailles (caption, display, etc.) ou ayant différentes approches / kernings (Normal, Condensed, Extended). En voici quelques exemples sur Typekit: Calluna et Calluna Sans, Freight Text et Freight Sans, etc.
- **Designer / Fondrie identique**: voici un raccourci par rapport au point suivant. En général, des polices même différentes au premier regard on pas mal de caractéristiques communes si elles sont conçues par la même personne ou la même fondrie. Pensez donc à aller voir de ce côté lorsque vous cherche un accord entre deux polices.
- **Caractéristiques communes**: cherchez des polices qui sont suffisamment différentes que pour êtres distinguées facilement l'une de l'autre mais qui ont des caractéristiques communes (formes des lettres, x-height, etc.) ou qui ont été développées dans un même contexte ou selon un concept similaire.
- **Outils**: des outils et services tels que Google Fonts ou Typekit vous proposent des pistes intéressantes pour le font pairing. N'hésitez pas non plus à inspecter des sites que vous appréciez au niveau typographique.

_Exercice: Voici [quelques](http://femmebot.github.io/google-type/) [exemples](http://hellohappy.org/beautiful-web-type/) de typographies réussies avec Google fonts. Analysons-les._

_Exercice: choisir deux polices_

### Compositions typographiques

Un élément important dans vos compositions typographiques est de faire varier les caractéristiques de vos éléments pour créer du contraste, des tensions et des similitudes. Vous avez pour ce faire beaucoup d'outils à votre disposition:

- familles (`font-family`): serifs, sans-serifs, display, etc.
- graisses (`font-weight`): black, bold, medium, etc.
- taille (`font-size`): pixels, rem, em, etc.
- casse (`text-transform`): uppercase, lowercase, etc.
- styles (`font-style`): normal, italique
- ornements: glyphs, ligatures, etc.
- couleurs (`color`): noir, rouge, gris, etc.
- alignement (`text-align`): left, right, center, justify
- espace (`margin`, `padding`, `line-height`, `letter-spacing`): margins, paddings, interligne, letter spacing

_Exercice: chercher chacun 1 composition typographiques sur Dribble et expliquer quels sont les outils utilisés_

_Exercice: chercher et trouver deux polices complémentaires_

### Echelle typographique et rythme vertical

Une fois vos polices choisies, l'étape suivante consiste à mettre en place une échelle typographique et un rythme vertical. Pour ce qui est de l'échelle typographique, vous pouvez-vous appuyer sur "[Modular Scale](https://www.modularscale.com/)" un outil développé par [Tim Brown](http://tbrown.org/).

Pour ce qui est du rythme vertical, le plus facile est de prendre un échelle à laquelle vous allez vous tenir pour ce qui est de l'interligne et de tous les espaces verticaux. Les échelles les plus populaires sont les échelles [de cinq](https://guides.area17.com/design-techniques/#baseline-grid), de six ou de [huit](https://themefoundation.com/vertical-rhythm-responsive-typography/).

Personnellement, je ne souscris pas forcément à une baseline grid stricte comme en print pour des projets d'interfaces ou digitaux. Par contre, il faut être attentif à avoir un rythme vertical aussi cohérent que possible en essayant que tous les espacements verticaux ainsi que les hauteurs de lignes soient des multiples de l'échelle de base.

Cette grille typographique sert également à la gestion des espaces entre les divers éléments de votre ihterface.

_Exercice: rythme vertical et typographie pour trois cartes côte à côte (images, titre, intro, call to actions)_

_Exercice: analyse rythme vertical et sections_

## 3. Layout et mise en page

En design, les grilles sont un outil essentiel. Elles vous permettent de structurer vos contenus et de créer des mises en page complexes dont les éléments sont connectés les uns au autres par une structure sous-jacente.

> Nothing could be more useful to reach our intention than the Grid. The grid represents the basic structure of our graphic design, it helps to organize the content, it provides consistency, it gives an orderly look and it projects a level of intellectual elegance that we like to express. - Massimo Vignelli, The Vignelli Canon [The Vignelli Canon](https://www.rit.edu/vignellicenter/sites/rit.edu.vignellicenter/files/documents/The%20Vignelli%20Canon.pdf).

Il existe deux grandes méthodes pour créer ces grilles:

- **Grilles content out**: grilles conçues à partir des contenus et des contraintes du projet (publicités, unités typographiques, longueur de lignes, etc.)
- **Grilles canvas in**: partir de vos différents breakpoints et designer plusieurs grilles.

Ces grilles peuvent être de différents types:

- **Grilles symétriques**: toutes les colonnes sont de même taille. Vous avez la possibilité de combiner deux grilles pour plus de variété (une grille de 10 et une grille de 12 par exemple)
- **Grilles asymétriques**: certaines colonnes sont de différentes tailles, à nouveau en se basant sur les contraintes du projet ou certaines éléments (menu latéral, compound grids)

Les grilles les plus courantes sont des grilles symétriques, souvent de 12 colonnes car 12 offre l'avantage d'être divisible par 2, 3 ou 4.

Si un nombre de colonnes pair comme 8, 10, 12 ou 18 apporte un grand équilibre et une grande symétrie, ce genre de grilles peut parfois être ennuyeux. Les grilles ayant un nombre de colonnes impair 5, 7, 9 sont légèrement plus difficiles à maîtriser mais apportent un dynamisme intéressant.

En parlant de dynamisme, n'oubliez pas que vous pouvez avoir des grilles sans gutter ou encore laisser des colonnes vides dans vos designs.

## 4. Exercices

- **Générique**: Choisir un film et créer à l'échelle un écran de générique statique contenant: le titre du film, la personne l'ayant réalisé, le casting principal et une citation extraite du film.
- **Courant musical et animaux**: choisir un aniimal et un courant musical et créer à l'échelle un layout mobile mettant en scène l'animal en utilisant des codes graphiques issus du courant musical.
- **Jeu vidéo**: réaliser un écran d'inventaire pour un jeu video fictif
