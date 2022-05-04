# Rapport d’optimisation
_(Projet 4 OpenClassrooms - Optimisez un site web existant)_

![Logo La Panthère](https://i.imgur.com/0JlBwl3.png)

Agence La Panthère | Entreprise de web design à Lyon
L'agence de Web design; La Panthère à Lyon est là pour tous vos besoins de développement Stratégique et d'Attractivité sur internet !

## Site de base

Site de base de L'agence La Panthère avant amélioration SEO et Accessibility
* [La Panthère Base](https://vincent-sniteur.github.io/P4-base/) - Site sans modification
* [Git La Panthère Base](https://github.com/Vincent-Sniteur/P4-base) - Git sans modification

### Score Measure page sans modification

![Score Site de Base](https://i.imgur.com/tWvLg3E.png)
### Remarque : 
* Performance basse à cause du temps de chargement de la page.

* Accessibilité dans la moyenne basse, quelque point important à améliorer pour les utilisateurs.

* SEO très bas a cause de l’utilisation de méthode BlackHat et d’un manque de certaines balises importantes comme un titre, une description et l’utilisation de mot clé.

### Score GTmetrix page sans modification

![Note GTMetrix Avant](https://i.imgur.com/294RDDP.png)
### Remarque : 
* Un chargement très long lié en grande partie au format et l’encodage des images.

* Des scripts charger avant le contenu.

* Un manque de minification des ressources CSS & JS.

### Score Dareboost avant optimisation :

![Note Dareboost Avant](https://i.imgur.com/qj496ml.png)
### Remarque : 
* Un temps de chargement de presque 3 secondes.

* Non-respect du “Core Web Vitals” qui représente les performances en rapidité d’affichage, interactivité et stabilité.
_Peuvent être utilisés comme classement par des moteurs de recherche._

* Un poids de 4 Mo pour les ressources a été chargé.

* Et un Speed Index de 1962 qui est la vitesse d’affichage de la partie visible du site, plus le chargement est rapide plus le score sera petit. 
_Google recommande un score en dessous de 1000_







## Site Améliorer & Résultat

### Site améliorer de L'agence La Panthère
* [La Panthère Base](https://vincent-sniteur.github.io/P4-base/) - Site avec modification
* [Git La Panthère Base](https://github.com/Vincent-Sniteur/P4-base) - Git avec modification

### Score Measure page avec modification

![Score Site Améliorer](https://i.imgur.com/Arhs5cD.png)

### Remarque : 
* Performance en nette amélioration après une modification des formats, des tailles d’images et d’une compression et pour les ressources JS & CSS une minification pour améliorer le poids et la lecture.


* Accessibilité amélioration après modification des tailles de fonts, leurs couleurs et leur contraste avec leur background, modification des noms de pages pour les rendre plus intelligibles et suppression de certains paragraphes charger en image pour les ajoutés en texte brut HTML.


* SEO grosse amélioration après l’ajout d’une description, d’un titre d’une balise canonique et ou encore de l’utilisation de mot clé important et de la suppression des méthodes BlackHat présente sur le site.



### Score GTmetrix page avec modification

![Note GTMetrix Après](https://i.imgur.com/IW8UZ99.png)
### Remarque : 
* Un chargement amélioré après modification des images, des scripts et une minification des ressources.

### Score Dareboost après optimisation :

![Note Dareboost Après](https://i.imgur.com/UrROgws.png)
### Remarque : 
* Le chargement global s'améliore de plus de 2 secondes.

* Le respect du “Core Web vitals”.

* Amélioration du poids des ressources a chargé de plus de 3 Mo.

* Speed Index améliorer et en dessous de la barre des 1000 comme recommandés par google.

* Amélioration sur le “Cumulative Layout Shift” qui représente la stabilité de la page.




## Résultat

### Une amélioration moyenne de : 

* Performance > +21

* Accessibilité > +11

* SEO > +22

* Temps de chargement en baisse de plus de 2 secondes.

* Respect du “Core Web Vitals” et bon score pour le “speed Index” comme recommandée par google.



## Modification Apporter

### SEO :
* <Meta> Description : Ajoutez une description cohérente selon les
bonnes pratiques à adopter

* <title> : Ajout d'un titre simple et accrocheur avec des mots-clés et le
nom de marque pour donner envie au consommateur de cliquer.

* Suppression des liens du footer. ( Black-Hat )

* Suppression des keywords cachés. ( Black-Hat )

* Ajout d’une <meta> “robots” pour dire au robot google que le site doit être indexé et follow.

* Ajout d’un fichier Robots.txt pour indiquer au robot google les liens à explorer ou non.

* Ajout d’un fichier SiteMap.txt pour lister les liens à lire et faciliter le crawling du site.

* Ajout d’une balise canonique pour permettre d’éviter des problèmes de contenus dupliqués et d'avoir une sorte d'URL préférée.

* Spécification de la langue “FR” sur les pages pour un meilleur référencement local.

* Ajout d’une <meta> OpenGraph et TwitterCard pour les réseaux sociaux.

* Ajout d’un suivi google analytics pour permettre d'avoir un outil de visualisation sur les stats.


### Accessibility :
* Remplacement des textes en image par de vrais paragraphes directement dans le code HTML de la page.

* Modification du nom des pages pour les rendre intelligibles.

* Modification de la taille des textes en 16 Pixels.

* Modification des couleurs du site pour un meilleur contraste.

* Ajout de zone placeholder dans le formulaire de contact.

* Amélioration de la responsivité pour la version mobile.

* Ajout de texte “descriptif” pour certaines images ou lien pour faciliter la compréhension.

* Ajout et vérification des attributs alt pour chaque image.

### Performance :
* Modification des images dans un format adapté. ( WEBP)

* Compression des images et modification des tailles.

* Retardement des scripts non obligatoires à l'affichage pour assurer un chargement de la page rapide.

* Ajout d'un temps de chargement lent sur les images pour faciliter le chargement du site.


## Logiciel / Site utilisé

* [Measure](https://web.dev/measure/)
* [PageSpeed Insights](https://pagespeed.web.dev/)
* [GTMetrix](https://gtmetrix.com/)
* [Dareboost](https://www.dareboost.com/fr)

## Auteurs

* **Vincent ~ Sniteur** _alias_ [@Vincent-Sniteur](https://github.com/Vincent-Sniteur)
Started : 20/04/2022
Finished : 04/05/2022