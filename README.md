Fichier README.md# Simulation IOT pour maison intelligente (Smart Home) avec Tinkercad 
## 📖 À propos du projet
Ce rapport décrit en détail l'utilisation de Tinkercad pour la simulation de systèmes IoT domotiques. Il aborde les bases de l'IoT et de Tinkercad. Ce guide présente des capacités de simulation et des étapes pratiques pour la configuration et la programmation d'appareils domotiques virtuels. Son objectif est de fournir un guide complet aux développeurs et aux passionnés souhaitant explorer les concepts de l'IoT dans un environnement sans risque.

## 🎓 Contexte AcadémiqueInstitution : Université d'Ain Temouchent-
Belhadj Bouchaib 
Département : Mathématiques et d'informatique
Formation : Master en Intelligence Artificielle et Cybersécurité
Auteur : BENTSABET Amira 
Année Universitaire : 2025_2026

## 🛠️ Matériel Utilisé (Hardware)
Au cœur du système se trouve l'Arduino Uno R3, microcontrôleur central qui traite les informations des capteurs et commande les actionneurs.
Les composants simulés incluent :
Arduino Uno R3 : Microcontrôleur polyvalent (ATmega328P), idéal pour le prototypage IoT.
Capteur de Mouvement PIR : Détecte la présence humaine, utile pour l'éclairage de sécurité ou les alarmes.
Capteur de Température : Mesure la température ambiante, essentiel pour les systèmes CVC intelligents.
Capteur de Gaz : Détecte les fuites de gaz dangereuses, fournissant des alertes de sécurité critiques.
Capteur d'Humidité : Surveille le niveau d'humidité, important pour le confort et la prévention des moisissures.
Écran LCD : Affiche les données des capteurs ou l'état du système.

## ⚙️ Scénarios d'Automatisation 
Clés Sécurité (Détection de Mouvement) : Le capteur PIR détecte les mouvements inattendus et active une alerte visuelle (LED) et une notification mobile pour une sécurité renforcée.
Confort Thermique (Régulation Automatique) : Un capteur de température ajuste chauffage ou ventilation pour maintenir une température agréable, optimisant la consommation d'énergie.
Éclairage Intelligent (Présence) : Capteur PIR et de luminosité allument/éteignent les lumières automatiquement selon la présence, réduisant la consommation électrique.
Qualité de l'Air (Multi-Capteurs) : Les capteurs d'humidité et de température activent déshumidificateur ou ventilation pour un environnement sain, prévenant moisissures.

# 💻 Lancer la Simulation
* Connectez l'Arduino, la plaque d'essai, les capteurs (ex: PIR) et les actionneurs (ex: LED avec résistance).
* Accédez à l'éditeur de code.Utilisez des blocs ou du code C++ pour définir le comportement des capteurs et actionneurs.
* Cliquez sur "Démarrer la simulation".Interagissez avec les capteurs pour observer la réaction des actionneurs.
* Ouvrez le moniteur série pour visualiser les données des capteurs (ex: température, mouvement) et les messages de débogage.
