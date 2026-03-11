# SR10-Projet
Projet SR10 Plateforme de recrutement

Antonin Fillipi / Maxime Boschet


Déroulé du projet: \n
    1ère phase: Usecase, Conception BDD, Carte site WEB + prototype IHM \n
        ->Dossier Livrable (document pdf du 1 er livrable attendu) \n
        ->1er commit avec structuration du projet (dossiers et début de configuration, packages)
    2ème phase: 



Cycle d'une requête: Navigateur → Express → Middleware (session, cookies…) → Route → Modèle (MySQL) → Vue (EJS) → Réponse


"
Bonnes pratiques Git & GitHub
1. Travailler avec des branches
Ne jamais travailler directement sur main. Crée une branche par fonctionnalité :


git checkout -b feature/nom-de-la-fonctionnalite
# ... travail ...
git push origin feature/nom-de-la-fonctionnalite
Puis crée une Pull Request sur GitHub pour merger dans main.

2. Commits clairs et fréquents
Un commit = une seule chose logique
Message court et descriptif

# Bien
git commit -m "Ajout de la page de connexion"

# Pas bien
git commit -m "modifications" ou "fix"
3. Toujours pull avant de travailler
Avant de commencer ta journée ou une session de travail :


git pull origin main
Évite les conflits et garde ton code à jour.

4. Ne pas committer certains fichiers
Ajoute dans ton .gitignore :

node_modules/
.env (variables d'environnement, mots de passe)
Fichiers de build (dist/, build/)
5. Workflow recommandé au quotidien

git pull origin main          # 1. Mettre à jour
git checkout -b ma-branche    # 2. Créer une branche
# ... coder ...
git add .                     # 3. Ajouter les fichiers
git commit -m "Mon message"   # 4. Committer
git push origin ma-branche    # 5. Pousser
# 6. Créer une Pull Request sur GitHub
6. Résumé visuel

main ──────────────────────────────► (production stable)
         │                 ▲
         └── feature/xyz ──┘  (Pull Request)
Pour un projet scolaire à plusieurs, l'essentiel est : branches + commits clairs + pull avant de travailler.


