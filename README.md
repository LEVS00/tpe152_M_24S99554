# Ouvre un terminal dans le dossier contenant ton projet
cd tpe_152_M_24S99554

# Initialise un dépôt Git local
git init

# Connecte-le à ton dépôt GitHub (remplace par ton lien réel)
git remote add origin https://github.com/TON_UTILISATEUR/tpe_152_M_24S99554.git

# Ajoute tous les fichiers
git add .

# Fais un commit
git commit -m "Premier envoi de mon projet TPE"

# Envoie vers GitHub (branche main)
git branch -M main
git push -u origin main
