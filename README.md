# 🍳 Projet Collaboratif MyDigitalSchool

Bienvenue dans le projet Git collaboratif du cours **"Introduction au versionnage et à Git"**.

## Objectif du projet
Ce dépôt a pour but de vous faire pratiquer les commandes Git et la collaboration via GitHub :
- Créer une branche personnelle
- Ajouter votre propre fichier ou modifier un fichier existant
- Pousser vos changements
- Créer une Pull Request pour fusionner votre travail sur `main`

## 🪜 Étapes à suivre

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/nom-utilisateur/projet-collaboratif-git.git
   cd projet-collaboratif-git
   ```

2. **Créer votre branche personnelle :**
   ```bash
   git checkout -b feature-prenom
   ```

3. **Ajouter votre contribution :**
   - Option 1 : Ajoutez votre prénom dans `team.txt`
   - Option 2 : Créez un fichier dans `recipes/` avec votre recette préférée.

4. **Valider et pousser vos changements :**
   ```bash
   git add .
   git commit -m "feat: ajout de la recette de [Votre prénom]"
   git push origin feature-prenom
   ```

5. **Créer une Pull Request sur GitHub**
   - Comparez votre branche avec `main`
   - Écrivez un message clair
   - Attendez la validation avant fusion

## Objectif final
À la fin du cours, le fichier `team.txt` contiendra le nom de tous les étudiants,  
et le dossier `recipes/` regroupera les recettes de toute la promo 🍝
