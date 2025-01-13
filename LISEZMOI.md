# Delphi DBExtend Library

[This page in English.](README.md)

Delphi est un environnement de développement permettant de programmer en Pascal tout en étant assisté par un grand nombre d'outils intégrés allant de la conception au déploiement de projets pour Windows, macOS, iOS, Android et Linux.

Ce projet contient des unités et des composants permettant d'étendre le fonctionnement des composants fournis en standard avec Delphi sur les bases de données.

Il peut aussi être utilisé dans le cadre d'un fonctionnement de Delphi en no code, de façon autonome ou associé à d'autres [librairies de composants no code pour Delphi](https://github.com/DeveloppeurPascal/Delphi-NoCode-Library).

Ce projet est un complément de frameworks de composants de bases de données existants dans Delphi ou son ecosystème.

Il cible pour le moment dbExpress et FireDAC mais pourra être étendu à ADO, UniDAC et d'autres si le besoin s'en fait sentir.

Ce dépôt de code contient un projet développé en langage Pascal Objet sous Delphi. Vous ne savez pas ce qu'est Dephi ni où le télécharger ? Vous en saurez plus [sur ce site web](https://delphi-resources.developpeur-pascal.fr/).

## Présentations et conférences

### XXX 2024

* [talk title](talk url) (en anglais)
* [talk title](talk url) (en français)

### Twitch

Suivez les streams de développement de jeux vidéo sur [ma chaîne Twitch](https://www.twitch.tv/patrickpremartin) ou en rediffusion sur [Serial Streameur](https://serialstreameur.fr) la plupart du temps en français.

## Utiliser ce logiciel

Ce logiciel est disponible dans une version de production directement installable ou exécutable. Il est distribué en shareware.

Vous pouvez le télécharger et le rediffuser gratuitement à condition de ne pas en modifier le contenu (installeur, programme, fichiers annexes, ...).

[Télécharger le programme ou son installeur](DDD)

Si vous utilisez régulièrement ce logiciel et en êtes satisfait vous êtes invité à en acheter une licence d'utilisateur final. L'achat d'une licence vous donnera accès aux mises à jour du logiciel en plus d'activer d'évenuelles fonctionnalités optionnelles.

[Acheter une licence](FFF)

Vous pouvez aussi [consulter le site du logiciel](EEE) pour en savoir plus sur son fonctionnement, accéder à des vidéos et articles, connaître les différentes versions disponibles et leurs fonctionnalités, contacter le support utilisateurs...

## Installation des codes sources

Pour télécharger ce dépôt de code il est recommandé de passer par "git" mais vous pouvez aussi télécharger un ZIP directement depuis [son dépôt GitHub](https://github.com/DeveloppeurPascal/XXXXXXXXXX).

Ce projet utilise des dépendances sous forme de sous modules. Ils seront absents du fichier ZIP. Vous devrez les télécharger à la main.

* [YYY](ZZZ) doit être installé dans le sous dossier ./lib-externes/YYY
* [YYY](ZZZ) doit être installé dans le sous dossier ./lib-externes/YYY

## Compatibilité

En tant que [MVP Embarcadero](https://www.embarcadero.com/resources/partners/mvp-directory) je bénéficie dès qu'elles sortent des dernières versions de [Delphi](https://www.embarcadero.com/products/delphi) et [C++ Builder](https://www.embarcadero.com/products/cbuilder) dans [RAD Studio](https://www.embarcadero.com/products/rad-studio). C'est donc dans ces versions que je travaille.

Normalement mes librairies et composants doivent aussi fonctionner au moins sur la version en cours de [Delphi Community Edition](https://www.embarcadero.com/products/delphi/starter).

Aucune garantie de compatibilité avec des versions antérieures n'est fournie même si je m'efforce de faire du code propre et ne pas trop utiliser les nouvelles façons d'écrire dedans (type inference, inline var et multilines strings).

Si vous détectez des anomalies sur des versions antérieures n'hésitez pas à [les rapporter](https://github.com/DeveloppeurPascal/XXXXXXXXXX/issues) pour que je teste et tente de corriger ou fournir un contournement.

## Licence d'utilisation de ce dépôt de code et de son contenu

Ces codes sources sont distribués sous licence [AGPL 3.0 ou ultérieure](https://choosealicense.com/licenses/agpl-3.0/).

Vous êtes globalement libre d'utiliser le contenu de ce dépôt de code n'importe où à condition :
* d'en faire mention dans vos projets
* de diffuser les modifications apportées aux fichiers fournis dans ce projet sous licence AGPL (en y laissant les mentions de copyright d'origine (auteur, lien vers ce dépôt, licence) obligatoirement complétées par les vôtres)
* de diffuser les codes sources de vos créations sous licence AGPL

Si cette licence ne convient pas à vos besoins vous pouvez acheter un droit d'utilisation de ce projet sous la licence [Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/) ou une licence commerciale dédiée ([contactez l'auteur](https://developpeur-pascal.fr/nous-contacter.php) pour discuter de vos besoins).

Ces codes sources sont fournis en l'état sans garantie d'aucune sorte.

Certains éléments inclus dans ce dépôt peuvent dépendre de droits d'utilisation de tiers (images, sons, ...). Ils ne sont pas réutilisables dans vos projets sauf mention contraire.

## Comment demander une nouvelle fonctionnalité, signaler un bogue ou une faille de sécurité ?

Si vous voulez une réponse du propriétaire de ce dépôt la meilleure façon de procéder pour demander une nouvelle fonctionnalité ou signaler une anomalie est d'aller sur [le dépôt de code sur GitHub](https://github.com/DeveloppeurPascal/XXXXXXXXXX) et [d'ouvrir un ticket](https://github.com/DeveloppeurPascal/XXXXXXXXXX/issues).

Si vous avez trouvé une faille de sécurité n'en parlez pas en public avant qu'un correctif n'ait été déployé ou soit disponible. [Contactez l'auteur du dépôt en privé](https://developpeur-pascal.fr/nous-contacter.php) pour expliquer votre trouvaille.

Vous pouvez aussi cloner ce dépôt de code et participer à ses évolutions en soumettant vos modifications si vous le désirez. Lisez les explications dans le fichier [CONTRIBUTING.md](CONTRIBUTING.md).

## Supportez ce projet et son auteur

Si vous trouvez ce dépôt de code utile et voulez le montrer, merci de faire une donation [à son auteur](https://github.com/DeveloppeurPascal). Ca aidera à maintenir le projet (codes sources et binaires).

Vous pouvez utiliser l'un de ces services :

* [GitHub Sponsors](https://github.com/sponsors/DeveloppeurPascal)
* Ko-fi [en français](https://ko-fi.com/patrick_premartin_fr) ou [en anglais](https://ko-fi.com/patrick_premartin_en)
* [Patreon](https://www.patreon.com/patrickpremartin)
* [Liberapay](https://liberapay.com/PatrickPremartin)
* [Paypal](https://www.paypal.com/paypalme/patrickpremartin)

ou si vous parlez français vous pouvez [vous abonner à Zone Abo](https://zone-abo.fr/nos-abonnements.php) sur une base mensuelle ou annuelle et avoir en plus accès à de nombreuses ressources en ligne (vidéos et articles).
