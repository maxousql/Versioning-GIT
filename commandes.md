# Commandes Versionning GitHub

## Les fichiers ont trois états dans git :
- Modifié (modified) checker avec la commande "git status"
- Indexé (staged) utiliser la commande "git add"
- Validé (commited) utiliser la commande "git commit"

-m est pour ajouter un msg de commit après le -m "ajouter msg"
- push

# Création et indexage 
- git add .
- git commit -m "update"
- git push -u origin main
- si la modification ne se fait pas il faut rajouter l'url "git remote add origin git@github.com:OukhtySama/VersioningGithub.git"

# Clonage 
- git clone https://github.com/OukhtySama/VersioningGithub.git

# Gestion fichier
- touch test.txt(nom fichier) : touch permet de créer un fichier 
- git add .
- git commit -m "Update" ( il faut commit le plus souvent possible  1 tache un commit)
- git rm --cached test.txt (nom fichier)
- git add .
- git status