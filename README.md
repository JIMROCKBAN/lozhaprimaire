# Lozhaprimaire - Théâtre du Petit Miroir

## Instructions pour héberger les images sur GitHub

### Étape 1 : Préparer les images
Placez vos images dans ce dossier. L'image principale devrait être nommée :
- `lozhaetledragon300dpi3.jpg`

### Étape 2 : Initialiser et pousser vers GitHub

```bash
# Initialiser le repo Git (si ce n'est pas déjà fait)
git init

# Ajouter le remote GitHub
git remote add origin git@github.com:JIMROCKBAN/lozhaprimaire.git

# Ajouter tous les fichiers
git add .

# Créer le commit
git commit -m "Ajout du fichier HTML et des images"

# Pousser vers GitHub (branche main)
git branch -M main
git push -u origin main
```

### Étape 3 : Accéder aux images
Une fois les images uploadées sur GitHub, elles seront accessibles via l'URL :
```
https://raw.githubusercontent.com/JIMROCKBAN/lozhaprimaire/main/NOMDELIMAGE.jpg
```

Cette URL est déjà utilisée dans le fichier HTML pour l'image principale.

## Modifications apportées au fichier HTML

✅ **Prix augmenté à 750 euros**
✅ **Balises Mautic ajoutées** : `{webview_url}`, `{unsubscribe_url}`, `{tracking_pixel}`
✅ **Texte modifié** : "Nous venons dans votre ecole" (au lieu de "Dans votre école")
✅ **Code restructuré** : Clean, moderne et responsive
✅ **Responsive** : Adapté pour Web, Desktop, Mobile (avec media queries)
✅ **Images hébergées** : URL GitHub configurée

## Structure du code

Le nouveau fichier HTML utilise :
- CSS moderne avec Flexbox/Box Model
- Media queries pour le responsive design
- Structure sémantique claire
- Optimisation pour tous les appareils (mobile, tablette, desktop)

## Fichiers

- `lozhaprimaire.html` - Fichier principal (nouvelle version)
- `lozhaprimaire_old.html` - Ancienne version (backup)
- `README.md` - Ce fichier
