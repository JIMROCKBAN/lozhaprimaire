# Instructions pour finaliser le projet

## ✅ Ce qui a été fait

1. ✅ **Prix augmenté à 750 euros**
2. ✅ **Balises Mautic ajoutées** : 
   - `{webview_url}` pour la version web
   - `{unsubscribe_url}` pour se désinscrire
   - `{tracking_pixel}` pour le suivi
3. ✅ **Texte modifié** : "Nous venons dans votre ecole"
4. ✅ **Code restructuré** : Clean, moderne et responsive
5. ✅ **Responsive design** : Mobile, tablette, desktop
6. ✅ **Git initialisé** et configuré
7. ✅ **URL d'image GitHub** : Configurée pour pointer vers le repo

## 📋 Prochaines étapes

### 1. Uploader l'image principale sur GitHub

Vous devez d'abord placer votre image dans le dossier :
```bash
# Téléchargez votre image "lozhaetledragon300dpi3.jpg" dans ce dossier
# puis :
git add lozhaetledragon300dpi3.jpg
git commit -m "Ajout de l'image principale"
```

### 2. Pousser vers GitHub

Une fois l'image ajoutée :
```bash
git push -u origin main
```

**Note** : Vous aurez besoin d'avoir configuré votre clé SSH GitHub ou d'utiliser HTTPS avec vos identifiants.

### 3. Alternative HTTPS

Si vous préférez utiliser HTTPS au lieu de SSH :
```bash
git remote remove origin
git remote add origin https://github.com/JIMROCKBAN/lozhaprimaire.git
git push -u origin main
```

### 4. Vérifier l'image

Après le push, votre image sera accessible à :
```
https://raw.githubusercontent.com/JIMROCKBAN/lozhaprimaire/main/lozhaetledragon300dpi3.jpg
```

Cette URL est déjà utilisée dans le fichier HTML !

## 🎨 Caractéristiques du nouveau code HTML

- **Structure propre** : Code bien organisé et facile à maintenir
- **CSS moderne** : Utilisation de variables, flexbox, grid
- **Responsive** : S'adapte automatiquement à tous les écrans
- **Media queries** :
  - Mobile : < 619px
  - Tablette/Desktop : ≥ 620px
- **Optimisé** : Chargement rapide et performances optimales
- **Accessible** : Balises sémantiques et bonne structure

## 📱 Tests recommandés

Testez le fichier HTML sur :
- ✅ Mobile (< 620px)
- ✅ Tablette (620px - 1024px)
- ✅ Desktop (> 1024px)

## 🔧 Configuration Mautic

Les balises Mautic utilisées :
- `{webview_url}` - URL de la version web
- `{unsubscribe_url}` - Lien de désinscription
- `{tracking_pixel}` - Pixel de tracking

Mautic remplacera automatiquement ces balises lors de l'envoi.

## 📁 Fichiers du projet

- `lozhaprimaire.html` - **Fichier principal à utiliser**
- `README.md` - Documentation
- `.gitignore` - Fichiers ignorés par Git
- `lozhaprimaire_old.html` - Backup de l'ancienne version
- `INSTRUCTIONS.md` - Ce fichier

---

**Besoin d'aide ?** Contactez-moi pour toute question !
