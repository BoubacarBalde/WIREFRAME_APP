Étape 1 : Cloner le projet depuis GitHub
Si vous ne l'avez pas déjà fait, clonez le projet en utilisant la commande git clone :

    git clone https://github.com/BoubacarBalde/WIREFRAME_APP.git
    cd WIREFRAME_APP

Étape 2 : Installer Flutter et Dart
Assurez-vous que Flutter et Dart sont installés sur votre système. Vous pouvez suivre les instructions d'installation sur le site officiel de Flutter.

Étape 3 : Vérifier les versions de Flutter et Dart
Vérifiez que vous utilisez les versions appropriées de Flutter et Dart en utilisant les commandes suivantes :

    flutter --version
    dart --version
  
  Assurez-vous que ces versions correspondent aux versions spécifiées dans le fichier pubspec.yaml du projet.

Étape 4 : Installer les c
Une fois que vous êtes dans le répertoire du projet, installez les dépendances du projet en utilisant la commande suivante :

    flutter pub get
  
  Cette commande va lire le fichier pubspec.yaml et télécharger toutes les dépendances nécessaires.

Étape 5 : Résoudre les problèmes de dépendances (si nécessaire)
Si vous rencontrez des problèmes de dépendances ou des erreurs, vous pouvez essayer les solutions suivantes :

Mettre à jour Flutter : En utilisant la commande suivante

    flutter upgrade

Nettoyer le cache des packages : En utilisant la commande suivante

    flutter pub cache repair

Nettoyer le projet : 

  En utilisant la commande suivante
  
    flutter clean

  En suite suite la commande suivante pour installer les dépendances
  
    flutter pub get

Étape 6 : Exécuter le projet
Enfin, vous pouvez exécuter le projet en utilisant la commande suivante :

    flutter run


Résumé des commandes:
Voici un résumé des commandes que vous utiliserez :

  #Cloner le projet
  
    git clone https://github.com/votre-utilisateur/votre-projet.git
    cd votre-projet

  #Installer les dépendances
  
    flutter pub get

  #(Optionnel) Mettre à jour Flutter
  
    flutter upgrade

  #(Optionnel) Nettoyer le cache et le projet
  
    flutter pub cache repair
    flutter clean
    flutter pub get

  #Exécuter le projet
  
    flutter run







