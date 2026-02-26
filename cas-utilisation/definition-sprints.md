# Définition des Sprints et Cas d'Utilisation

Ce document détaille la planification agile du projet **SoliQuiz**, divisée en deux sprints majeurs : le MVP (Minimum Viable Product) et les fonctionnalités avancées.

## Sprint 1 : MVP (Focus : Cœur du système et Valeur immédiate)
**Objectif** : Permettre au formateur de créer un QCM simple et à l'étudiant de le passer avec un calcul de score automatique.

### Cas d'Utilisation (UC) du Sprint 1 :
1.  **UC1-1 : Création de QCM (Structure de base)**
    *   Le formateur crée un titre de QCM et une description.
2.  **UC1-2 : Gestion des Questions et Choix (Essentiel)**
    *   Ajouter des questions à choix unique/multiple.
    *   Définir la bonne réponse pour chaque question.
3.  **UC1-3 : Passation de QCM (Étudiant)**
    *   L'étudiant accède au QCM et coche ses réponses.
4.  **UC1-4 : Calcul automatique du Score (Global)**
    *   Le système valide les réponses et affiche un score total (ex: 15/20) immédiatement.
5.  **UC1-5 : Authentication de base**
    *   Connexion simple pour identifier qui passe le test (Formateur vs Étudiant).

---

## Sprint 2 : Fonctionnalités Avancées (Focus : Pédagogie et Analyse)
**Objectif** : Répondre aux besoins spécifiques de granularité (Youssef/Soufiane) et d'ergonomie (Mehdi/Fatine).

### Cas d'Utilisation (UC) du Sprint 2 :
1.  **UC2-1 : Liaison Session et Objectif Pédagogique**
    *   Lier un QCM à une session spécifique et à un micro-objectif.
2.  **UC2-2 : Analyse de Performance par Objectif**
    *   Calculer et afficher le score détaillé (ex: "Logique : 80%, Syntaxe : 20%").
3.  **UC2-3 : Feedback Détaillé & Correction (Soufiane)**
    *   Afficher la correction après la validation avec les explications des bonnes réponses.
4.  **UC2-4 : Historique et Tableau de bord (Étudiant & Formateur)**
    *   Consultation des anciens scores et suivi de la progression sur la durée.
5.  **UC2-5 : Améliorations UX & Techniques (Mehdi)**
    *   Implémentation d'un **Timer (Compte à rebours)** visible.
    *   Sauvegarde automatique des réponses en cours (prévention des coupures).
    *   Optimisation de l'interface mobile-first.
6.  **UC2-6 : Exportation vers SoliLMS (Optionnel/Vision)**
    *   Préparation des données pour l'intégration automatique des notes dans le LMS.
