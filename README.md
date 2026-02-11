# 🛡️ Étude du Top 10 OWASP 2025 - Projet Académique

Bienvenue sur le dépôt collaboratif dédié à l'étude des vulnérabilités de sécurité web. Ce projet a pour objectif de documenter les failles critiques répertoriées par l'**OWASP** afin de mieux comprendre les risques et les méthodes de remédiation.

## 👥 Équipe du Projet

* **Lead / Administrateur** : @oubaidHL
* **Contributeurs** : @FARAH @EWwAN @AURORE

---

## 🛠️ Instructions de Collaboration (Règles Git)

Pour maintenir la propreté du code et éviter les erreurs, des règles de protection ont été mises en place :

1. **Interdiction de pousser (push) sur `main`** : La branche principale est verrouillée.
2. **Branches individuelles** : Chaque membre doit créer une branche dédiée à sa faille.
3. **Validation par Pull Request (PR)** : Pour fusionner votre travail dans `main`, vous devez ouvrir une PR qui sera revue.

### Comment contribuer ?

```bash
# 1. Cloner le projet
git clone https://github.com/oubaidHL/faille-explorer.git

# 2. Créer votre branche spécifique (ex: A03-Injection)
git checkout -b AXX-Nom-De-La-Faille

# 3. Travailler dans votre propre dossier
# 4. Envoyer vos modifications
git add .
git commit -m "Ajout de la documentation pour [Nom de la faille]"
git push origin AXX-Nom-De-La-Faille

```

---

## 📁 Structure du Projet

Chaque branche doit contenir un dossier nommé selon la faille, incluant un fichier `README.md` détaillé :

```text
📂 Projet_OWASP
 ┣ 📂 A01_Broken_Access_Control
 ┃ ┗ 📜 README.md
 ┣ 📂 A03_Injection
 ┃ ┗ 📜 README.md
 ┗ ...

```

---

## 📖 Contenu attendu par Faille

Pour chaque vulnérabilité, merci de respecter le plan suivant dans votre documentation :

* **Description** : Explication technique de la faille.
* **Scénario d'attaque** : Comment un pirate pourrait exploiter cette vulnérabilité.
* **Exemple de code** : Un extrait de code vulnérable et sa version sécurisée.
* **Prévention** : Liste des bonnes pratiques pour corriger la faille.

---

## 🔗 Ressources Utiles

* [Site Officiel OWASP](https://owasp.org/www-project-top-ten/)
* [Documentation Git pour débutants](https://git-scm.com/doc)

---

*Ce projet est réalisé dans un cadre pédagogique. Ne pas utiliser les techniques décrites à des fins malveillantes.*

---

### Prochaine étape pour toi :

1. **Enregistre** ce texte dans ton fichier `README.md`.
2. Fais un **commit** et un **push** sur GitHub.
3. Vérifie que tes camarades ont bien reçu l'invitation "Collaborator" pour qu'ils puissent commencer à créer leurs branches.

Souhaites-tu que je te prépare un exemple de fichier `README.md` spécifique pour la faille "Injection SQL" que tu pourras mettre dans un dossier pour montrer l'exemple ?
