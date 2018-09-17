# Design d'interfaces

Le but de ce cours est de vous donner les bases théoriques, graphiques et les bonnes pratiques en terme de design d'interfaces et d'expérience utilisateur, que cela soit pour des sites de contenus ou des applications.

Pour cela, nous allons nous pencher sur les divers éléments importants dans un design web ainsi que sur les livrables à utiliser.

## Principes de base

Sur le web, les designers doivent gérer trois grandes inconnues, auxquelles répondent trois grands principes.

### L'inconnue du canevas & mobile first responsive design

En print comme en vidéo, le canevas du produit fini est connu. Il s’agit d’une affiche de telle dimensions, d’une brochure en format A5 de 20 pages, d'un sport publicitaire de 3 minutes pour la télévision, etc. Il en va tout autrement sur le web où le concept même de canevas sur lequel baser un design disparait devant la diversité des supports sur lesquels les sites et applications doivent fonctionner (tailles, résolutions et orientations d’écrans, etc.).

La philosophie du **mobile first responsive design** répond à cette première inconnnue. Si nous ne pouvons plus baser nos designs sur le canevas, nous devons alors [partir des contenus](https://markboulton.co.uk/journal/a-richer-canvas) et des contraintes pour designer non plus des pages mais bien des [systèmes de composants flexibles](http://styleguides.io/) pouvant s’agencer de diverses façons pour occuper et s’adapter à un maximum de canevas possibles.

- **grilles fluides**: d'une grille simple de deux colonnes sur petits écrans, on peut passer à une grille de plus en plus complexe au fur et à mesure que l'espace disponible augmente. Les nouvelles spécifications de layout en CSS (Flexbox et Grid) sont adaptées à cette approche.
- **media flexibles**: pour s'intégrer à une grille fluides, vos media (images, video, etc.) doivent être flexibles et non de tailles fixes. Grâce à quelques règles CSS, il est possible d'adapter la taille de vos media aux containers dans lesquels ils se trouvent.
- **media queries**: le mécanisme CSS grâce auquel le code CSS (layout, typographie, etc) est capable de "répondre" à une grande palettes de paramètres du navigateur client (largeur d'écran, orientation, couleurs, etc.)

### L'inconnue des capacités du terminal & progressive enhancement

En print ou en vidéo, une fois un design créé, son rendu est contrôlable et contrôlé de bout en bout: de la conception jusqu’à la diffusion finale.

Au niveau du web, tout passe par deux canaux que le concepteur ne contrôle pas et dont vont largement dépendre l'expérience utilisateur: le navigateur et le terminal sur lequel celui-ci est hébergé. Là aussi, nous avons affaire à une large diversité de capacités: support tactile, bande passante, support images, support vidéos, support CSS, support javascript, gyroscope, appareil photo, géolocalisation, etc.

Lorsque nous envisageons des solutions de design, nous devons tenir compte de cette seconde inconnue. Dans l’industrie, on se réfère souvent au concept de **progresssive enhancement** selon lequel on va d’abord se concentrer sur le fait de délivrer une bonne expérience utilisateur de base, que l’on va enrichir pour les navigateurs et terminaux disposant de capacités plus avancées.

Selon Jeremy Keith dans "[Resilient Web Design](https://resilientwebdesign.com/chapter6/)", cette idée repose sur trois étapes simples:

1. Identifier les fonctionalités ou les contenus principaux / essentiels
2. Rendre disponibles ces contenus ou ces fonctionalités à l'aide des technologies les plus silmples possibles
3. Construire sur cette base en utilisant les technologies plus modernes

### L'inconnue du contexte d'utilisation & user centered design

Si nous pouvons en général définir assez précisément nos publics cibles (à travers des études de marché, des personas, etc.), le contexte d’utilisation d'un site ou d'une application peut varier grandement et nous est la plupart du temps complètement inconnu.

L’utilisateur mobile peut utiliser son téléphone debout dans son train matinal, être facilement distrait, ne disposer que d’une seule main et d’une connectivité faible. Ce même utilisateur mobile peut utiliser sa tablette, confortablement installé dans le canapé du lobby de son entreprise. Il est dans ce cas très concentré et dispose d’une connexion à haut débit. Les circonstances et le contexte d’utilisation est tout aussi divers pour un utilisateur d’ordinateur fixe.

La solution est ici de toujours centrer les solutions sur l'utilisateur. C'est ce que préconise le **User Centered Design**

- impliquer les utilisaturs très tôt dans la définition des solutions envisagées
- passer par des cycles d'itérations courts: prototypes, tests et feedback utilisateurs

Depuis quelques années, [Thoughtbot](https://thoughtbot.com/) et [Google Ventures](http://www.gv.com/sprint/) ont popularisé un outil: le Design Sprint. L'idée est de passer en 5 jours seulement d'un simple concept à un prototype concret et testé par des utilisateurs.

- jour 1: comprendre les utilisateurs, leurs besoins et leurs contextes (côté utilisateurs) ainsi que les objectifs à atteindre et les KPIs (côté business). Identifier aussi les risques potentiels et les moyens de les réduire.
- jour 2: diverger en proposant (sketch et pitch) différentes solutions possibles aux problèmes et au contexte posés préalablement.
- jour 3: converger en se mettant d'accord sur une ou deux solutions à prototyper
- jour 4: prototyper les solutions en ayant un degré de fidélité juste suffisant que pour pouvoir réaliser les tests utilisateurs
- jour 5: tester le(s) prototype(s) avec des utilisateurs et évaluer

Si vous souhaitez en savoir plus concernant le design sprint, [le petit guide online de Thoughtbot](https://thoughtbot.com/product-design-sprint/guide) est très bien fait et vous donne quelques examples d'activités ou d'exercices à réaliser avec vos clients.

## En pratique

Après avoir introduit le sujet par un peu de théorie, passons à la pratique. La suite de ce cours se veut être un guide pratique pour réaliser efficacement des designs pour le web, qu'il s'agisse d'un site ou d'une application.

1. Recherche et stratégie
2. Couleurs
3. Typographie
4. Layout et mise en page
5. Livrables pour le design web

### 1. Recherche et stratégie

La phase de recherche vise à cerner les tenants et aboutissants du projet, tant du point de vue des utilisateurs (publics cibles, besoins, contexte) que du business (objectifs, KPI, compétition).

La permière chose à faire est de bien cerner quels sont les publics cibles. Pour cela, rien ne remplace un contact direct avec des utilisateurs ou, à défaut, avec les responsables du support ou du marketting qui sont en contact avec eux. De simples activités comme un future perfect / pitch, des [proto-personas](https://uxmag.com/articles/using-proto-personas-for-executive-alignment) (voici des [photos utilisables créées par Jason Travis](http://www.jasontravisphoto.com/persona/)) et quelques [job stories](https://jtbd.info/replacing-the-user-story-with-the-job-story-af7cdee10c27) par persona peuvent déjà s'avérer très utiles.

En regard des personas, il importe de se pencher sur les objectifs business. Pour chaque personas, demandez-vous comment votre site ou votre application peut les aider. De manière plus générale, quels sont les indicateurs (mesurables) qui vous permettront de dire si votre projet à atteint ses objectifs et rencontre les besoins des clients.

Lors de cette phase de recherche, il est bon de se pencher sur la compétition. Quels sont les sites ou les aplications qui répondent aux même besoins? Quels sont leurs points forts et leurs points faibles?

Au niveau du design, deux exercices sont assez utiles.

- *Adjectifs et priorités*: demander à tous de noter sur un post-it trois adjectifs qu'ils souhaitent que les clients ressentent en visitant le site ou en utilisant l'application. Chacun vote ensuite pour deux adjectifs et les trois plus importants sont classés par priorité.
- *Design brief à l'instinct*: rassembler 15 à 20 sites ou applications avec des styles graphiques très différents. Ces exemples sont passés en revue et chacun donne une note de 1 à 5. Une fois les moyennes établies, discuter des 3 premiers et des trois derniers vous donnera un bon design brief.

Les dernières choses à aborder tiennent à la structure générale de l'application ou du site. Une architecture d'information et / ou des [wireflows](https://dribbble.com/shots/2248785-Web-Wireframes-UX-Flow/attachments/420198) réalisés en petits groupes peuvent vous donner une bonne approximation de la structure souhaitée. Il s'agit d'un élément important dans la mesure où il va être matérialisé par les interfaces de navigation qui sont une contrainte importante au niveau du design.

*Exercice: @TODO*

### 2. Couleurs

Ici, il vous faudra faire preuve de mesure. Dans la plupart des cas, une couleur principale (déclinée) et une couleur d'accent (déclinée également) ainsi qu'une gamme de gris (basés sur votre couleur principale) pour les couleurs neutres suffiront largement. Certaines applications ou sites ont des palettes de couleurs plus étendues mais il est préférable de rester le plus simple possible.

Commencer par choisir une couleur principale en rapport avec votre branding ou qui vous plait. Pour le choix de la couleur complémentaire, des outils peuvent vous aider, comme [Adobe Color CC](https://color.adobe.com/create/color-wheel/) ou [Coolors](https://coolors.co/). Pensez également à aller faire un tour sur [Dribbble](https://dribbble.com/colors/3116EF) et à utiliser l'outil de recherche par couleur pour immédiatement avoir un grand choix de couleurs complémentaires.

Une fois que vous avez deux (maximum trois) couleurs complémentaires, vous pouvez utiliser votre application de design favorite et [des techniques reposant sur des layers](https://www.smashingmagazine.com/2017/07/advanced-color-palettes-photoshop-sketch-affinity-designer/) pour démultiplier vos options tout en restant dans la gamme. Il vous reste ensuite à déterminer une gamme de gris contenant votre couleur principale et vous voilà paré.

Une autre méthode efficace pour cérer une palette de de couleurs harmonieuse consiste à partir de photos de paysage / de nature. Adobe Color CC possède une fonction qui vous y aidera.

Un dernier conseil, [évitez le noir pur dans vos palettes](https://ianstormtaylor.com/design-tip-never-use-black/). Afin dêtre dans la gamme partez plutôt de votre couleur de base et saturez-là pour obtenir une couleur proche du noir mais contenant votre couleur de base.

*Exercice: créer une palette de couleurs simple*

### 3. Typographie

Comme le dit fort justement Oliver Reichenstein, [le texte compose 95% d'un site web ou d'une application](https://ia.net/topics/the-web-is-all-about-typography-period). La typographie est donc une étape importante dans la conception de tout produit digital.

Il va falloir choisir une ou deux polices et ensuite créer un échelle typograohique sur laquelle baser nos interlignes et nos espacements verticaux.

#### Choix de polices

Pour commencer, il est important de poser des limites. Les fichiers de polices sont des ressources externes et charger une police, une graisse ou un style supplémentaire ajoutera au poids de vos pages. En général on travaillera donc avec une ou deux polices maximum et un nombre limité de variantes en termes de graisses et de styles.

*Exercice: Google Font et poids des fichiers de police*

Votre premier choix devra sans doute être la police que vous utiliserez pour votre corps de texte. Il vous faut une police solide et de lisible qui permettra aux autres éléments textuels importants (titres, calls to action) de ressortir. Préférez des polices avec une x-height élevée et peu de fioritures. Soyez également attentif à ce que la police choisie possède plusieurs graisses et variantes (au moins bold et italique). Les polices avec plusieurs graisses sont intéressantes de par la variété potentielle qu'elles proposent.

Si vous vous posez des questions, regardez simplement dans quel but ou contexte la police que vous considérez a été dévelopée, explorez son histoire. Des services tels que Typekit ou Google fonts vous donnerons des reseignements précieux. Ces services possèdent également des spécimens qui vous permettrons de mieux appréhender les caractéristiques des divers fontes proposées. Allez également faire un petit tour du côté des sites tels que [Typewolf](https://www.typewolf.com/), [Fonts in Use](https://fontsinuse.com/) ou [Dribbble](https://dribbble.com/).

Un exercice difficile en typographie consiste à trouver plusieurs polices qui vont fonctionner ensemble dans un design. Une fois votre police de coprs de texte choisie, vous avez plusieurs options:

- **Superfamilies**: certaines polices forment une famille de polices et sont designées comme telles. Elles contiennent souvent des polices différentes (serif et sans-serif par exemple), utilisables à différentes tailles (caption, display, etc.) ou ayant différentes approches / kernings (Normal, Condensed, Extended). En voici quelques exemples sur Typekit: Calluna et Calluna Sans, Freight Text et Freight Sans, etc.
- **Designer / Fondrie identique**: voici un raccourci par rapport au point suivant. En général, des polices même différentes au premier regard on pas mal de caractéristiques communes si elles sont designées par la même personne ou la même fondrie. Pensez donc à aller voir de ce côté lorsque vous cherche un accord entre deux polices.
- **Caractéristiques communes**: cherchez des polices qui sont suffisamment différentes que pour êtres distinguées facilement l'une de l'autre mais qui ont des caractéristiques communes (formes des lettres, x-height, etc.) ou qui ont été développées dans un même contexte ou selon un conceopt similaire.
- **Outils**: des outils et services tels que Google Fonts ou Typekit vous proposent des pistes intéressantes pour le font pairing. N'hésitez pas non plus à inspecter des sites que vous appréciez au niveau typographique.

*Exercice: Voici [quelques](http://femmebot.github.io/google-type/) [exemples](http://hellohappy.org/beautiful-web-type/) de typographies réussies avec Google fonts. Analysons-les.*

*Exercice: choisir deux polices*

#### Compositions typographiques

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

*Exercice: chercher 5 compositions typographiques sur Dribble et expliquer quels sont les outils utilisés*

*Exercice: utiliser la typographie et Google fonts pour designer les divers éléments d'un blogpost et des paroles d'un track de hip-hop, d'abord dans Figma et puis dans le code*

#### Echelle typographique et rythme vertical

Une fois vos polices choisies, l'étape suivante consiste à mettre en place une échelle typographique et un rythme vertical. Pour ce qui est de l'échelle typographique, vous pouvez-vous appuyer sur "[Modular Scale](https://www.modularscale.com/)" un outil développé par [Tim Brown](http://tbrown.org/).

Pour ce qui est du rythme vertical, le plus facile est de prendre un échelle à laquelle vous allez vous tenir pour ce qui est de l'interligne et de tous les espaces verticaux. Les échelles les plus populaires sont les échelles [de cinq](https://guides.area17.com/design-techniques/#baseline-grid), de six ou de [huit](https://themefoundation.com/vertical-rhythm-responsive-typography/).

Personellement, [je ne souscris pas forcément à une grille stricte](http://jasonsantamaria.com/articles/baseline-grids-on-the-web) (baseline grid) difficile à maintenir sur un médium aussi fluide que le web. Par contre, il faut être attentif à avoir un rythme vertical aussi cohérent que possible en essayant que tous les espacements verticaux ainsi que les hauteurs de lignes soient des multiples de l'échelle de base.

Cette grille typographique sert également à la gestion des espaces dans les composants: boutons, listes et autres éléments utilisent également cette grille typographique.

*Exercice: rythme vertical et typographie pour trois cartes côte à côte avec des boutons de call to action*

*Exercice: rythme vertical et sections d'un layout*

### 4. Layout et mise en page

En design, les grilles sont un outil essentiel. Elles vous permettent de structurer vos contenus et de créer des mises en page complexes dont les élements sont connectés les uns au autres par une structure sous-jascente.

  > Nothing could be more useful to reach our intention than the Grid. The grid represents the basic structure of our graphic design, it helps to organize the content, it provides consistency, it gives an orderly look and it projects a level of intellectual elegance that we like to express.

  > Massimo Vignelli. The Vignelli Canon

En venant du print et de ses canevas fixes, la question se pose naturellement, comment créer une grille alors que le canevas global change constamment?

La réponse est la même que pour le reste: vos grilles doivent être fluides. La technique la plus utilisée est de garder des gutters fixes, tandis que la largeur et le nombre de colonnes change. Là où un design sur petits écrans utilisera une grille de 2 ou 3 colonnes maximum, un design sur un grand écran peut utiliser 8, 10, 12 ou 16 colonnes par exemple.

*Exercice: reconstruire la grille du [New York Times](nytimes.com)*

*Exercice: reconstruire la grille de [Steele Brand Co](https://dribbble.com/shots/2899485-Steele-Brand-Co/attachments/600278)*

Il existe deux grandes méthodes pour créer ces grilles:

- **Grilles content out**: grilles designées à partir des contenus et des contraintes du projet (publicités, unités typographiques, longueur de lignes, etc.)
- **Grilles canvas in**: partir de vos différents breakpoints et designer plusieurs grilles.

Ces grilles peuvent être de différents types:

- **Grilles symétriques**: toutes les colonnes sont de même taille. Vous avez la possibilité de combiner deux grilles pour plus de variété (une grille de 10 et une grille de 12 par exemple)
- **Grilles asymétriques**: certaines colonnes sont de différentes tailles, à nouveau en se basant sur les contraintes du projet ou certaines éléments (menu latéral, compound grids)

Les grilles les plus courantes sur le web sont des grilles symétriques, souvent de 12 colonnes car 12 offre l'avantage d'être divisible par 2, 3 ou 4.

Si un nombre de colonnes pair comme 8, 10, 12 ou 18 apporte un grand équilibre et une grande symétrie, ce genre de grilles peut parfois être ennuyeux. Les grilles ayant un nombre de colonnes impair 5, 7, 9 sont légèrement plus difficiles à maîtriser mais apportent un dynamisme intéressant.

En parlant de dynamisme, n'oubliez pas que vous pouvez avoir des grilles sans gutter ou encore laisser des colonnes vides dans vos designs.

*Exercice: design d'une grille responsive symétrique pour trois tailles d'écran*

*Exercice: design d'une grille responsive asymétrique pour trois tailles d'écran*

*Exercice: expérimenter avec des colonnes vides*

### 5. Design web: documents de delivery

Afin de présenter les designs web dans tous leurs aspects, [le plus efficace est de le faire à l’aide de prototypes interactifs](https://www.webstoemp.com/blog/to-hell-with-abstract-prescriptive-deliverables/), plutôt que d’utiliser des documents et méthodes plus statiques qui posent problème à de nombreux niveaux.

#### Problèmes des documents statiques / uniques

Classiquement, les designs à l’aide de [wireframes](https://dribbble.com/shots/1893359-Exelerate-Wireframes/attachments/322535) statiques qui se transforment finalement en [chartes graphiques statiques détaillées](https://dribbble.com/shots/1874207-Exelerate-Product-view/attachments/317155) réalisées sur Sketch, Figma ou Photoshop. Cette manière de travailler provient du print mais n’est pas tpujours adaptée au design web pour diverses raisons.

##### Non prise en compte des spécificités du medium

Ces documents ne sont pas à même de matérialiser efficacement les spécificités du medium Internet que sont l’interactivité (survol des boutons, menus déroulant, accordéons, slideshows, animations, etc.), l’adaptation aux diverses tailles d’écran et résolutions (desktops, tablettes, mobiles, écrans haute résolution, etc.) et l'adaptation aux capacités du navigateur ou du terminal utilisé.

##### Représentation irréaliste du produit fini

De tels documents donnent une fausse image du produit fini. On habitue ainsi le client à voir une version "irréaliste" de son futur site.

La résolution des documents imprimés est plus élevée qu’un affichage sur écran, les pages sont présentées dans leur entièreté alors que, dans un navigateur, seule une petite portion en sera visible à la fois, les polices n’ont pas du tout le même rendu à l’écran.

Enfin, ces documents donnent l’impression que le site aura toujours le même rendu. Or, selon les navigateurs utilisés, un site n’a pas toujours la même apparence ni les mêmes comportements.

##### Dissociation des aspects de design et des aspects techniques

L’utilisation de documents statiques favorise une déconnexion entre le design et le code, entre l’expérience utilisateur et les moyens techniques permettant de la réaliser. Cette fracture cause de nombreuses pertes de temps, de malentendus et de frustrations entre développeurs et designers.

#### L’avènement des documents dynamiques

Pour ces diverses raisons et depuis un certain temps déjà, les web designers cherchent à travailler de façon plus rapide et itérative, en utilisant des documents moins lourds à produire, permettant des cycles de feedback plus fréquents et plus rapides et créant de ce fait une dynamique dans laquelle le client / commanditaire est plus impliqué.

##### Content prototypes

Pour ce qui est des contenus, de simples "[content prototypes](https://thomasbyttebier.be/blog/the-bold-beauty-of-content-prototypes)" réalisés en HTML brut permettent aux copywriters de travailler, à l'équipe d'avoir une référence mise à jour et au client de valider le copy.

Les avantages sont multiples:

- ces prototypes sont mobile first et permettent de tester la hiérarchie des contenus la data structure des différentes pages / vues et éléments
- une fois en ligne, ces prototypes peuvent être consultés et modifiés par tous
- les patterns de navigation et la forme des divers contenus peuvent être testés rapidement

##### Moodboards and elements collages

Plutôt que de fournir au client des “mockups” sur Sketch, Figma ou Photoshop dans lesquels les moindres éléments des pages sont designés, il est plus facile et plus rapide d’explorer diverses pistes graphiques à l’aide de ce que Dan Mall appelle des "[elements collages](http://v3.danielmall.com/articles/rif-element-collages/)".

De tels elements collages ou [moodboards](https://thomasbyttebier.be/blog/mood-boards-in-a-content-first-design-process) peuvent être produits relativement rapidement pour réaliser quelques itérations autour de concepts intéressants et d'éléments centraux du site / de l’application. Présenter les choses sous forme d'une longue page web permet aussi d'utiliser des videos ou un peu de JavaScript pour présenter des concepts plus interactifs ou dynamiques.

Sketch, Figma ou Framer sont encore présents dans le processus, mais la philosophie change.

Il ne s'agit plus de produire des designs finalisés mais de pouvoir rapidement tester et valider des idées pour ensuite pouvoir travailler de façon itérative et collaborative.

#### Designers hybrides

> [the design process] is about designing, prototyping and making. When you separate those, I think the final result suffers."

> Jonathan Ive, March, 2012

Cette phrase de Jonathan Ive pourrait sans problème être appliquée au web d’aujourd’hui, dans lequel le design, la création de prototypes et la réalisation technique sont de plus en plus intimement liés.

##### Les designers web doivent ils coder?

Pas forcément, mais cela aide beaucoup et cela permet de gagner du temps. Au minimum, designers et dévelopeurs doivent collaborer étroitement et avoir une bonne connaissance des modes de travail et défis recontrés par les uns et les autres est primordial.

Le travail des designers web à grandement évolué: nous devons maintenant créer des systèmes modulaires et flexibles et plus des interfaces fixes dans photoshop. Le nombre d’inconnues et d’élements entrant en ligne de compte dans un site Internet ne cesse d’augmenter.

Cela requiert des changements dans les processus et workflow utilisés mais aussi une plus grande collaboration et un dialogue plus étroit entre les différents intervenants.

> You must also address the very human issue of communication. Earlier and more frequent collaboration among team members and the client must become the rule in your workflow, not the exception. Content, design, and development team members must review and collaborate regularly at every stage in the creation process until the site is live. We can’t ‘throw it over the wall’ anymore— at least, not if we want our sites to be excellent. There are simply too many moving parts now. Go forth and collaborate.

> Drew Clemens - Smashing Magazine

*Exercice: réaliser un elements collage dans Figma*

## Ressources

- [Design Principles: Visual Perception And The Principles Of Gestalt](https://www.smashingmagazine.com/2014/03/design-principles-visual-perception-and-the-principles-of-gestalt/) - Smashing Magazine
- [Gestalt Principles: How Are Your Designs Perceived?](http://vanseodesign.com/web-design/gestalt-principles-of-perception/) - Vanseo Design
- [Dieter Rams: ten principles for good design](https://www.vitsoe.com/gb/about/good-design) - Vitsoe
- [Startups, this is how design works](https://startupsthisishowdesignworks.com/) - Wells Riley
- [Design techniques](https://guides.area17.com/) - Area17
- [Website Style Guides ressources](http://styleguides.io/) - Anna Debenham and the community
- [From print, to digital, and beyond …](https://www.youtube.com/watch?v=42RXq0fgP24) (video) - Mark Porter
- [Objectified](https://www.youtube.com/watch?v=e52fYCYiPok) (film) - Gary Hustwit
- [Exercices, ressources et déroulement d’un Design Sprint](https://github.com/thoughtbot/design-sprint) - Thoughtbot
- [Atomic Design](http://atomicdesign.bradfrost.com/chapter-1/) (particulièrement pour le premier chapitre) - Brad Frost
