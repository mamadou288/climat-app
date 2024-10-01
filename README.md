Application Climat
Application Climat est une application web simple qui permet aux utilisateurs de rechercher les informations météorologiques d'une ville spécifique. L'application utilise l'API d'OpenWeatherMap pour récupérer en temps réel des données météorologiques telles que la température, l'humidité, la vitesse du vent et les conditions météorologiques comme la pluie, les nuages ou le brouillard.

Fonctionnalités
Recherche Météo par Ville : Entrez le nom d'une ville pour obtenir ses informations météorologiques actuelles.
Données Météorologiques en Temps Réel : Affiche la température, l'humidité et la vitesse du vent en direct.
Gestion des Erreurs : Affiche un message d'erreur si la ville n'est pas disponible ou si elle est mal orthographiée.
Icônes Météo : Met à jour dynamiquement les icônes en fonction des conditions météorologiques de la ville (ex : ciel dégagé, pluie, nuages).
Technologies Utilisées
HTML5 pour la structure de la page.
CSS3 pour le style et la mise en page.
JavaScript pour la logique de l'application, les requêtes API, et l'affichage dynamique des données.
API OpenWeatherMap pour récupérer les données météorologiques.
Installation et Utilisation
Cloner le projet :
git clone https://github.com/votre-utilisateur/votre-repo.git
Accéder au dossier du projet :
cd votre-repo
Ouvrir index.html dans votre navigateur :

Lancez le fichier index.html directement dans votre navigateur pour commencer à utiliser l'application.
API OpenWeatherMap
Pour obtenir des données météo, l'application utilise l'API OpenWeatherMap. Vous pouvez modifier la clé API directement dans le fichier index.html :

javascript
const apiKey = "votre_clé_api";

Structure des Fichiers
index.html : Contient la structure de base de l'application, les éléments visuels ainsi que la logique de recherche et d'affichage des données météorologiques.
style.css : Fichier de style qui gère la mise en page et le design de l'application.
images/ : Contient les icônes météo utilisées pour représenter les différentes conditions météorologiques.
Avertissement
Assurez-vous d'avoir une clé API valide d'OpenWeatherMap.
