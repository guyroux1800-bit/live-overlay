# Live Meme Overlay 🎉

Petit outil pour afficher des memes/images/vidéos envoyés par tes amis en live dans OBS.

---

## ⚡ Installation

1. Télécharge ou clone ce dossier.
2. Va sur [Firebase Console](https://console.firebase.google.com) et crée un projet.
3. Active la **Realtime Database** en mode test.
4. Copie les infos de config Firebase dans `overlay.html` et `sender.html`.
5. Dans OBS, ajoute une **Source Navigateur** et sélectionne `overlay.html` (local file).
6. Ouvre `sender.html` dans ton navigateur et partage-le à tes amis → ils collent des liens (images/GIF/vidéos).
7. Les memes apparaissent instantanément dans ton stream Discord 🎉

---

## 🚀 Hébergement

- Local : double-clique simplement sur `sender.html` et `overlay.html`.
- Web : mets les fichiers sur **GitHub Pages**, **Netlify** ou **Vercel** pour que tes amis y accèdent facilement.
