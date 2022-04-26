+++
author = "Fred Maget"
categories = "Optimisation"
date = 2020-09-19T22:00:00Z
description = "JPG, PNG, GIF, WEBP, chaque format d’image web a ses qualités et ses défauts. Finalement, son choix ne tient qu’à vos envies et objectifs."
image = "/uploads/webplusun-blog-optimisation.jpg"
tags = "Images"
title = "quel-format-d-images-choisir-pour-mon-site-web"
type = ""
watermark = "formats"

+++
Par « format » il faut comprendre le type d’image ; je ne parle pas ici de la dimension en pixels ou en centimètres, qui a tout autant son importance. L’image est en fait constituée d’un ensemble de points appelés pixels, et sa résolution est exprimée en DPI (Dots Per Inch). Définir le bon format va servir à \[optimiser ses images pour le web\](/blog/pourquoi-optimiser-ses-images-pour-le-web/) afin d'&rsquo;'en tirer le plus grand bénéfice possible pour vos lecteurs et votre indexation.

>Les images représentent en moyenne 65% des données reçues lors de la consultation d&rsquo;une page web.

Le format d’une image est facile à trouver puisque c’est le suffixe du nom de votre image : .jpg .png .gif, etc., ce qu’on appelle l’extension. Tiens, rien qu’avec ces trois-là vous avez déjà les formats les plus répandus. Pourtant ils ont tous trois des utilisations différentes. Sans compter les autres formats existants.

<h2 id="comment-choisir-le-bon-format-d-image">Comment choisir le bon format d’image ?</h2>

Chaque format a ses qualités et ses défauts. En fait, c’est ce qu’il représente qui va définir son choix. On peut déjà distinguer les formats

<ul>

<li>standards ou automatisés, générés directement par l’appareil photo ou le smartphone : JPG, JPEG ;</li>

<li>retravaillés : GIF, PNG ;</li>

<li>optimisés : SVG ;</li>

<li>nouvelle génération: WEBP.</li>

</ul>

<h3 id="le-format-jpeg-ou-jpg">Le format JPEG, ou JPG</h3>

(Joint Photographic Experts Group)

Le plus connu car format universel devenu standard, il permet un bon compromis entre la taille et la qualité de l’image en adoptant plus de 16 millions de couleurs. C’est un format de haute qualité avec, hélas, aucune transparence possible et une marge de compression limitée.

<h3 id="le-format-gif">Le format GIF</h3>

\**(Graphics Interchange Format)**

<p>Avec le GIF, il devient possible de stocker plusieurs images dans un même fichier afin de créer des diaporamas, voire des animations. Limité à 256 couleurs, ce format permet tout de même la transparence bien qu'il ait du mal à restituer les nuances (dégradé, ombre, etc.). Très léger par défaut, le GIF restreint la qualité des images mais la compresse sans perte.</p>

<h3 id="le-format-png">Le format PNG</h3>

\**(Portable Network Graphics)**

Le format PNG a été créé par la W3C pour contourner le format GIF soumis à royalties. Il intègre la transparence et compresse sans perte de qualité, même sur des résolutions élevées. Ce format se décline en 2 versions :

<ul>

    <li>PNG 8 (bits) intègre 256 couleurs et gère la transparence, plus léger que le GIF</li>

    <li>PNG 24 (bits) intègre 16.7 millions de couleurs, une compression sans perte mais un poids de fichier plus élevé que le JPG</li>

</ul>

À savoir que, utilisé sans transparence, le résultat est souvent encore plus léger.

<h3 id="le-format-svg">Le format SVG</h3>

\**(Scalable Vector Graphics)**

Le format SVG a aussi été développé par la W3C pour décrire des ensembles de "graphiques vectoriels adaptables", c’est-à-dire que les images peuvent être automatiquement redimensionnées. De plus, la taille des fichiers est généralement plus petite que les formats JPEG et PNG, donc le temps de chargement des images est plus rapide. De plus, le SVG est reconnu par une grande partie des navigateurs.

<h3 id="le-format-webp">Le format WEBP</h3>

Selon son concepteur Google : « *60% des octets transmis sur la toile seraient des images, et WebP procurerait de 30% à 80% de réduction d&rsquo;espace face aux formats JPEG et PNG* ».

Introduit en 2010 par Google pour offrir une alternative aux autres formats, le WebP intègre la transparence, une possibilité d’animations à la manière des GIF, et une option de compression sans perte de qualité via le WebP Lossless. Le seul problème actuel est qu'il n'est reconnu par tous les navigateurs majeurs, et notamment Os et iOs.

<h2 id="poids-photo">Quel poids photo pour un site web ?</h2>

Le poids d'une image, que ce soit une photo, un logo, un visuel animé,… dépend d'abord de sa résolution. Par exemple, une photo de 300 DPI signifie qu'elle contient 300 colonnes et 300 lignes de pixels par pouce carré. Cette résolution est essentiellement utilisée pour tout ce qui est "impression" (print) : prospectus, magazine, etc. Pour un site web, il est préférable de travailler à partir d'une résolution d'image à 72 DPI. Avec les réseaux 4G+ et maintenant 5G, vous pouvez monter jusqu'à 144 DPI pour les grandes tailles d'images dans des sections spécifiques type "heros" ou "slider". \[éco-responsable\] Ne soyez pas trop gourmand quand même, car le poids des images joue un rôle important dans la vitesse d'affichage du site web.

Outre la résolution, il est aussi important de déterminer une taille stratégique concernant l'aspect responsif du site web. Pour cela, pensez vos pages sous différents formats d'écrans : ordinateurs, tablets et smartphones, et pour être plus précis d'un écran d'ordinateur ultra large (type 24' et +) à celui du smartphone tenu en mode "portrait" et "paysage". Attention, pas besoin d'aller obligatoirement d'un extrême à l'autre, concentrez-vous sur ce que votre cible (persona) est le plus susceptible d'utiliser.

     {{<img src="/images/picto-ecoresponsable.png" alt="picto ecoresponsable.png" height="32" width="32">}} Comme il est désormais préférable de privilégier la conception de votre site en "mobil first", l'idéal, pour des articles par exemple, est de publier des images qui ne demanderont pas ou peu d'agrandissement de l'image, en spécifiant -ou pas- les attribut width et height de la balise img. L'avantage est une prise en charge directe du navigateur sans passer par une nouvelle requête, d'où une économie de bande-passante et des cycles CPU.

<h2 id="redimensionner-une-image">Comment redimensionner une image pour un site web ?</h2>

Si vous êtes équipé d'outils numériques pour les retouches d'images tels que Photoshop, Lightroom, Illustrator ou CorelDraw, vous n'aurez aucun mal à préparer chaque image. Pour les autres, vous trouverez pléthore de logiciels en ligne ainsi que des tutos vidéos.

<h2 id="quelle-est-le-meilleur-format-d-image">Quelle est le meilleur format d’image ?</h2>

À ce jour, il n&rsquo;y a pas de véritables rivaux au format WebP.

D’abord parce que presque tous les navigateurs web actuels sur smartphone et ordinateur prennent en charge le format WebP. Seul Safari (Apple) est à la traine et nécessite un encodage particulier pour ne pas voir son contenu visuel absent des iPhones et MacBooks. Ensuite la conversion est facile et rapide à travers des outils comme <a href="[https://convertio.co/fr/formats/webp/](https://convertio.co/fr/formats/webp/ "https://convertio.co/fr/formats/webp/")" target="_blank" rel="noopener nofollow">Convertio</a> ou <a href="[https://imagify.io/fr](https://imagify.io/fr "https://imagify.io/fr")" target="_blank" rel="noopener nofollow">Imagify</a>. Enfin les images en WebP sont approximativement 25% plus légères que les mêmes images en JPEG et PNG, qu&rsquo;elles soient sans perte (LossLess) ou non.

Bien sûr, il existe des extensions qui peuvent être encore plus efficacement compressées, mais elles ne sont tout simplement pas prises en charge par le même nombre de navigateurs web.

<div class="text-center">

     <picture>

          <source srcset="/uploads/webplusun-tableau-avantages-images.webp" type="image/webp">

          <source srcset="/uploads/webplusun-tableau-avantages-images.png" type="image/png">

          <img src="/uploads/webplusun-tableau-avantages-images.png" class="img-fluid" alt="Tableau des avantages de chaque format d'images" data-aos="fade-up">

      </picture>

</div>

{{<img src="/images/picto-ecoresponsable.png" alt="picto ecoresponsable.png" height="32" width="32">}} D’un point de vue éco-responsable, Google annonce comme raison de la création de ce format : « *la volonté de réduire la quantité de données circulant sur Internet car, selon les développeurs, les images représentent en moyenne 65% des données reçues lors de la consultation d&rsquo;une page web. Des tests réalisés par Google en transcodant un million d’images déjà compressées avec pertes montrent qu&rsquo;en moyenne le WebP réduirait la taille des fichiers de 39% par rapport aux formats JPEG, PNG et GIF, sans perte de qualité perceptible*. »

Finalement, le choix du format ne tient qu’à votre stratégie d’acquisition vs les moyens mis en œuvre. Certes, ça demande du temps à mettre en place pour un résultat efficace, mais les retombées en valent la peine sur du long terme : WebP charge plus vite et est pris en charge par plus de 80% des navigateurs du monde entier. Et n’est-il pas plus judicieux d&rsquo;investir dans ces 80% d&rsquo;utilisateurs ? Pour les 20% restants, un bon vieux JPG ou PNG fera l’affaire.