# 🔮 L'Oracle — Quiz de Prédiction Mystique

Un quiz interactif et visuellement immersif qui génère des prédictions personnalisées basées sur les réponses des utilisateurs.

## 🚀 Héberger sur GitHub Pages (3 étapes)

### 1. Créer un repo GitHub
- Va sur [github.com](https://github.com) → **New repository**
- Nomme-le `oracle-quiz` (ou ce que tu veux)
- Laisse-le **Public**
- Clique **Create repository**

### 2. Upload le fichier
- Dans ton repo, clique **Add file → Upload files**
- Glisse-dépose le fichier `index.html`
- Clique **Commit changes**

### 3. Activer GitHub Pages
- Va dans **Settings → Pages**
- Source : **Deploy from a branch**
- Branch : `main` / `root`
- Clique **Save**

✅ Ton site sera disponible à : `https://TON-USERNAME.github.io/oracle-quiz`

---

## 📊 Collecte de données

Les réponses sont sauvegardées dans le **localStorage** du navigateur de chaque visiteur.

**Pour récupérer les données :**
- En bas de la page résultat, clique sur **"◆ Archives de l'Oracle"**
- Clique **"⬇ Exporter CSV"** pour télécharger toutes les réponses

**Données collectées :**
- Date, prénom, email (optionnel)
- Profil obtenu
- Réponse à chacune des 7 questions

> 💡 **Note :** localStorage est par navigateur. Pour une collecte centralisée multi-utilisateurs, il faudra connecter une base de données (Supabase, Firebase, etc.). Je peux t'aider à configurer ça si tu le souhaites.

---

## ✨ Fonctionnalités

- 7 questions · 28 profils de prédiction uniques
- Canvas animé : constellation de particules, nébuleuses, étoiles filantes
- Curseur personnalisé
- Orbe cristalline animée
- Bagues orbitales tournantes
- Progression dorée animée
- Typographie premium (Cinzel Decorative + Cormorant Garamond)
- Formulaire de collecte email intégré
- Export CSV des réponses
