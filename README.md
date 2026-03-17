# CyberAcademy PWA 🔐

Application mobile d'apprentissage quotidien en cybersécurité (Pentest, IAM, GRC, Système).

---

## 🚀 Déploiement en 5 minutes (GitHub Pages - GRATUIT)

### Étape 1 — Créer un compte GitHub
Rendez-vous sur https://github.com et créez un compte gratuit.

### Étape 2 — Créer un nouveau repository
1. Cliquez sur **"New"** (bouton vert)
2. Nommez-le : `cyberacademy`
3. Cochez **"Public"**
4. Cliquez **"Create repository"**

### Étape 3 — Uploader les fichiers
1. Cliquez sur **"uploading an existing file"**
2. Glissez-déposez TOUS les fichiers (index.html, manifest.json, sw.js, et le dossier icons/)
3. Cliquez **"Commit changes"**

### Étape 4 — Activer GitHub Pages
1. Allez dans **Settings** du repository
2. Menu gauche → **Pages**
3. Source → **"Deploy from a branch"**
4. Branch → **main** → **/(root)**
5. Cliquez **Save**

### Étape 5 — Votre app est en ligne !
Votre URL sera : `https://VOTRE-USERNAME.github.io/cyberacademy`

---

## 📲 Installation sur iPhone

1. Ouvrez l'URL dans **Safari** (obligatoire sur iPhone)
2. Appuyez sur le bouton **Partager** (carré avec flèche)
3. Faites défiler vers le bas → **"Sur l'écran d'accueil"**
4. Appuyez **Ajouter**

L'icône CyberAcademy apparaîtra sur votre écran d'accueil !

## 📲 Installation sur Android

1. Ouvrez l'URL dans **Chrome**
2. Une bannière "Installer l'app" apparaît automatiquement
3. Appuyez **Installer** — ou menu (3 points) → "Ajouter à l'écran d'accueil"

---

## Alternative : Netlify (encore plus simple)

1. Allez sur https://netlify.com → compte gratuit
2. Glissez le dossier cyberacademy-pwa directement sur la page
3. Votre app est déployée instantanément avec une URL publique !

---

## Fonctionnalités

- 🔐 Notions quotidiennes générées par IA (Claude Sonnet)
- 🎯 4 domaines : Pentest, IAM, GRC, Système
- 🧠 Quiz interactif pour chaque notion
- 🔥 Streak de jours consécutifs
- 📊 Statistiques de progression
- 🔔 Rappels quotidiens (matin + soir)
- 💾 Sauvegarde locale (fonctionne hors-ligne)
- 📲 Installable sur iOS et Android

---

## Structure des fichiers

```
cyberacademy-pwa/
├── index.html      → Application principale
├── manifest.json   → Configuration PWA
├── sw.js           → Service Worker (offline + notifications)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```
