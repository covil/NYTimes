# Projet 2 - * NYTimesSearch*

** Nom de votre application ** est une application Android qui permet à un utilisateur de rechercher des articles sur le web en utilisant des filtres simples. L'application utilise [New York Times Search API] (http://developer.nytimes.com/docs/read/article_search_api_v2).

Temps passé: ** 8h** heures passées au total

## Histoires d'utilisateurs

La fonctionnalité ** requise ** suivante est terminée:

* [] L'utilisateur peut ** rechercher un article d'actualité ** en spécifiant une requête et en lançant une recherche. La recherche affiche une grille de résultats d'images de l'API de recherche du New York Times.
* [] L'utilisateur peut cliquer sur "paramètres" qui permet la sélection de ** options de recherche avancée ** pour filtrer les résultats
* [] L'utilisateur peut configurer des filtres de recherche avancés tels que:
  * [] Date de début (en utilisant un sélecteur de date)
  * [] Valeurs de bureau de nouvelles (arts, mode et style, sports)
  * [] Ordre de tri (le plus ancien ou le plus récent)
* [] Les recherches suivantes ont des filtres appliqués aux résultats de recherche
* [] L'utilisateur peut appuyer sur n'importe quel article dans les résultats pour afficher le contenu dans un navigateur intégré.
* [] L'utilisateur peut ** faire défiler vers le bas pour voir plus d'articles **. Le nombre maximal d'articles est limité par la recherche d'API.

Les fonctionnalités ** optionnelles ** suivantes sont implémentées:

* [] Implémente la gestion robuste des erreurs, [vérifier si Internet est disponible] (http://guides.codepath.com/android/Sending-and-Managing-Network-Requests#checking-for-network-connectivity), gérer les cas d'erreur , les pannes de réseau
* [] Utilisé la ** ActionBar SearchView ** ou la mise en page personnalisée comme boîte de requête au lieu d'un EditText
* [] L'utilisateur peut ** partager un lien d'article ** à ses amis ou lui envoyer un courriel
* [] Remplacement de l'activité des paramètres de filtre avec une superposition modale légère

Les fonctionnalités ** bonus ** suivantes sont implémentées:

* [] Utilisez le [RecyclerView] (http://guides.codepath.com/android/Using-the-RecyclerView) avec le `StaggeredGridLayoutManager` pour afficher l'amélioration de la grille des résultats d'image
* [] Pour les différents articles de presse qui n'ont que du texte ou seulement des images, utilisez [Disposition hétérogène] (http://guides.codepath.com/android/Heterogenous-Layouts-inside-RecyclerView) avec RecyclerView
* [] Utilisez Parcelable au lieu de Serializable en utilisant la populaire [bibliothèque Parceler] (http://guides.codepath.com/android/Using-Parceler).
* [] Utilise le [module de prise en charge de la liaison de données] (http://guides.codepath.com/android/Applying-Data-Binding-for-Views) pour lier des données dans des modèles de présentation.
* [] Remplacez tous les tirages d'icônes et autres éléments d'image statiques par [vector drawables] (http://guides.codepath.com/android/Drawables#vector-drawables), le cas échéant.
* [] Remplacer Picasso par [Glide] (http://inthecheesefactory.com/blog/get-to-know-glide-recommended-by-google/en) pour un rendu d'image plus efficace.
* [] Utilise [expressions retrolambda] (http://guides.codepath.com/android/Lambda-Expressions) pour nettoyer les blocs de gestion d'événements.
* [] Tire parti de la populaire [bibliothèque GSON] (http://guides.codepath.com/android/Using-Android-Async-Http-Client#decoding-with-gson-library) pour rationaliser l'analyse des données JSON.
* [] Utilise la [bibliothèque de mise à niveau réseau Retrofit] (http://guides.codepath.com/android/Consuming-APIs-with-Retrofit) pour accéder à l'API du New York Times.
* [] Remplacez le `WebView 'incorporé par [Chrome Custom Tabs] (http://guides.codepath.com/android/Chrome-Custom-Tabs) en utilisant un bouton d'action personnalisé pour le partage. (_ ** 2 points ** _)

Les fonctionnalités ** supplémentaires ** suivantes sont implémentées:

* [] Liste toute autre chose que vous pouvez faire pour améliorer la fonctionnalité de l'application!

## Procédure pas à pas vidéo

Voici une présentation des user stories implémentées:

<img src = 'https://imgur.com/539693e1-91cb-4d9c-9080-9614324a0aca/file.gif' title = 'Vidéo Procédure pas à pas' width = '' alt = 'Vidéo Procédure pas à pas' />

GIF créé avec [LiceCap] (https://imgur.com/ZeON2qa).

## Remarques

Décrivez les problèmes rencontrés lors de la création de l'application.

## Bibliothèques open-source utilisées

- [HTTP asynchrone Android] (https://github.com/loopj/android-async-http) - Requêtes HTTP asynchrones simples avec analyse JSON
- [Picasso] (http://square.github.io/picasso/) - Bibliothèque de chargement et de mise en cache d'images pour Android

## Licence

    Droit d'auteur [yyyy] [nom du titulaire du droit d'auteur]

    Sous licence Apache, Version 2.0 (la "Licence");
    Vous ne pouvez pas utiliser ce fichier sauf en conformité avec la licence.
    Vous pouvez obtenir une copie de la licence à

        http://www.apache.org/licenses/LICENSE-2.0

    Sauf si requis par la loi applicable ou convenu par écrit, logiciel
    distribué sous licence est distribué "TEL QUEL",
    SANS GARANTIE OU CONDITION D'AUCUNE SORTE, expresse ou implicite.
    Voir la licence pour la langue spécifique régissant les autorisations et
    limitations en vertu de la licence.
