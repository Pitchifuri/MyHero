


Ce plugin s'utilise facilement. (mais bon, ça casse pas la baraque hein!)

Tout d'abord, coller le link scss "hero-plugin.css" dans le head de votre html:

<link rel="stylesheet" href="http://cepegra-labs.be/webdesign/2017/phec/_hero-plugin.css">


Il s'agit de placer les différentes classes sur vos éléments html.
Vous devez tout d'abord créer un "container" (un div fait l'affaire, bien que d'autres balises comme les sections sont utilisables aussi).
Ajoutez la classe "hero-cover" sur celui-ci.

Placez votre image de "background" directement dans le container à l'aide d'une balise img.

Si vous voulez ajouter un titre, placez-le dans votre container et ajoutez-lui la classe "hero-title".
Il sera centré, avec un top de 30%.

Si vous voulez ajouter un paragraphe, placez-le dans votre container et ajoutez-lui la classe "hero-paragraph".
Il sera centré, avec un top de 50%.

Pour utiliser les effets "dark-filter" et "light gradient" il vous faudra créer un deuxième container à l'intérieur du premier. C'est
sur celui-ci que vous ajouterez la classe "dark-filter" ou "gradient". Votre titre ainsi que votre paragraphe
doivent se retrouver à l'intérieur de celui-ci.


Vous pouvez gérer vous-même les dimensions de votre container ".hero-cover" en lui ajoutant une classe de votre choix.

