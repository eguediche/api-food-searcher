# 🍽️ API Food Searcher

> Application web de recherche de recettes de cuisine, développée en HTML / CSS / JavaScript vanilla, utilisant l'API publique [TheMealDB](https://www.themealdb.com/api.php).

---

## 🧭 Aperçu

**API Food Searcher** permet de rechercher n'importe quel plat du monde entier et d'afficher en temps réel :

- 📸 Une photo du plat
- 🧂 La liste complète des ingrédients avec leurs quantités
- 📋 Les instructions de préparation étape par étape
- 🏷️ La catégorie et l'origine géographique du plat
- 🎥 Un lien vers une vidéo YouTube de la recette

---

## 🛠️ Stack technique

| Technologie | Rôle |
|---|---|
| HTML5 | Structure sémantique de l'interface |
| CSS3 | Mise en page, design et responsive |
| JavaScript (ES6+) | Logique applicative, appels API asynchrones |
| [TheMealDB API](https://www.themealdb.com/api.php) | Source de données des recettes |
| Google Fonts | Typographies (Poppins, Space Mono, Unbounded…) |

---

## ✨ Fonctionnalités

- 🔍 **Recherche en temps réel** — saisie d'un nom de plat, résultat instantané via fetch API
- 📦 **Affichage structuré** — ingrédients en tableau, instructions en liste ordonnée
- 🌍 **Base de données internationale** — milliers de recettes issues de cuisines du monde entier
- 📱 **Interface responsive** — adaptée mobile et desktop
- 🔗 **Lien YouTube intégré** — pour suivre la recette en vidéo

---

## 📁 Structure du projet

```
api-food-searcher/
├── index.html      # Point d'entrée de l'application
├── styles.css      # Feuille de styles complète
└── app.js          # Logique JavaScript & appels API
```

---

## 🚀 Installation & lancement

Aucune dépendance ni serveur requis. Le projet fonctionne directement dans le navigateur.

```bash
# 1. Cloner le dépôt
git clone https://github.com/votre-username/api-food-searcher.git

# 2. Ouvrir le fichier dans un navigateur
open index.html
```

> **Conseil :** Pour éviter d'éventuels problèmes CORS en développement, lancez un serveur local avec l'extension **Live Server** (VS Code) ou via :
> ```bash
> npx serve .
> ```

---

## 🔌 Utilisation de l'API

Le projet consomme l'API publique et gratuite **TheMealDB** :

```
GET https://www.themealdb.com/api/json/v1/1/search.php?s={nom_du_plat}
```

La réponse JSON contient le nom, la photo, la catégorie, l'origine, les ingrédients (jusqu'à 20), les instructions et le lien YouTube de la recette.

---

## 📸 Démonstration

| Recherche | Résultat affiché |
|---|---|
| `arrabiata` | Penne Arrabiata — Pasta / Italian |
| `sushi` | Sushi — Japanese |
| `chicken` | Chicken Handi — Indian |
