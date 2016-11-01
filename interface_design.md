# Design d'interfaces

Le but de ce cours est de vous donner les bases théoriques, graphiques et les bonnes pratiques en terme de design d'interfaces et d'expérience utilisateur, que cela soit pour des sites de contenus ou des applications.

## Principes de base et perception

Voyons rapidement ensemble à quels grandes tendances obéit notre perception et sur quels principes nous pouvons nous baser pour nos designs. A ce sujet, je vous propose de nous pencher sur les principes de Gestalt appliqués au design et sur les 10 principes de "Good Design" énoncés par Dieter Rams. Nous terminerons par quelques conseils pratiques.

### Principes de Gestalt

La [théorie de la perception en Gestalt](https://www.smashingmagazine.com/2014/03/design-principles-visual-perception-and-the-principles-of-gestalt/) examine la manière dont nous percevons les choses et énonce quelques grands principes qu'il est bon d'avoir en tête lorsque nous créons nos designs. Connaître la façon dont vos utilisateurs fonctionne au niveau de la perception visuelle aide à créer des designs qui atteignent leurs objectifs.

1. **Principe de similarité**: les éléments qui partagent des caractéristiques similaires sont perçus comme étant liés. Un exemple type au niveau du web sont les caractéristiques communes aux liens dans un texte. Dans une interface de navigation, on peut également créer deux groupes de liens distincts en ayant un traitement graphique différents de ceux-ci.
2. **Principe de proximité**: les éléments qui sont placés les uns près des autres sont perçus comme étant d’avantage liés que des objets séparés par d’avantage d’espace. La gestion du whitespace dans vos design va permettre de créer des éléments perçus comme groupes et d'autres clairement séparés les uns des autres. Nous avons souvent tendance à ne pas assez utiliser le whitespace dans nos designs, ce qui diminue l’impact du principe de proximité.
3. **Principe de simplicité**: nous avons tendance à percevoir et à interpréter des images complexes de la façon la plus simple possible. Un groupe de formes simples sera interprété comme tel plutôt que comme la forme complexe formée par l'ensemble.
4. **Figure and ground**: naturellement, nous avons tendance à percevoir des éléments comme étant à l'avant plan et d'autres comme appartenant au décor. Il est possible de créer des ambiguïtés: un exemple célèbre et celui des visages ou du vase. L'interprétation du visuel dépend de ce que nous plaçons à l'avant et à l'arrière plan.
4. **Principe de fermeture (Closure)**: lorsque nous analysons nos perceptions visuelles, notre cerveau a naturellement tendance à combler les blancs. Deux mécanismes opposés existent: notre cerveau va supprimer certains détails pour créer une forme ou un pattern reconnaissable ou au contraire ajouter des détails pour créer une forme ou un pattern reconnaissable.
5. **Continuité**: notre cerveau a tendance à faire se poursuivre les formes au delà de leurs limites. Par exemple, nous percevons une croix comme une intersection de deux droites plutôt que comme 4 droites convergentes.
6. **Symétrie et ordre**: si une composition n'est pas ordonnée et symétrique, le risque est que le sujet consacre du temps à comprendre ce qui pose problème et à le contrebalancer plutôt que de consacrer son attention au message véhiculé.

### Dieter Rams

Dieter Rams est sans doute l'un des plus grands designers industriels encore en vie. Il a travaillé pour Braun et pour Vitsoe. Il a énoncé [10 grands principes](https://www.vitsoe.com/gb/about/good-design) qui peuvent largement êtres appliqués au design d'interfaces et de produits digitaux.

1. **Good design is innovative**: le web est un milieu qui évolue sans cesse. Un designer web doit se maintenir à jour, se familiariser avec les nouvelles techniques et technologies et les incorporer dans son travail. Le concept de "progressive enhancement" correspond assez bien à ce premier principe: il nous permet de nous assurer que les navigateurs plus anciens puissent interpréter notre code tout en faisant droit aux capacités des browsers plus avancés.
2. **Good design makes a product useful**: le but d'un site Internet ou d'une application n'est jamais d'être esthétiquement plaisant. Les projets digitaux se situent toujours à communiquer des informations à un utilisateur (sites de contenus) ou à lui faire accomplir des tâches (applicatifs). Vos design doivent toujours soutenir les objectifs de l’émetteur et les besoins des utilisateurs.
3. **Good design is aesthetic**: le design a également une valeur intrinsèque. Nous avons également tendance à pardonner d'avantage à des applications ou sites que nous jugeons esthétiquement plaisants.
4. **Good design makes a product understandable**: vos sites et vos applications ne devraient idéalement pas avoir besoin d'explications ou de mode d'emplois. Vos designs peuvent aider à créer une expérience utilisateur qui se suffit à elle-même.
5. **Good design is unobtrusive**: veillez à ce que vos designs n’introduisent pas de gros problème d'accessibilité et ne rendent pas vos sites ou applications moins facilement utilisables. Scroll highjacking, parallaxes intempestives, dépendance au javascript pour des sites de contenus ou des fonctionnalités de base, etc.
6. **Good design is honest**: vos designs peuvent contribuer à faire en sorte que vos utilisateurs soit tout de suite au fait des fonctionnalités et contenus qu'ils vont y trouver. Le packaging trompeur et la publicité mensongère sont tout aussi problématiques dans le digital que dans la réalité.
7. **Good design is long-lasting**: la durée de vie d'un site Internet ou d'une application est en moyenne de 3 ou 4 ans. Concevoir vos designs comme étant au service des contenus, des fonctionnalités et des utilisateurs, sans forcément suivre la mode ou viser un [awwward](http://www.awwwards.com/) leur permet de rester pertinents sur la durée.
8. **Good design is thorough, down to the last detail**: Etre attentifs au moindre détail dans vos designs est une preuve de respect pour vos utilisateurs ainsi que pour vos clients.
9. **Good design is environmentally-friendly**: votre environnement est le web, avec ses trois principes: standards libres de droits, universalité d'accès et moyens de publication ouverts. Utilisez les standards ouverts plutôt que des languages propriétaires. Respecter l'universalité d'accès c'est également réaliser des sites et applications les plus optimisés possible afin de réduire les ressources qu'ils consomment tant au niveau des serveurs que des machines des utilisateurs.
10. **Good design is as little design as possible**: focalisez-vous sur l'essentiel, éliminez le superflu. Commencez toujours vos designs en pensant aux environnements dans lesquels les contraintes sont les plus importantes: mobile first et connection 3G ou Edge.

### Conseils pratiques

A ce sujet, je vous propose de lire et d'appliquer les 7 conseils détaillés dans les deux articles publiés sur Medium par Erik D. Kennedy: 7 Rules for Creating Gorgeous UI ([part1](https://medium.com/@erikdkennedy/7-rules-for-creating-gorgeous-ui-part-1-559d4e805cda#.ka06muuxz) et [part2](https://medium.com/@erikdkennedy/7-rules-for-creating-gorgeous-ui-part-2-430de537ba96))

1. **La lumière vient d'en haut**: avoir une source de lumière cohérente pour l'ensemble des éléments sur l'ensemble de vos écrans amène une grande cohérence. Le plus facile est de placer la source lumineuse au dessus de l'écran. Il est parfois utile de dessiner vos interfaces de profil pour comprendre ce qui se passe au niveau de la lumière.
2. **Penser en niveaux de gris d'abord**: commencer par dessiner ses interfaces en niveaux de gris permet de tester vos écrans en évitant que vos utilisateur ne soient distraits par graphisme, couleurs et visuels.
3. **Doubler votre whitespace**: nous avons tous tendance à essayer de placer autant de contenus que possible dans chacun de nos écrans et dans nos interfaces. Augmenter l'espace vide et négatif permet d'aérer nos interfaces et de les rendre plus compréhensibles.
4. **Techniques pour superposer textes et images**: superposer du texte et des images est une opération délicate mais qui doit souvent être réalisée. Il existe quelques bonnes pratiques à respecter.
5. **Textes - pop et unpop**: Permettre à certains éléments textuels de ressortir par rapport au reste ou permettre à certains autres de se fondre dans le décor permet de créer une hiérarchie directement perceptibles par vos utilisateurs.
6. **Utiliser des fontes de qualité**: le web c'est à 80% de la typographie. Utiliser des fontes de qualité, c'est vous assurer que vous disposez d'une fondation solide pour gérer cet aspect important de vos designs et interfaces.
7. **Etudier le travail des autres**: lorsque vous croisez la route d'un design que vous trouver efficace et esthétique ou une interface particulièrement réussie, étudiez là. Prenez un screenshot et décortiquez les choses, penchez-vous sur les détails, sur ce qui fait que cela fonctionne. Cela vous donnera des bases pour votre propre travail.

## Elements importants: grilles et typographie

Vos utilisateurs tentent toujours d'ordonner et de structurer ce qu'ils perçoivent. Il importe donc de leur donner cette structure dans vos designs.

Les deux grands éléments permettant de structurer vos contenus et vos interfaces sont les grilles et la typographie, qui vont créer de la structure à travers la mise en place d'un certain rythme, tant sur le plan horizontal que vertical.

### Grilles (macro)

Au niveau macro, vos layouts vont en général obéir à une ou plusieurs grilles qui vont vous permettre de structurer votre contenu horizontalement. Deux types de grilles sont en général utilisés:

- **grilles symétriques**: basées sur des colonnes de tailles égales
- **grilles proportionnelles**: basées sur des proportions telles que le nombre d'or

#### Rythme horizontal: grilles symétriques et proportionnelles

##### Grilles symétriques

Les grilles les plus simples à utiliser et à créer sont des grilles symétriques possédant des colonnes de même tailles. Il est possible de créer des changements de rythmes en combinant deux de ces grilles avec une taille de gutter commune. Avec l'avènement du responsive design, le nombre de colonnes de ces grilles change en fonction de la taille d'écran considérée.

Une exemple classique est celui d'une grille de 6 colonnes combinée avec une grille de 5 colonnes (écrans de taille moyennes), ou une grille de 12 colonnes combinée avec une grille de 10 colonnes (écrans de grande taille).

##### Grilles symétriques

Les autres grilles utilisées sont des grilles proportionnelles, basées soit sur des proportions existant dans la nature (nombre d'or), soit sur des proportions considérées comme harmonieuses:

#### Rythme vertical

De la même manière, il est important de créer un rythme vertical. Certains tentent de recréer une baseline grid similaire à celles utilisée dans l'industrie du print. Personnellement, je pense qu'essayer de créer une baseline grid stricte sur le web est utopique et ne rencontre pas les particularités du media (images, videos, etc.). Il vaut mieux viser un rythme vertical en gérant vos espacements verticaux le plus justement possible.

Pour ce faire, on utilise en général un multiple de votre taille de police de base. Part exemple, si votre taille de police est de 16px vos espaces verticaux seront tous des multiples de 8: séparez vos sections avec des paddings de 160px, séparez vos titres de vos paragraphes avec des espaces de 32 pixels, etc. Beaucoup préconisent de créer un lien entre la taille des colonnes de votre grille horizontale, votre taille de police de base et votre rythme vertical.

### Typographie (micro)

Le web étant composé à 90% de textes, la typographie reste un élément important. Avec les web fonts, nous avons aujourd'hui à notre disposition une large palette de fontes et de polices. Face à un tel choix, la question est: quelle fontes choisir, comment choisir de bonnes combinaisons et comment  créer une échelle typographique faisant sens pour votre design.

#### Choix de fontes

Quelques sites vont vous permettre de naviguer dans d'importants catalogues de fontes gratuites ou payantes: [Google fonts](https://fonts.google.com/), [Adobe Typekit](http://typekit.com/), [Fontdeck](http://fontdeck.com/), [Font Squirrel](https://www.fontsquirrel.com/), [Cloud.Typography](http://www.typography.com/cloud/welcome/), etc.

Lorsque vous choisissez une police en fonction des objectifs de votre site et de ses utilisateurs, il est intéressant d’en examiner l’histoire et de voir pour quel(s) usage(s) cette fonte a été crée, dans quel contexte. Visitez les sites des studios de typographie ou [Typedia](http://typedia.com/) pour en avoir une bonne idée.

#### Combinaisons de fontes

Combiner différentes fontes au sein d’un même design est toujours un exercice complexe.

La première chose à faire est de voir si il est possible de vous en sortir avec une seule. Pour ce faire, il est préférable qu’elle offre de multiples graisses et variantes et qu’elle se comporte convenablement à grandes et petites tailles.

Si vous combinez plusieurs fontes, les superfamilies (la même famille de fontes avec des caractéristiques différentes) sont une option intéressante: Freight Text et Freight Sans par exemple. Jetez également un coup d’oeil aux fontes réalisées par un même designer ou une même fondrie: elles ont sans doute des “liens de parenté”.

Des sites tels que Google Fonts et Typekit vous proposent des tris par caractéristique, des exemples de pairing et des spécimens détaillés pour juger sur pièce.

- N’hésitez pas non plus à vous inspirer des combinaisons réalisées par d’autres: des sites tels que [Typewolf](https://www.typewolf.com/), [Fonts in Use](http://fontsinuse.com/) ou [le blog de Typekit](http://blog.typekit.com/category/using-type/) en répertorient un grand nombre.

#### Echelles typographiques

Pour ce qui est des tailles respectives de vos polices au sein d’un même design, des outils tels que [Modular Scale](http://www.modularscale.com/) par [Tim Brown](http://nicewebtype.com/) vous permettent de créer des échelles typographiques intéressantes. 

## Exemples de design systems

Les [style guides](http://styleguides.io/) réalisés par quelques grandes compagnies ou institutions sont une bonne source d’inspiration et vous donnent également une bone idée de ce qu’il vous faudra prévoir comme composants et patterns. Ils vous permettent également de vous pencher sur leur implementation technique.

- [US Government web design standards](https://standards.usa.gov/) by 18F
- [Lightning](https://www.lightningdesignsystem.com/) by Salesforce
- [Mapbox](https://www.mapbox.com/base/) style guide by Mapbox
- [Material Design](http://material.io/) by Google
- [Rizzo](http://rizzo.lonelyplanet.com/) by Lonely Planet

## Méthodologies

Une méthodologie très utilisée dans le design d’interfaces ou dans les projets digitaux en général au niveau de l’expérience utilisateur est celle du Design Sprint, popularisée par [Thoughtbot](https://thoughtbot.com/product-design-sprint) et [Google Ventures](http://www.gv.com/sprint/).

En seulement une semaine, un Design Sprint bien conduit permet de créer et de tester un prototype en situation réelle avec des utilisateurs. Cette méthode de travail permet de vérifier ses assomptions et d’éviter d’engager ressources et fonds sans avoir de feedback de ses utilisateurs.

1. **Lundi**: définition du challenge pour le sprint et des questions à résoudre, interviews d’experts, personas et user journeys.
2. **Mardi**: exploration des solutions possibles, review de solutions existantes dans et hors du secteur, creation de solutions propres, pitch et vote.
3. **Mercredi**: Choix d’une solution à prototyper, scénario et storyboard complet, choix d’un degré de fidélité et des moyens à mettre en oeuvre pour avoir un prototype crédible.
4. **Jeudi**: création du prototype et répétition des tests utilisateurs en fin de journée.
5. **Vendredi**: tests utilisateurs et feedback.

## Ressources

- [Design Principles: Visual Perception And The Principles Of Gestalt](https://www.smashingmagazine.com/2014/03/design-principles-visual-perception-and-the-principles-of-gestalt/) - Smashing Magazine
- [The designer's guide to Gestalt Theory](http://www.creativebloq.com/graphic-design/gestalt-theory-10134960) - Creative Bloq
- [Gestalt Principles: How Are Your Designs Perceived?](http://vanseodesign.com/web-design/gestalt-principles-of-perception/) - Vanseo Design
- [Dieter Rams: ten principles for good design](https://www.vitsoe.com/gb/about/good-design) - Vitsoe
- [Startups, this is how design works](https://startupsthisishowdesignworks.com/) - Wells Riley
- [Design techniques](https://guides.area17.com/) - Area17
- [Website Style Guides ressources](http://styleguides.io/) - Anna Debenham and the community
- [From print, to digital, and beyond …](https://www.youtube.com/watch?v=42RXq0fgP24) (video) - Mark Porter
- [Objectified](https://www.youtube.com/watch?v=e52fYCYiPok) (film) - Gary Hustwit
- [Exercices, ressources et déroulement d’un Design Sprint](https://github.com/thoughtbot/design-sprint) - Thoughtbot
- [Atomic Design](http://atomicdesign.bradfrost.com/chapter-1/) (particulièrement pour le premier chapitre) - Brad Frost
