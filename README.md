# Système de Gestion des Employés
Ce projet est une application en C++ permettant de gérer les données des employés stockées dans un fichier. Elle permet aux utilisateurs d'effectuer diverses opérations, telles que l'ajout, la recherche et la suppression de dossiers d'employés, la génération de rapports et le calcul des salaires.

Fonctionnalités
Le système de gestion des employés inclut les fonctionnalités suivantes :

Ajouter un Employé
Ajouter les informations d'un nouvel employé, y compris son ID, nom, email et détails de salaire.

Imprimer des Rapports d'Employés
Afficher un rapport détaillé de tous les employés, comprenant :

Salaire de base
Fonds de prévoyance (PF)
Assurance santé (HlthInc)
Salaire net
Rechercher un Employé
Rechercher les détails d’un employé à l’aide de son ID unique.

Supprimer un Employé
Supprimer l'enregistrement d’un employé du système.

Sauvegarder
Enregistrer les données actuelles dans un fichier pour assurer leur persistance.

Quitter
Quitter l’application en toute sécurité.

Captures d'Écran
Menu Principal

Rapport des Employés

Technologies Utilisées
Langage de Programmation : C++
Gestion des Fichiers : Utilisée pour la persistance des données
Application Basée sur le Terminal
Comment Lancer l'Application
Clonez ce dépôt :
bash
Copy code
git clone https://github.com/votre-nom-utilisateur/systeme-gestion-employes.git
Accédez au répertoire du projet :
bash
Copy code
cd systeme-gestion-employes
Compilez le code :
bash
Copy code
g++ -o gestion_employes main.cpp
Exécutez l'application :
bash
Copy code
./gestion_employes
Structure des Fichiers
main.cpp : Contient la logique principale de l'application.
employee_data.txt : Fichier utilisé pour stocker les informations des employés.
Améliorations Futures
Ajouter une interface graphique pour une meilleure expérience utilisateur.
Implémenter un chiffrement des données sensibles.
Intégrer une base de données pour une meilleure scalabilité.
