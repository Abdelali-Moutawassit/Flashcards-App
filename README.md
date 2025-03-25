# Flashcards App

## Description
L'application **Flashcards** est une application Flutter interactive qui permet aux utilisateurs d'apprendre en utilisant des cartes de questions-réponses. Les utilisateurs peuvent faire défiler les cartes et les retourner pour voir les réponses. L'application utilise la bibliothèque `flip_card` pour l'animation des cartes et `swipeable_card_stack` pour le balayage des cartes.

## Fonctionnalités
- Affichage de cartes avec une question et une réponse.
- Flip des cartes pour voir les réponses.
- Balayage des cartes à gauche/droite pour supprimer ou conserver.
- Ajout automatique de nouvelles cartes après chaque balayage.

## Technologies utilisées
- **Flutter**: Framework de développement d'applications mobiles.
- **Dart**: Langage de programmation utilisé avec Flutter.
- **flip_card**: Bibliothèque permettant d'animer les cartes retournables.
- **swipeable_card_stack**: Bibliothèque permettant de glisser les cartes dans différentes directions.
- **google_fonts**: Pour utiliser des polices personnalisées.

## Structure du projet
```
/flashcards_app
│── lib/
│   ├── main.dart              # Point d'entrée de l'application
│   ├── card_model.dart        # Modèle de données pour une carte
│   ├── card_view.dart         # Widget affichant une carte
│   ├── home_page.dart         # Page principale contenant les cartes
│── assets/
│   ├── delete.png             # Icône pour supprimer une carte
│   ├── check.png              # Icône pour valider une carte
│── pubspec.yaml               # Fichier de configuration des dépendances Flutter
│── README.md                  # Documentation du projet
```

## Installation
1. **Cloner le projet**
   ```sh
   git clone https://github.com/votre-repo/flashcards-app.git
   cd flashcards-app
   ```
2. **Installer les dépendances**
   ```sh
   flutter pub get
   ```
3. **Lancer l'application**
   ```sh
   flutter run
   ```

## Dépendances
Ajoute ces dépendances dans `pubspec.yaml` si elles ne sont pas encore incluses :
```yaml
dependencies:
  flutter:
    sdk: flutter
  flip_card: ^0.6.0
  swipeable_card_stack: ^0.2.0
  google_fonts: ^6.1.0
```

## Utilisation
- Ouvrir l'application.
- Faire défiler les cartes en balayant vers la gauche ou la droite.
- Retourner les cartes pour voir les réponses.
- De nouvelles cartes apparaissent automatiquement après un balayage.

## Améliorations futures
- Ajout d'une base de données locale (SQLite ou Hive) pour sauvegarder les cartes.
- Personnalisation des cartes par l'utilisateur.
- Ajout d'un mode d'entraînement avec suivi des performances.

## Auteur
- **[ABDELALI MOUTAWASSIT]** – Développeur Flutter


