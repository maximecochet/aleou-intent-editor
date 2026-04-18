# Aleou Intent Editor

Éditeur visuel pour les fichiers JSON d'intentions du pipeline email Aleou.

🔗 **Accès à l'éditeur** : [maximecochet.github.io/aleou-intent-editor](https://maximecochet.github.io/aleou-intent-editor/)

---

## Comment mettre à jour la page

### Prérequis
- Avoir accès au repo GitHub `maximecochet/aleou-intent-editor`
- Avoir [Git](https://git-scm.com/) installé, ou utiliser l'interface GitHub directement

---

### Option A — Via l'interface GitHub (sans Git)

1. Ouvre le repo : [github.com/maximecochet/aleou-intent-editor](https://github.com/maximecochet/aleou-intent-editor)
2. Clique sur le fichier `index.html`
3. Clique sur l'icône **crayon** (Edit this file) en haut à droite
4. Fais tes modifications
5. En bas, clique sur **Commit changes**
6. La page se met à jour automatiquement dans 1-2 minutes

---

### Option B — Via Git en ligne de commande

```bash
# 1. Cloner le repo (une seule fois)
git clone https://github.com/maximecochet/aleou-intent-editor.git
cd aleou-intent-editor

# 2. Modifier le fichier index.html avec ton éditeur
open index.html  # ou code index.html, etc.

# 3. Envoyer les modifications
git add index.html
git commit -m "Update: description de ta modification"
git push
```

La page GitHub Pages se met à jour automatiquement après le push (1-2 minutes).

---

## Structure du repo

```
aleou-intent-editor/
├── index.html    # L'éditeur complet (application self-contained)
└── README.md     # Ce fichier
```

Tout le code (HTML + CSS + JS) est dans un seul fichier `index.html`. Il n'y a pas de dépendances externes, pas de build step.

---

## Vérifier le statut du déploiement

Dans le repo GitHub → onglet **Actions** → le workflow "pages build and deployment" doit être vert ✅.

Si la page n'est pas à jour après 5 minutes, aller dans **Settings → Pages** et vérifier que la source est bien `main / (root)`.
