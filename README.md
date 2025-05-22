# Va dans le dossier du projet téléchargé
cd /chemin/vers/ton/dossier

# Initialise Git
git init

# Ajoute un dépôt distant (remplace l’URL par celle de ton GitHub)
git remote add origin https://github.com/ton-utilisateur/ton-repo.git

# Ajoute les fichiers
git add .

# Commit les fichiers
git commit -m "Ajout du fichier depuis WeTransfer"

# Envoie sur GitHub
git push -u origin main
