# Projet : Scanner de Vulnérabilités SQL Injection

## Description
Ce projet est un outil de scan de vulnérabilités SQL injection pour analyser les formulaires d'une page web et tester leur résilience face aux attaques par injection SQL. L'outil extrait les formulaires disponibles sur la page spécifiée, soumet des charges malveillantes basiques, et analyse les réponses pour détecter des erreurs indiquant une vulnérabilité.

## Objectifs et Fonctionnalités

- **Extraction des Formulaires** : Utilisation de BeautifulSoup pour localiser et extraire tous les formulaires présents sur la page cible.
- **Analyse des Champs** : Collecte des détails des champs de chaque formulaire (type, nom, valeur) pour simuler des soumissions réalistes.
- **Injection et Détection de Vulnérabilités SQL** : Envoie des charges d’injection SQL aux formulaires et inspecte la réponse pour des messages d’erreur indiquant une vulnérabilité potentielle.
- **Rapport de Résultats** : Indique si des vulnérabilités SQL injection ont été trouvées, ce qui permet à l'utilisateur d'identifier les points faibles dans la sécurité du site.

## Technologies Utilisées

- **Python** : Langage de programmation principal.
- **Requests** : Utilisé pour gérer les requêtes HTTP, permettant de simuler les envois de formulaires.
- **BeautifulSoup** : Bibliothèque pour l'analyse et l'extraction de données HTML.
- **User-Agent Personnalisé** : Pour imiter un navigateur et éviter les restrictions de sites.

## Code et Structure

- **Fonction `get_forms()`** : Récupère tous les formulaires de la page web.
- **Fonction `form_details()`** : Analyse chaque formulaire et collecte les détails des champs.
- **Fonction `vulnerable()`** : Vérifie les réponses pour détecter des indices de vulnérabilité SQL injection.
- **Fonction `sql_injection_scan()`** : Coordonne l'analyse et envoie des charges aux formulaires pour tester leur résilience.

## Exemple d’Utilisation
En exécutant le script et en fournissant l'URL d'une page cible, l’outil analyse les formulaires, exécute les tests d’injection SQL et fournit un retour sur les vulnérabilités potentielles.
