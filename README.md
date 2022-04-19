# Ressources pour les développeuses et les développeurs, et autres intéressé·es

Une liste d'outils et de ressources culturelles (ebooks, podcasts, vidéos, conférences...) **gratuites** pour les développeur·euse·s, *sélectionés avec nez et amour*, plutôt orientés web (en tout cas initialement). Cette liste ne se veut pas exhaustive *par choix* et contient **évidemment** des opinions sur certains sujets.

La liste est francophone, cependant bon nombre de ressources listées ici ne sont malheureusement que disponibles en anglais.

Choisissez parmi ces outils ceux que vous préférez et intégrez les à votre *workflow* pour vous aider à produire plus efficacement du code ou du design de qualité. 

## Contribuez

Un lien mort ? Une typo ? Votre ressource préférée n'est pas présente ici et vous voulez la partager ? 

Proposez votre contribution via l'ouverture d'une issue ou d'une [Pull Request](http://thelia-school.com/faire-une-pull-request-sur-un-projet-thelia/faire-une-pull-request.html).

## Partagez

N'hésitez pas à *star* ce dépôt (suivre, en haut à droite), à le partager : )

*No time to lose !*

<img src="img/./no%20time%20to%20lose.jpeg" alt="No time to lose ! (Monty Python Flying Circus)" width="600"/>

## Table des matières

- [Ressources pour les développeuses et les développeurs, et autres intéressé·es](#ressources-pour-les-développeuses-et-les-développeurs-et-autres-intéressées)
  - [Contribuez](#contribuez)
  - [Partagez](#partagez)
  - [Table des matières](#table-des-matières)
  - [Frontend](#frontend)
    - [Typographies/Fonts](#typographiesfonts)
    - [Palettes de couleurs](#palettes-de-couleurs)
    - [Pack d'icones](#pack-dicones)
    - [Images: photos, illustrations, svg](#images-photos-illustrations-svg)
    - [Générateurs CSS](#générateurs-css)
    - [Générateur de formes au format SVG](#générateur-de-formes-au-format-svg)
    - [Animations CSS (keyframes API)](#animations-css-keyframes-api)
    - [Frameworks CSS](#frameworks-css)
    - [Gradients](#gradients)
    - [Générateur de mise en page / layouts](#générateur-de-mise-en-page--layouts)
    - [JS](#js)
    - [Backgrounds](#backgrounds)
    - [Pixel art](#pixel-art)
    - [Design aggregators](#design-aggregators)
    - [Composants](#composants)
    - [UI/UX](#uiux)
    - [DOM](#dom)
    - [Documentation et articles de référence](#documentation-et-articles-de-référence)
    - [Check, check, check](#check-check-check)
      - [Code](#code)
      - [Est-ce-que j'oublie un truc ?](#est-ce-que-joublie-un-truc-)
      - [Contraste](#contraste)
  - [Comme évaluer la santé d'un dépôt/bibliothèque avant d'y lier son projet pour le meilleur et pour le pire ?](#comme-évaluer-la-santé-dun-dépôtbibliothèque-avant-dy-lier-son-projet-pour-le-meilleur-et-pour-le-pire-)
  - [Comment apprendre à apprendre le développement ?](#comment-apprendre-à-apprendre-le-développement-)
    - [Quand on débute](#quand-on-débute)
    - [Quand on débute moins](#quand-on-débute-moins)
  - [SEO](#seo)
  - [Page builders](#page-builders)
  - [Analytics](#analytics)
  - [Browser extensions](#browser-extensions)
  - [API](#api)
  - [Fake data generators](#fake-data-generators)
  - [Wordpress](#wordpress)
    - [Un mot sur Wordpress](#un-mot-sur-wordpress)
    - [Doc officielle wordpress.org](#doc-officielle-wordpressorg)
    - [Articles](#articles)
    - [Livres de développement wordpress](#livres-de-développement-wordpress)
    - [Épisodes de podcasts sur wordpress](#épisodes-de-podcasts-sur-wordpress)
    - [Podcasts dédiés à Wordpress](#podcasts-dédiés-à-wordpress)
    - [Formations](#formations)
    - [Starter themes](#starter-themes)
    - [Plugins recommandés](#plugins-recommandés)
  - [Générateur de mots de passe](#générateur-de-mots-de-passe)
  - [Standards](#standards)
  - [XML](#xml)
    - [Un mot sur le XML](#un-mot-sur-le-xml)
    - [Apprendre le XML et ses standards associés](#apprendre-le-xml-et-ses-standards-associés)
  - [Protocoles](#protocoles)
    - [SSH](#ssh)
  - [Spécifiques à un langage/écosystème](#spécifiques-à-un-langageécosystème)
    - [PHP](#php)
    - [JavaScript](#javascript)
  - [Suivi de projets](#suivi-de-projets)
  - [Bases de données](#bases-de-données)
  - [Perl](#perl)
  - [Programmation fonctionnelle](#programmation-fonctionnelle)
    - [Général](#général)
    - [Haskell](#haskell)
    - [Clojure](#clojure)
    - [Elm](#elm)
    - [Racket, le *langage-oriented programming language*](#racket-le-langage-oriented-programming-language)
  - [Conception de bases de données](#conception-de-bases-de-données)
  - [Rich Hickey](#rich-hickey)
  - [Environement de développement](#environement-de-développement)
  - [Challenges](#challenges)
  - [Markdown](#markdown)
  - [Présentations / Slides](#présentations--slides)
  - [Éditeurs de texte](#éditeurs-de-texte)
  - [Boîte à outils](#boîte-à-outils)
    - [Sed](#sed)
  - [Convertisseurs de documents](#convertisseurs-de-documents)
  - [Automatisation de tâches sous linux](#automatisation-de-tâches-sous-linux)
  - [Langages/technos à découvrir](#langagestechnos-à-découvrir)
    - [Un mot](#un-mot)
    - [Rust](#rust)
    - [Smalltalk](#smalltalk)
    - [Assembleur](#assembleur)
    - [Prolog](#prolog)
    - [Scheme (List dialect)](#scheme-list-dialect)
    - [Arduino](#arduino)
  - [Ebooks](#ebooks)
    - [Classiques](#classiques)
    - [Refactoring, travailler sur du code legacy](#refactoring-travailler-sur-du-code-legacy)
    - [Software design](#software-design)
    - [Architecture de l'information](#architecture-de-linformation)
    - [Wordpress](#wordpress-1)
    - [Sécurité des applications webs](#sécurité-des-applications-webs)
    - [Webmaster](#webmaster)
    - [HTTP](#http)
    - [Perl](#perl-1)
    - [Test driven development](#test-driven-development)
    - [Programmation CGI](#programmation-cgi)
    - [Génération procédurale et game design](#génération-procédurale-et-game-design)
    - [Freelance, conseils pour bien gérer son business depuis chez soi](#freelance-conseils-pour-bien-gérer-son-business-depuis-chez-soi)
    - [Algorithmes](#algorithmes)
  - [O'Reilly Open Books](#oreilly-open-books)
  - [Billets](#billets)
  - [Papiers](#papiers)
  - [Podcasts](#podcasts)
  - [Youtube](#youtube)
    - [Conférences](#conférences)
    - [La vérité par l'humour](#la-vérité-par-lhumour)
    - [Génération procédurale](#génération-procédurale)
    - [Game Developers Conference (aka GDC)](#game-developers-conference-aka-gdc)
    - [Computer graphics et art génératif](#computer-graphics-et-art-génératif)
    - [Programmation fonctionnelle](#programmation-fonctionnelle-1)
      - [Haskell](#haskell-1)
      - [PHP](#php-1)
    - [Créativité, modèles mentaux](#créativité-modèles-mentaux)
    - [Chaînes](#chaînes)
    - [Playlists](#playlists)
  - [Prendre soin de soi](#prendre-soin-de-soi)
  - [Inclassables](#inclassables)
  - [Banques de ressources](#banques-de-ressources)
  - [Twitter(s)](#twitters)
  - [Trouver des livres techniques d'occasion pas cher](#trouver-des-livres-techniques-doccasion-pas-cher)


## Frontend

### Typographies/Fonts

- [typescale](https://type-scale.com/), creer facilement un système de tailles de font à suivre
- [typography principles](https://typographyprinciples.obys.agency/alignments/), un guide pour apprendre les principes de la typo
- [fontjoy](https://fontjoy.com/), trouver facilement des combinaisons de fonts qui fonctionnent
- [google-type](https://femmebot.github.io/google-type/), trouver facilement des combinaisons de fonts qui fonctionnent
- [fontsquirrel](https://www.fontsquirrel.com/), bibliothèque de fonts libres pour usage commercial
- [fontsinuse](https://fontsinuse.com/), bilbiothèque de typos
- [fontfabric](https://www.fontfabric.com/font-tester/), tester rapidement ses fonts

### Palettes de couleurs

- [open color](https://yeun.github.io/open-color/), une reference
- [coloors](https://coolors.co/), fouiller ce site il vous offre toute une palette d'outils incroyables autre que les palettes de couleurs
- [colorspace](https://mycolor.space/), generateur de palettes de couleurs stylé
- [css duotones](https://cssduotone.com/)
- [duotones](https://medialoot.com/duotones/), palettes duotones (deux couleurs)
- [palette ninja](https://palette.ninja/)
- [pattern background](http://www.patternify.com/)
- [palettes](https://flatuicolors.com/)

### Pack d'icones

- [favicon generator](https://favicon.io/)
- [icomoon](https://icomoon.io/)
- [font awesome icons](https://fontawesome.com/v4.7.0/icons/)
- [tabler-icons](https://tabler-icons.io/)
- [heroicons](https://heroicons.com/)
- [iconshock](https://www.iconshock.com/)
- [phosphor icons](https://phosphoricons.com/)

### Images: photos, illustrations, svg

- [unsplash](https://unsplash.com/)
- [pexels](https://www.pexels.com/fr-fr/)
- [drawkit](https://drawkit.com/)
- [undraw](https://undraw.co/)
- [compresseur](https://squoosh.app/)
- [noun project](https://thenounproject.com/)
- [fake images please?](https://fakeimg.pl/)
- [freepik](https://www.freepik.com/)

### Générateurs CSS

- [neumorphism](https://neumorphism.io/#e0e0e0), generer de l'UI en pure CSS
- [glassmorphism](https://hype4.academy/tools/glassmorphism-generator), effet verre
- [gloweffect](https://codersblock.com/blog/creating-glow-effects-with-css/), generer des glow effects
- [underline generator](https://underline-generator.netlify.app/)
- [ribbon generator](https://www.cssportal.com/css-ribbon-generator/), creez vos rubans

### Générateur de formes au format SVG

- [getwaves](https://getwaves.io/), faites des vagues
- [blobmakers](https://www.blobmaker.app/), creer des formes uniques et organiques en svg rapidement
- [clip path maker](https://bennettfeely.com/clippy/), creer des svg de manière interactive
- [fancy border radius](https://9elements.github.io/fancy-border-radius/full-control.html)

### Animations CSS (keyframes API)

Expérimenter et créer des animations CSS

- [Animista](https://animista.net/), experimentez les animations CSS
- [Pictogon](https://pictogon.com/), images interactives
- [keyframes animate](https://keyframes.app/animate/)
- [wait !](https://waitanimate.wstone.uk/)

### Frameworks CSS

- [emotion](https://emotion.sh/docs/introduction), lib JS pour écrire du style CSS



### Gradients

- [ui gradients](uigradients.com)

### Générateur de mise en page / layouts

- [css grid generator](https://css-generator.netlify.app/)
- [layout generator](https://grid.layoutit.com/)
- [flexbox builder](https://flexbox.webflow.com/)


### JS

- [waterpipes generator](http://dragdropsite.github.io/waterpipe.js/)
- [magic grid](https://github.com/e-oj/Magic-Grid)
- [scroll reavel](https://scrollrevealjs.org/), animer le scrolling de vos pages webs


### Backgrounds

- [pattern background](http://www.patternify.com/)
- [stripes generator](https://stripesgenerator.com/)


### Pixel art

- [pixel art to css](https://t.co/6eyHLm8PUE)


### Design aggregators

- le web !
- [land-book](https://land-book.com/)
- [onepagelove](https://onepagelove.com/)
- [awwwards](https://www.awwwards.com/)
- [screenlane](https://screenlane.com/)
- [webdesign inspiration](https://www.webdesign-inspiration.com/fr/)
- [dribble](https://dribbble.com/)
- [landingfolio](https://landingfolio.com/?offset=1), designs de landing pages
- [ui garage](https://uigarage.net/)
- [collect ui](https://collectui.com/)


### Composants

- [accordion slider generator](https://accordionslider.com/)
- [navbar generator](http://www.menucool.com/css-menu)
- [button](https://www.bestcssbuttongenerator.com/)
- [loader](https://loading.io/)
- [Froala Design Blocks](https://froala.com/design-blocks/), une banque de composants prêt à l'emploi

### UI/UX

- [checklistdesing](https://www.checklist.design/), une collection des meilleures pratiques de design web
- [laws of UX](https://lawsofux.com/), une autre collection des meilleures pratiques en design web, très bien faite, avec un résumé de ce qu'il faut retenir sur chaque post
- [design principles](https://principles.design/)
- [uiplaybook](https://uiplaybook.dev/), un dictionnaire des composants webs (fonction, bonnes pratiques, implémentation etc..)
- [UX challenges](https://uxtools.co/challenges), exercices d'UX

### DOM

- [testing playground](https://testing-playground.com/), tester vos interactions avec le DOM dans un environnement dédié

### Documentation et articles de référence

- [css grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [css selectors](https://www.w3schools.com/cssref/css_selectors.asp)
- [how to draw an svg in Inscape](https://www.youtube.com/watch?v=PSl1c6kYfHs)


### Check, check, check

#### Code

- [The W3C Markup Validation Service](https://validator.w3.org/), valider le code source de vos pages web
- [can i use...](https://caniuse.com/)

#### Est-ce-que j'oublie un truc ?

- [Landing Page Checklist](https://landingpage.fyi/landing-page-checklist.html), des ressources pour votre landing page et s'assurez de n'avoir rien oublié d'important
- [Front-end checklist](https://frontendchecklist.io/)


#### Contraste

- [color contrast checker](https://coolors.co/contrast-checker/495057-ffffff)

## Comme évaluer la santé d'un dépôt/bibliothèque avant d'y lier son projet pour le meilleur et pour le pire ?

Quelques conseils pour *se faire une idée* de la *santé* d'un dépôt ou d'une bibliothèque, à savoir est-ce-que j'en ai vraiment besoin ? Si oui, pourquoi ? Est-ce-que ce dépôt est maintenu ou abandoné ? Est-ce-qu'il y a une communauté derrière active et prête à dépanner ? Est ce que cette dépendance de mon projet va casser dans 6 mois ? 

Aller sur le dépôt puis
- regarder s'il y a une documentation. S'il n'y en a pas, fuyez !
- regarder si la documentation est à jour. Si ce n'est pas le cas, vous allez souffrir
- regarder la date du dernier commit
- regarder le nombre d'issues ouvertes et à quelles dates les dernières ont été ouvertes. Qu'il y ait un grand nombre d'issues en soit n'est pas vraiment un problème. Au contraire, cela témoigne de l'activité du dépot, de son usage et peut-être de son utilité. Ce qui compte c'est *est-ce qu'on répond à ces issues*
- regarder depuis combien de temps les contributeurs du dépot n'ont pas répondu à une issue
- regarder le nombre de stars/fav (attention, métrique pas toujours pertinente)
- regarder le nombre de contributeurs
- regarder le nombre de pull requests en attente
- trouver une coquille dans le README et faites une Pull Request pour la corriger (un espace qui manque, une ponctuation peu importe). Observer le temps de réaction des contributeurs du dépôt. Cela donne une bonne mesure de son activité. (Merci à [@frozar](https://github.com/frozar) pour cette technique) Essayez donc sur ce dépôt !
- essayer de trouver où se cache la communauté en ligne (site, wikis, IRC, Discord etc...) Dites bonjour, si on vous répond pas mieux vaut passer son chemin
- est-ce que le projet est versionné ? C'est important pour exactement de quelle version dépend notre projet, tracker les changements rétrocompatibles ou non etc..


## Comment apprendre à apprendre le développement ?

A venir...

### Quand on débute

### Quand on débute moins

## SEO

- [siteliner](https://siteliner.com/), trouver le contenu dupliqué sur votre site (et supprimez le !)


## Page builders

- [swipepages](https://swipepages.com/)

## Analytics

- [splitbee](https://splitbee.io/)
- [clearbit](https://clearbit.com/resources/tools/visitor-report)

## Browser extensions

A venir

## API

- [weatherstack](https://weatherstack.com/)
- [fakerapi](https://fakerapi.it/en/)
- [wordsapi](https://www.wordsapi.com/)
- [catfacts](https://alexwohlbruck.github.io/cat-facts/)

## Fake data generators

- [random users](https://xsgames.co/randomusers/)


## Wordpress

### Un mot sur Wordpress

Il y avait en 2021 [environ 455 000 000 sites Wordpress](https://techjury.net/blog/percentage-of-wordpress-websites/). Cela représente *au moins 30% du web*, mais plutôt *40%* (estimation haute). 

C'est toujours un phénomène curieux et intéressant de constater que sur les internets (Twitter, plateformes de blogging) on entend si peu parler des outils qui font tourner le web. Pourquoi n'entend on jamais parler de Wordpress ou de JQuery mais plutôt des 30 derniers frameworks JS à la mode alors que ces outils font littéralement tourner l'immense majorité du web ? Les modes passent. Wordpress, lui, reste.

Wordpress est un framework parfaitement adapté pour publier du contenu sur Internet. Wordpress se met très bien à l'échelle et est très polyvalent. Oui, si Wordpress peut être utilisé pour tout faire, il n'est pas toujours la solution la plus adaptée ! 

Wordpress existe depuis 2004, dans le monde du logiciel libre c'est une éternité. Pensez à vos propres dépôts, projets que vous n'arrivez pas à maintenir plus d'un an, tout seul. 

Wordpress c'est développé et pensé *pour l'utilisateur* (celui qui publie et gère le contenu), et non pour le développeur. Les utilisateurs se moquent bien de nos outils tant qu'ils ont ce qu'ils demandent. Wordpress, à l'instar de LibreOffice ou autre, est devenu un standard de gestion de contenu en ligne que beaucoup de personnes non techniciennes connaissent bien, utilisent quotidiennement. C'est donc un énorme avantage de capitaliser dessus pour vos les futurs utilisateurs de votre application web.


### Doc officielle wordpress.org

Très bien faite, mais peut parfois demander un peu d'experience pour s'y retrouver. Ne pas oublier que de documenter un immense framework qui évolue sans cesse est un immense challenge en soi.

- [Codex](https://codex.wordpress.org/)
- [Wordpress hierarchy](https://developer.wordpress.org/themes/basics/template-hierarchy/)
- [Wordpress coding standards](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/)
- [Template tags](https://codex.wordpress.org/Template_Tags)
- [Using Permalinks](https://wordpress.org/support/article/using-permalinks/)
- [Data Sanitization/Escaping](https://developer.wordpress.org/themes/theme-security/data-sanitization-escaping/#escaping-with-localization)
- [Localization](https://developer.wordpress.org/apis/handbook/internationalization/localization/)
- [Make Wordpress](https://make.wordpress.org/), un hub centralisés de ressources pour les développeurs Wordpress



### Articles

- [WordPress Taxonomies: The Ultimate Guide](https://ithemes.com/blog/wordpress-taxonomies)
- [WordPress Permalinks: The Essential Guide](https://ithemes.com/blog/wordpress-permalinks)

### Livres de développement wordpress

A télécharger sur [pdfdrive](https://www.pdfdrive.com/):

- *[Professional WordPress: Design and Development](https://www.pdfdrive.com/wrox-press-professional-wordpress-design-and-development-3rd-e30698942.html)* de Brad Williams et David Damstra, Edition Wrox, 3rd Edition, 2015
- *[Professional WordPress Plugin Development](https://www.pdfdrive.com/professional-wordpress-plugin-developmen-4074kb-jun-27-2012-120000-am-e42772568.html)* de Brad Williams et Justin Taldock, Edition Wrox, 2nd Edition, 2020
- *[Modern PHP: new features and good practices](https://www.pdfdrive.com/modern-php-e34337192.html)*, Josh Lochart, Edition O'REILLY, 2015

### Épisodes de podcasts sur wordpress

- [070: All things WordPress](https://phproundtable.com/episode/all-things-wordpress), [Tessa Kriesel](https://twitter.com/tessak22?s=20&t=L4nTJJGyh2w5UbPY7aDo9g) présente ici l'état et le futur de Wordpress ainsi que l'histoire de son développement
- [The thing about Wordpress](https://podcast.htmlallthethings.com/e/the-thing-about-wordpress/), Matt y discute des avantages et inconvénients de Wordpress en tant que développeur. Tout ce qui est discuté ici est pertinent

### Podcasts dédiés à Wordpress

- [dradcast](http://dradcast.com/)
- [wp watercooler](https://wpwatercooler.com/)

### Formations

- [Cours wordpress.org](https://learn.wordpress.org/courses)
- [Building websites with WordPress](https://nmiletic.gumroad.com/l/kSrqD) 
- [Learn Wordpress](https://kinsta.com/learn/)
- [Wordpress for beginners training](https://yoast.com/academy/free-training-wordpress-for-beginners/)
- [How to Learn WordPress for Free in a Week (or Less)](https://twitter.com/natmiletic/status/1511711827398258695)
- [Wordpress tutorials](https://www.siteground.com/tutorials/wordpress/)
- [How to](https://wordpress.tv/category/how-to/), video
- [Our wordpress library](https://wpapprentice.com/courses/)
- [Wordpress freecodecamp](https://www.freecodecamp.org/news/tag/wordpress/)
- [Building PHP MVC Framework from Scratch](https://www.youtube.com/watch?v=WKy-N0q3WRo&list=PLLQuc_7jk__Uk_QnJMPndbdKECcTEwTA1), The Codeholic. Pas sur Wordpress mais montre les fonctionnalités de base d'un framework à implémenter

### Starter themes

- [underscores](https://underscores.me/)
- [astra](https://fr.wordpress.org/themes/astra/)
- [generate press](https://generatepress.com/)
- [tail press](https://tailpress.io/)

### Plugins recommandés

Le plus recommandé est *de limiter au maximum l'usage de plugins pour vos thèmes*. Cela dit certains plugins stables et bien maintenus sont souvent de la partie pour des sites en production

- [ewww image optimizer](https://wordpress.org/plugins/ewww-image-optimizer/)
- [bulletProof Security](https://wordpress.org/plugins/bulletproof-security/), bonne alternative à WordFence
- [carbon fields](https://carbonfields.net/), alternative gratuite à ACF Pro
- [fakerpress](http://fakerpress.com/r/github), générateur de faux contenu pour tester son thème
- [RankMath](https://rankmath.com/fr/), plugin SEO, bonne alternative à [Yoast](https://yoast.com/)
- [BuddyPress](https://wordpress.org/plugins/buddypress/), plugin pour ajouter une couche réseau social à votre site
- [bbPress](https://wordpress.org/plugins/bbpress/), gestionnaire de forums/fils de discussion
- [W3 Total Cache](https://wordpress.org/plugins/w3-total-cache/), un plugin pour optimiser les performances de Wordpress, complètement agnostique de l'hébergeur. Mise en cache des pages webs etc... Au final, améliore l'experience utilisateur et le SEO de votre site. Vérifiez que votre hébergeur ne vous propose pas déjà un plugin de mise en cache maison avant de l'installer sur votre site en prod


## Générateur de mots de passe

- [xkpasswd](https://xkpasswd.net/s/), créer des mots de passes sécurisés ET faciles à retenir (si vous devez le faire)


## Standards

## XML

### Un mot sur le XML

Le standard [XML](https://www.w3.org/XML/) (*eXtensible Markup Language*) est extrêmement puissant pour construire des structures de données robustes et échangeables. Contrairement aux idées reçues il n'est pas à mettre au placard et [n' a pas vocation à être remplacé par JSON](https://codepunk.io/xml-vs-json-why-json-sucks/) car les deux standards n'ont pas du tout la même histoire, ni les mêmes ambitions. *JSON est un excellent format pour... Javascript*. 

XML est un format universel pouvant être lu facilement par des humains et par des machines. Il dispose d'une structure de données en arbre et surtout, se trouve accompagné d'autres standards comme par exemple

- [XPath](http://www.xmlfacile.com/guide_xml/xpath_1.php5), un standard qui permet de requêter la structure XML pour naviguer dans la structure de données et la manipuler
- [XQuery](https://www.w3schools.com/xml/xml_xquery.asp), un standard qui permet de reqûeter l'abre via un *langage déclaratif* (le pied) comme le SQL
- [XSLT](https://www.w3schools.com/xml/xml_xslt.asp), standard plus avancé que le CSS pour styliser les données XML et les présenter. Permet également de modifier l'affichage d'éléments, de les réorganiser etc...
- [DTD](https://www.w3schools.com/xml/xml_dtd.asp), pour la validation des données par un schéma
- et d'autres encore...

Tous ces standards font d'XML un outil à avoir dans sa poche lorsque l'on a besoin d'échanger ou de construire des structures de données complexes et *validables*.

### Apprendre le XML et ses standards associés

- [XML Tutorial, W3C Schools](https://www.w3schools.com/xml/)
- [XML Facile !](http://www.xmlfacile.com/)
- [XML in a nutshell, A Desktop Quick Reference](https://www.pdfdrive.com/xml-in-a-nutshell-e54427253.html)


## Protocoles

### SSH

- [Secure Secure Shell](https://stribika.github.io/2015/01/04/secure-secure-shell.html)
- [The Ultimate Guide to SSH - Setting Up SSH Keys](https://www.freecodecamp.org/news/the-ultimate-guide-to-ssh-setting-up-ssh-keys/)

## Spécifiques à un langage/écosystème

### PHP

- [Awesome PHP](https://github.com/ziadoz/awesome-php), une liste organisée de ressources pour PHP (lib, books, podcasts, frameworks...)
- [PHP: The Right Way](https://phptherightway.com/) référence accessible aux standards modernes de PHP
- [packagist](https://packagist.org/), dépôt principal de Composer pour trouver des paquets gratuits

### JavaScript

- [p5js](https://p5js.org/), une librairie JavaScript open-source pour le code créatif. Avec un focus pour rendre le code accessible et inclusif pour les artistes, designers, formateurs, débutants. 
- [leaflet](https://leafletjs.com/SlavaUkraini/index.html), **le** projet open-source pour développer des cartes interactives et *mobile-friendly*.

## Suivi de projets

- [clickup](https://clickup.com/), alternative gratuite à Figma, plus facile à prendre en main et bourrée de toutes les fonctionnalités nécessaires 

## Bases de données

- [PostegreSQL](https://www.postgresql.org/), le choix à faire lorsqu'on part sur une base de données relationnelle. Projet open-source maintenu depuis 30ans, le SGBD qui va le plus loin sur l'implémentation du standard SQL
- [ClickHouse](https://clickhouse.com/), base de données relationnelle orientée colonnes. Optimisé pour l'[OLAP](https://www.oracle.com/fr/database/olap-definition.html). Vérifiez bien avant de vous en servir pour votre projet que [ce système soit adapté à votre cas d'utilisation](https://clickhouse.com/docs/en/#key-properties-of-olap-scenario)
- [Datomic](https://www.datomic.com/), un SGBD développé par [Rich Hickey](#rich-hickey). En plus de concevoir la base de données comme *une valeur* ce modèle incorpore le temps de manière native.


## Perl

A venir...

## Programmation fonctionnelle

### Général

- [ericnormand](https://ericnormand.me/), Eric Normand est une référence en programmation fonctionnelle, en tant que développeur mais aussi professeur. Il a écrit des livres de qualité sur le sujet.
- [Mostly adequate guide to functional programming](https://drboolean.gitbooks.io/mostly-adequate-guide-old/content/)

### Haskell

- [Le Guide (fr)](https://github.com/bitemyapp/learnhaskell/blob/master/guide-fr.md)
- [Haskell basics](https://www.seas.upenn.edu/~cis194/spring13/lectures/01-intro.html)

Voir ce [bouquin de référence](#haskell-1).

### Clojure

- [Clojure for the Brave and True ](https://www.braveclojure.com/foreword/), un livre complet, hyper pédagogique, accessible en ligne pour s'initier à la programmation fonctionnelle avec Clojure.
- [clojuredocs](https://clojuredocs.org/), un dépôt regroupant documentation et exemples pour Clojure
- [How to earn your Clojure white belt](https://www.notamonadtutorial.com/how-to-earn-your-clojure-white-belt/)

### Elm

[Elm](https://elm-lang.org/) est un langage/ecosystème fonctionnel pour développer des applications web. Il compile vers Javascript. Elm possède peut être le compilateur le plus *human-friendly* au monde

### Racket, le *langage-oriented programming language*

- [Racket, the Programming Language](https://racket-lang.org/), un *language orienté language*

## Conception de bases de données

- [Initiation à la conception de bases de données relationnelles avec MERISE](https://ineumann.developpez.com/tutoriels/merise/initiation-merise/)


## Rich Hickey

Et oui, [Rich Hickey](https://en.wikipedia.org/wiki/Rich_Hickey) a le droit à sa propre section. Allez directement voir [ce dépôt](https://github.com/tallesl/Rich-Hickey-fanclub), le job est déjà fait avec talent pour recenser tous ses travaux.


## Environement de développement

- [Environement de développement docker+reverse proxy pour un workflow multiprojets aux petits oignons + starter pack canonical](https://github.com/websealevel/starterpack-front-php8-postgresql-adminer)
- [replit](https://replit.com/), un IDE collaboratif dans le navigateur pour travailler sur des projets à plusieurs dans plus de 50 langagues sans passer une seconde à configurer son environnement de dev

## Challenges

Apprenez à coder des trucs via des challenges

- [Root Me](https://www.root-me.org/?lang=fr), testez vos compétences en hacking
- [codewars](https://www.codewars.com/), affutez votre lame en réalisant/publiant des katas
- [codinGame](https://www.codingame.com/start), on ne présente plus cette plateforme 


## Markdown

<img src="img/markdown%20everywhere.jpg" alt="Markdown, Markdown everywhere !" width="600"/>

Le [Markdown](https://daringfireball.net/projects/markdown/) est tout simplement le meilleur outil pour créer de la documentation sur tout ce que vous faites sur votre machine. C'est un convertisseur *texte vers HTML* designé pour écrire sur le web. 

Facile à apprendre, facile à exporter vers tout un tas de formats (HTML, PDF, Latex...).

*Le Markdown est à l'édition web ce que [Latex](https://www.latex-project.org/) est à l'édition papier*. Le web et le papier sont deux media différents, avec des contraintes différentes. Les chercheurs le savent bien et sont souvent embêtés car ils utilisent Latex pour leurs articles mais ils doivent aussi communiquer sur le web.

C'est l'arme ultime pour écrire, prendre des notes, partager et surtout créer une base de connaissances, que ce soit en local ou sur Internet car les *[hyperliens](https://fr.wikipedia.org/wiki/Hypertexte)* tout simplement. Markdown refait apprécier le goût du *web 1.0* : les liens hypertextes et un processus de publication simple et facile. 

Si vous voulez que je m'étale encore davantage sur les qualités du Markdown et trouver des références sur le sujet, [jetez un coup d'oeil à ce dépot](https://github.com/websealevel/doc-markdown).

Écrire en Markdown c'est comme jouer à Tetris, ça fait du bien.


## Présentations / Slides

Utilisez le pouvoir du *Markdown*, *revealjs* et *reveal-md* pour faire vos présentations.

- [revealjs](https://revealjs.com/), creer des présentations pour le web mais pas que. Et surtout générer des présentations directement à partir de vos notes en Markdown
- [Use reveal-md to generate multiple slides and host them on GitHub Page](https://blog.hanklu.tw/post/2021/use-reveal-md-to-generate-multiple-slides-and-host-them-on-github-page/), cet étudiant vous propose un workflow de folie pour générer des présentations à la volée à partir de vos notes et les héberger automatiquement sur un dépôt pour qu'elles soient toujours en ligne avec vous
- [un workflow complet à suivre pas à pas](https://github.com/websealevel/presentations), un dépôt qui reprend l'article précédent.
- [slides](https://slides.com/), si vous êtes plutôt éditeur graphique/GUI slides vous permet de créer vos présentations à la main grâce à un éditeur de qualité, et vous les heberge en ligne.


## Éditeurs de texte

- [learn Vim for the last time: A tutorial and Primer](https://danielmiessler.com/study/vim/)
- [ReText](https://github.com/retext-project/retext), un éditeur petit et puissant pour le Markdown et les langages Markup.

## Boîte à outils

### Sed

- [Sed, an introduction and Tutorial, Bruce Barnett](https://www.grymoire.com/Unix/Sed.html#uh-0), l'éditeur de flux par excellence. Comme l'indique l'auteur de ce site web, sed est un outil merveilleux mais sa documentation laisse à désirer. Privilégiez ce site pour vous y initier

## Convertisseurs de documents

- [pandoc](https://pandoc.org/index.html) : convertisseur de document universel (par exemple markdown vers pdf). Très puissant, facile à scripter et automatiser

## Automatisation de tâches sous linux

- [xdotool](https://www.semicomplete.com/projects/xdotool/), simule des inputs au clavier ou à la souris (clicks, déplacements de fenêtre, redimensionnement de fenêtre...) via le gestionnaire de fenêtres X11
- [xbindkeys](https://www.nongnu.org/xbindkeys/xbindkeys.fr.html), est un programme qui permet de lancer des commandes shell avec le clavier ou la souris sous X Window. Il associe, à l'aide d'un fichier de configuration, une commande à une touche du clavier ou à un bouton de la souris.

## Langages/technos à découvrir

### Un mot

- Est ce que *X* est mort ? 
- Apprendre *X* en 2022 ?

On a tous déjà vu ces sujets abordés partout sur internet. La vérité c'est qu'on s'en fout, *apprenez ce qui vous fait plaisir*. Même si vous ne trouverez sûrement pas de poste SmallTalk sur Linkedin aujourd'hui, apprendre SmallTalk fera de vous un meilleur programmeur. Tout est transférable, *aucun chemin d'apprentissage n'est inutile*, même si c'est sur des technos retombées aujourd'hui dans l'oubli. 

Tomber dans l'oubli ne signifie pas nécessairement devenir obselète. C'est bien souvent le contraire d'ailleurs. Par exemple, le *server side rendering* qui est tant à la mode ([tout ça pour ne pas utiliser JJQuery...](https://youtu.be/Uo3cL4nrGOk)) c'est le retour aux architectures du début du web 2.0. Souvent même, c'est juste que le *monde n'était pas encore prêt*. 

Le passé est rempli d'idées, de concepts, de technos révolutionnaires et longuement débatues collectivement par des personnes intelligentes. Profitons-en et regardons en arrière. La majorité des modes, de ce qui est nouveau dans le domaine informatique, de la hype, sont en fait des vieilles idées des années 80.

Que je sois bien compris, *je n'ai rien contre les modes et la nouveauté*. Les modes sont toujours là et aucune personne n'y échappe, aussi condenscendante soit-elle. Les frameworks JS sont des outils formidables, allez donc les apprendre (aussi). 

Ce que je veux dire c'est qu'il faut apprendre à filtrer le signal, les modes c'est du *bruit* qu'il faut souvent filtrer pour en extraire la *vraie valeur*, *les idées de fond*. Les chercheurs sont mieux armés pour cela car ils pratiquent la bibliographie de manière assidue le vendredi matin, ils connaissent les références, les idées qui sont là depuis 50 ans dans leur domaine. 

Ils se font (en général) moins avoir qu'un·e jeune de 20 ans qui débarque dans l'industrie du développement web à qui on *push* par tous les ports, via tous les canaux possibles, les derniers outils à la mode, dont la plupart seront morts dans quelques années pour laisser leur place à d'autres. Il faut avoir un biais pour ce qui est stable et éprouvé, et non pour ce qui est nouveau. Cela veut dire accueillir la nouveauté, la tester, mais toujours rester *soupçonneux*. Si demain je me lance dans un gros projet sur plusieurs années, est-ce que je prends cet outil qui est sorti le mois dernier ? (La réponse est non) .

Il vaut mieux comprendre les principes du web, qui fait quoi, dans les grandes lignes, que le dernier framework `whatever.js` à la mode. `whatever.js` va disparaître, alors qu'une architecture client-serveur non. Il faut d'abord aller voir dans le passé, on est surpris d'y constater que *la plupart des idées nouvelles ne sont pas nouvelles*.

Pour finir, ce dépôt n'échappe pas à la règle et ajoute du *bruit au bruit*. Cela représente un paradoxe assez connu de celles et ceux qui veulent apprendre le web et se retrouvent confronté·e·s à un flow de ressources complètement impossible à digérer. Ces questions sont d'ailleurs discutées dans ce podcast, consacré au sujet [Comment apprendre à devenir développeur web ?](https://www.htmlallthethings.com/podcasts/how-to-learn-web-development-skills)



### Rust

### Smalltalk

- [squeak](https://squeak.org/)

### Assembleur

### Prolog

- [swi-prolog](https://www.swi-prolog.org/)

### Scheme (List dialect)

### Arduino

## Ebooks

  Allez fouiller sur [pdfdrive](https://www.pdfdrive.com/), ce site est incroyable. Vous trouverez certainement ici le bouquin que vous cherchez.

### Classiques

- [The Pragmatic Programmer: From Journeyman to Master](https://www.pdfdrive.com/the-pragmatic-programmer-from-journeyman-to-master-e157846585.html)
- [Structure and interpretation of computer programs, 2nd edition, Harold Abelson, Gerald Jay and Julie Sussman](https://web.mit.edu/6.001/6.037/sicp.pdf), ce livre, et derrière ce cours du MIT, est juste à part. Les auteurs vont au coeur de ce que signifie *programmer* en tant qu'activité humaine. Ce cours va rajeunir avec le temps. Son objectif est de montrer ce que sont réellement les programmes et comment gérer la complexité intellectuelle des grands systèmes d'information. Et comme il est tout de suite dit dans l'intro du cours "*Computer science is a terrible name for this business... First of all, it's not a science... It's also not really very much about computers" (Harold Abelson)*
- [The C programming language](https://math.ecnu.edu.cn/~jypan/Teaching/ParaComp/books/The%20C%20Programming%20Language%202nd.pdf)
- [Designing data intensive applications](https://www.pdfdrive.com/designing-data-intensive-applications-the-big-ideas-behind-reliable-scalable-and-maintainable-systems-e167514656.html), une référence absolue

### Refactoring, travailler sur du code legacy

- [Refactoring: Improving the Design of Existing Code](https://www.pdfdrive.com/refactoring-improving-the-design-of-existing-code-e185896299.html)

### Software design

- [A philosophy of software design](https://www.pdfdrive.com/a-philosophy-of-software-design-e195285924.html)
- [Domain driven design](https://www.pdfdrive.com/domain-driven-design-e95986647.html)

### Architecture de l'information

Les livres de [Peter Morville](https://fr.wikipedia.org/wiki/Peter_Morville), un pionnier de l'architecture informationnelle. Bibliothécaire de formation, il s'est ensuite intéressé au web. Hyper intéressant

- [Information Architecture for the World Wide Web: Designing Large-Scale Web Sites](https://www.pdfdrive.com/information-architecture-for-the-world-wide-web-designing-large-scale-web-sites-e184621172.html)
- [Information Architecture: For the Web and Beyond](https://www.pdfdrive.com/information-architecture-for-the-web-and-beyond-e158738770.html)
- [Search Patterns: Design for Discovery](https://www.pdfdrive.com/search-patterns-design-for-discovery-e159084430.html)


### Wordpress

- [voir ici](#livres-de-développement-wordpress)


### Sécurité des applications webs

- [The web application hacker's handbook](https://www.pdfdrive.com/the-web-application-hackers-handbook-wordpresscom-e12194346.html)


### Webmaster

Pour apprendre les bases du web, mettre en prod, configurer un serveur, la programmation CGI

- [Webmaster in a Nutshell](https://www.pdfdrive.com/webmaster-in-a-nutshell-a-desktop-quick-reference-e106392581.html)
- [Linux en concentré](https://www.pdfdrive.com/linux-in-a-nutshell-6th-editionpdf-e18844861.html)

### HTTP

- [HTTP: The Definitive Guide](https://www.pdfdrive.com/http-the-definitive-guide-e156760262.html)

### Perl

- [Intermediate Perl, 2nd Edition: Beyond The Basics of Learning Perl](https://www.pdfdrive.com/intermediate-perl-2nd-edition-beyond-the-basics-of-learning-perl-e166970357.html)
- [Programming Perl, 4th Edition](https://www.pdfdrive.com/programming-perl-4e-e33432156.html)

### Test driven development

- [Test-Driven Development By Example, Kent Beck](https://www.pdfdrive.com/test-driven-development-by-example-e50686597.html)

### Programmation CGI

- [CGI programming with Perl](https://www.pdfdrive.com/cgi-programming-with-perl-2nd-ed-e187832058.html)

### Génération procédurale et game design

- [Procedural generation in game design](https://www.pdfdrive.com/procedural-generation-in-game-design-e184787611.html)
- [Curating Simulated Storyworlds](https://www.researchgate.net/publication/330855103_Curating_Simulated_Storyworlds), Thèse de [James Ryan](https://twitter.com/xfoml?s=20&t=fe7H8fGL0ox2vDtd6OOhnw) une référence sur les procédés de génération procédurale, l'interaction entre l'intelligence artificielle et l'experience ludique. Archéologue des travaux pionniers sur l'usage des machines pour produire des contenus culturels et artistiques

### Freelance, conseils pour bien gérer son business depuis chez soi

- [Start and Run A Business From Home: How to turn your hobby or interest into a business (Small Business Start-Ups)](https://www.pdfdrive.com/start-and-run-a-business-from-home-how-to-turn-your-hobby-or-interest-into-a-business-small-business-start-ups-d185035411.html)
- [The Small Business Owner's Manual: Everything You Need To Know To Start Up And Run Your Business](https://www.pdfdrive.com/the-small-business-owners-manual-everything-you-need-to-know-to-start-up-and-run-your-business-d184086729.html)

### Algorithmes

Soyons honnêtes, vous n'aurez jamais à coder un *binary tree* à la main dans la vraie vie, voir même en utiliser un durant votre carrière. Cette mode de connaître ces algorithmes par coeur, cette maladie, on la doit aux recruteurs qui pensent bêtement que ces méthodes de recrutement *c'est normal*. Vous pouvez avoir 5 ans d'expérience, maintenir du code legacy, refactorer, modeliser de la logique métier, écrire de la documentation de qualité, si vous savez pas inverser une chaine de caractères sur place de tête vous n'êtes pas compétent. C'est d'ailleurs un très bon premier avertissement que vous ne devriez peut être pas travailler là et passer votre chemin. 

Cela dit, si on oublie cette tendance déletère, les algorithmes c'est hyper intéressant. C'est même passionant et ça peut vous permettre d'ouvrir de nouveaux horizons pour créer des systèmes intéressants. La différence c'est que vous pouvez vous y intéressez, les comprendre sans les apprendre par coeur. Tout le monde travaille avec un onglet ouvert(mille) ou un bouquin sur la table.

- [Grokking Algorithms: An Illustrated Guide for Programmers and Other Curious People, Eric Normand](https://www.pdfdrive.com/grokking-algorithms-an-illustrated-guide-for-programmers-and-other-curious-people-e158082191.html)

## O'Reilly Open Books

L'excellent éditeur [O'Reilly](https://fr.wikipedia.org/wiki/O%27Reilly_Media), éditeur spécialisé en informatique depuis 1978, met en ligne gratuitement beaucoup d'anciennes éditions qui ne sont plus publiées via son projet de bilbliothèque ouverte. Vous pouvez retrouvez tous ces livres [ici](https://www.oreilly.com/openbook/), téléchargeables en PDF et/ou consultables en ligne.


## Billets

- [Developer Task Automation – It’s Easier Than You Think ](https://spin.atomicobject.com/2020/03/18/dev-task-automation/),*starterpack* pour mettre en place les bases de votre workflow d'automatisation en shell
- [Semantic Versioning 2.0.0](https://semver.org/), standard de versionnement expliqué et détaillé pour la gestion des dépendances dans les systèmes
- [How to Use Google – Search Tips for Better Results](https://www.freecodecamp.org/news/use-google-search-tips/), améliorer sa capacité de *pull*
- [Dependency Inversion Principle](https://wiki.c2.com/?DependencyInversionPrinciple=)
- [Reducing Coupling, Martin Fowler](https://martinfowler.com/ieeeSoftware/coupling.pdf)
- [The Principles of Functional Programming](https://www.freecodecamp.org/news/the-principles-of-functional-programming/amp/)

## Papiers

- [Out of the Tar Pit, Moseley & Marks](http://curtclifton.net/papers/MoseleyMarks06a.pdf), papier fondateur sur l'émergence et la gestion de la complexité dans la construction de systèmes d'information
- [How Do People Organize Their Desks? Implications for the Design of Office Information Systems, Malone](https://www.researchgate.net/publication/220515815_Malone_T_How_Do_People_Organize_Their_Desks_Implications_for_the_Design_of_Office_Information_Systems_ACM_Transactions_on_Office_Information_Systems_11_99-112), analyse du rôle de la spatialisation/localisation spatiale dans le processus de recherche et de l'accès à la mémoire


## Podcasts

- [podcasts sur wordpress](#podcasts-sur-wordpress)
- [syntax](https://syntax.fm/)
- [html all the things](https://www.htmlallthethings.com/), web development, web design and small business
- [phproundtable](https://phproundtable.com/)

## Youtube

### Conférences

- [The language of the system, Rich Hickey](https://youtu.be/ROor6_NGIWU)
- [Database as a value, Rich Hickey](https://youtu.be/EKdV1IgAaFc)
- [The value of values, Rich Hickey [vostfr]](https://youtu.be/VJi1vOwu2SM)
- [Are we there yet ?, Rich Hickey](https://youtu.be/ScEPu1cs4l0)
- [Hammock Driven Development, Rich Hickey](https://youtu.be/f84n5oFoZBc)
- [Same-origin policy: The core of web security, OWASP Wellington](https://youtu.be/zul8TtVS-64), la SOP merveilleusement bien expliquée
- [Tech Talk: Linus Torvalds on git](https://youtu.be/4XpnKHJAok8), je passerai pas un weekend avec Linus Torvald (le type est insupportable) mais faut avouer qu'il est vraiment intéressant
- [Noise based RNG](https://youtu.be/LWFzPP8ZbdU)
- [I used Elm in production and it cost me my job, Annaia Berry](https://youtu.be/RFrKffrKCeU)
- [Assignment, State, and Side-effects](https://youtu.be/dO1aqPBJCPg)
- [The Art of Code, Dylan Beattie](https://youtu.be/6avJHaC3C2U)


### La vérité par l'humour

- [*The Hustle*, Krazam](https://youtu.be/_o7qjN3KF8U)
- [*Microservices*, Krazam](https://www.youtube.com/watch?v=y8OnoxKotPQ)
- [*Interview with Senior JS Developer in 2022*,  Programmers are also human
](https://youtu.be/Uo3cL4nrGOk)
- [Wat, Gary Bernhardt](https://www.destroyallsoftware.com/talks/wat), exploration des arcanes de l'implémentation de différents langages

### Génération procédurale

- [Procedural Generation: Programming The Universe](https://youtu.be/ZZY9YE7rZJw)
- [Designing a Procedurally Generated Game - Dwarf Fortress, Darkest Dungeon, etc](https://youtu.be/S9pc8li4fuQ)
- [End-to-End Procedural Generation in Caves of Qud](https://youtu.be/jV-DZqdKlnE)
- [Dwarf fotress](http://bay12games.com/dwarves/), un projet fou [de générateur de monde de fantasy interactif](http://bay12games.com/dwarves/features.html), qui dure depuis plus de 20ans, fabriqué avec passion par deux frangins. Pour l'anectode, [dwarf fortress est rentré au MoMa](https://www.moma.org/collection/works/164920). Le jeu sert également de base pour [écrire des histoires](http://bay12games.com/dwarves/dev_story.html).

### [Game Developers Conference](https://gdconf.com/) (aka GDC)

La conférence annuelle de la communauté du développement du jeux vidéos. [Des tonnes et des tonnes de conférences](https://www.youtube.com/c/Gdconf) gratuites, de qualité (également dans la captation) à regarder.

- [Magic: the Gathering: Twenty Years, Twenty Lessons Learned](https://youtu.be/QHHg99hwQGY)
- [Diablo: A Classic Game Postmortem](https://youtu.be/VscdPA6sUkc)

### Computer graphics et art génératif

- [Building Collision Simulations: An Introduction to Computer Graphics](https://youtu.be/eED4bSkYCB8)
- [generativeartistry](https://generativeartistry.com/), un superbe site regroupant une multitude de tutoriels sur de l'art génératif

### Programmation fonctionnelle

#### Haskell

- [Haskell, The Craft of Functional Programming](https://www.pdfdrive.com/haskell-the-craft-of-functional-programming-e158848677.html)

#### PHP

- [Functional Programming in PHP](https://youtu.be/LZh4_q04aKo)

### Créativité, modèles mentaux

- [John Cleese on Creativity In Management](https://youtu.be/Pb5oIIPO62g), le célèbre membre des Monty Python donne son point de vue sur le processus créatif en se basant sur ses expériences d'écriture avec les Monty Python

### Chaînes

- [Krazam](https://www.youtube.com/channel/UCgBVkKoOAr3ajSdFFLp13_A), un humour tech de niche unique au monde
- [ici Amy Plant](https://www.youtube.com/channel/UC9wzC5mFFcIdguoyveTo6Ng), cherchez pas cette meuf produit du contenu unique
- [Galileo51 Galilei](https://www.youtube.com/channel/UCXdBefIuCkeLl2IYJaZyMdQ), conférences sous-titrées en français (Physique, tech)
- [The Coding Train](https://www.youtube.com/channel/UCvjgXvBlbQiydffZU7m1_aw), l'innénarable Daniel Shiffman. Apprendre plein de trucs en codant des petits projets dans le fun

### Playlists

- [MIT Course : Structure and Interpretation of computer programs, 1986 ](https://youtube.com/playlist?list=PLE18841CABEA24090), de l'or en barre
- [JavaScript Objects and Prototypes In-depth](https://youtube.com/playlist?list=PLqq-6Pq4lTTaflXUL0v3TSm86nodn0c_u), excellente série de vidéos détaillées pour bien comprendre les specs de JS et de son système de prototypes

## Prendre soin de soi

Des conseils à la volée

- **la reconnaissance ça passe avant tout par le salaire**. Même si on aime notre boulot, un boulot c'est un boulot. Faites vous payer convenablement
- coder c'est cool mais y'a autre chose dans la vie
- quand on bloque sur un bug on s'arrête, on fait autre chose, et on revient avec la solution
- quand on est fatigués on s'arrête (au moins un moment)
- quand on voit qu'on arrive plus à rien on arrête. Si on peut pas arrêter tout de suite alors on fait des petites choses qui trainent et qui restent à faire. Au moins on avance et c'est satisfaisant
- on peut tenir un journal (en Markdown bien sûr !) où on note chaque jour tout ce qu'on a fait dans la journée (on peut limiter au taff mais on peut l'étendre à tout ce qu'on veut en fonction des besoins). On fait des listes avec des entrées courtes, pas besoin de détails. Ça sert à quoi ? A se dire "ah ouais quand même j'ai fait des trucs aujourd'hui même si j'arrête ma journée sur un bug que j'ai pas résolu et que j'ai l'impression d'être un gros looser"
- quand on bloque sur un truc et que quelqu'un vous propose d'aller *X* [au choix boire un verre, manger un truc, aller voir un film etc...] ne vous dites pas "non je ne peux pas je dois finir ça. Merde, si j'étais bon je pourrai résoudre ce problème et aller *X*. Mais comme je suis débile bin je dois rester devant mon ordi tout seul à galérer." Dites "j'arrive dans 5 minutes"
- faire un peu de sport ça fait toujours du bien. Même si on en fait pas beaucoup, au moins se créer une habitude. Par exemple "Le mercredi à 17h je vais à la piscine, c'est non négociable, même si je nage 5min". Le fait d'y aller, qu'on ai envie ou pas, déjà c'est une victoire et le début d'habitudes saines pour vivre plus longtemps
- [faire attention au burnout et identifier les symptômes le plus tôt possible](https://www.passeportsante.net/fr/Maux/Problemes/Fiche.aspx?doc=epuisement_professionnel_pm). Vous n'avez pas envie de vivre ça (votre conjoint·e/chat·te/chien·ne non plus). Un [témoignage d'un dev](https://www.jesuisundev.com/burnout/)

## Inclassables

- [readme](https://readme.so/fr), créer un readme de manière simple
- [Red Blob Games](https://www.redblobgames.com/), le site d'Amit Patel. Un bijou de pédagogie sur les structures de données, algorithmes, la génération procédurale etc. Une vrai référence notamment sur [la manipulation des grilles hexagonales](https://www.redblobgames.com/grids/hexagons/) et les algorithmes de Pathfinding. Chaque article est blindé de démos interactives, révisé sans arrêt. Contenu de très grande qualité.

## Banques de ressources

- [webcode.tools](https://webcode.tools/)
- [omatsuri](https://omatsuri.app/)
- [Jonas' Resources for Hand-Crafting Beautiful and Performant Websites](https://codingheroes.io/resources/)
- [GameDev Ressources](https://github.com/Kavex/GameDev-Resources), un dépôt recenssant une tonne de ressources pour le développement de jeux vidéos (asset, code, design, outils...)
- [Magic tools](https://github.com/ellisonleao/magictools), un autre dépôt recenssant une tonne de ressources pour le développement de jeux vidéos (asset, code, design, outils.
- [Free web development resources](https://markodenic.com/free-web-development-resources/), un site maintenant une liste de ressources pour le développement web
- [awesome-talks](https://github.com/JanVanRyswyck/awesome-talks), un dépôt maintenant une liste de conférences tech, sacré taff
- [filina consulting](https://afilina.com/), [Anna Filina](https://twitter.com/afilina?s=20&t=hsMUOt5TRY3Tl4bjrh43mA) est développeuse, consultante et intervient sur du legacy code. Elle est spécialisée dans la maintenance de projets et le développements de tests. Elle propose sur son site un tas de ressources (tutoriels, conferences, billets) 
- [Awesome Web Development Resources](https://github.com/markodenic/web-development-resources), un dépôt impressionant (et mieux organisé que celui-ci) référençant des tonnes de ressources pour le développement web


## Twitter(s)

Une grande partie des ressources présentées ici ont été partagées par d'autres personnes, notamment sur Twitter. Vous pouvez les suivre directement, elles proposent souvent des *threads* d'outils à explorer

- [@code_rams](https://twitter.com/code_rams?s=20&t=AStQKPZdtAuBUMY9rzIU5Q)
- [@_georgemolle](https://twitter.com/_georgemoller?s=20&t=AStQKPZdtAuBUMY9rzIU5Q)
- [@adarsh____gupta](https://twitter.com/adarsh____gupta?s=20&t=AStQKPZdtAuBUMY9rzIU5Q)
- [@Prathkum](https://twitter.com/Prathkum?s=20&t=ld8NhKzunXZuebfP4vVMtw)
- [@Insharamin](https://twitter.com/Insharamin?s=20&t=En9NKc7qJD5d1_OUae5Yyw)
- [@Amit_T18](https://twitter.com/Amit_T18?s=20&t=Vy0BKNzmB3NMVVv7XK0iqw)
- [@natmiletic](https://twitter.com/natmiletic?s=20&t=AStQKPZdtAuBUMY9rzIU5Q)
- [@csaba_kissi](https://twitter.com/csaba_kissi?s=20&t=AStQKPZdtAuBUMY9rzIU5Q)
- [@parik36](https://twitter.com/parik36?s=20&t=AStQKPZdtAuBUMY9rzIU5Q)
- [@htmleverything](https://twitter.com/htmleverything?s=20&t=tQ_gJCWyNfWPHVkHahh_IA)


## Trouver des livres techniques d'occasion pas cher

Les livres ça coute cher. Heureusement on en trouve plein en ligne gratuitement. Mais certain·e·s aiment bien le papier, vivre parmi les livres et en devenir familier pour retrouver facilement un chapitre dans un bouquin au pied levé, entourer, surligner, mettre des marque pages partout etc...

Pour cela on peut trouver pas mal de vieux livres mais qui restent toujours pertinent sur [recyclelivre.com](https://www.recyclivre.com/shop/11600-), une recyclerie de livres en ligne. On peut facilement repartir avec des livres de qualité pour quelques euro. En plus recyclelivre fait de la réinsertion sociale et verse une partie de ses bénéfices à des associations écolos.

Certaines villes ont peut être encore la chance d'avoir des *Librairies médicales et scientifiques*, un ancien réseau de librairies pour les étudiants. Ces librairies disposaient d'une section informatique et distribuait notamment des livres de l'éditeur O'Reilly. 

Si vous avez des adresses de librairies physiques pour des livres techniques en informatique n'hésitez pas à les suggérer via une Pull Request. C'est très difficile d'en trouver malheureusement dès qu'on s'éloigne de la capitale...