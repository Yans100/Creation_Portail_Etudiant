
# Portail étudiant — INF1034

Application de bureau JavaFX simulant un portail étudiant avec authentification, gestion des notes, des tâches et de l'horaire.

## Fonctionnalités

- Authentification par courriel et mot de passe
- Consultation des notes par cours avec comparaison à la moyenne
- Gestion de tâches avec date et titre (ajout et suppression)
- Affichage de l'horaire des examens
- Navigation multi-fenêtres via un système de layout centralisé
- Persistance des données utilisateur en JSON (Jackson)

## Technologies

- Java 19
- JavaFX 19
- Maven
- FXML
- Jackson
- ControlsFX

## Prérequis

- Java 19+
- Maven 3.8+

## Lancer le projet

```bash
mvn javafx:run
```

## Compte de test

```
Courriel  : test
Mot de passe : pass
```

## Structure

```
src/main/
  java/com/example/projet_finale/
    controller/    — contrôleurs JavaFX
    App.java       — point d'entrée
    Database.java  — singleton de données
    Student.java   — modèle étudiant
    Note.java      — modèle note
    Task.java      — modèle tâche
  resources/       — fichiers FXML et CSS
```

---

Projet universitaire en équipe — cours INF1034, UQTR.
