# API Food Searcher

Application web de recherche de recettes, développée en HTML / CSS / JavaScript vanilla, connectée à l'API publique [TheMealDB](https://www.themealdb.com/api.php).

*A recipe search web app built with vanilla HTML / CSS / JavaScript, powered by the public [TheMealDB](https://www.themealdb.com/api.php) API.*

---

## Aperçu / Overview

À partir d'un nom de plat, l'application affiche en temps réel une photo, la liste des ingrédients avec leurs quantités, les instructions de préparation, la catégorie et l'origine du plat, ainsi qu'un lien YouTube vers la recette.

*Type in a dish name and the app instantly shows a photo, full ingredient list with measurements, step-by-step instructions, the dish category and origin, and a YouTube link.*

---

## Stack technique / Tech Stack

| Technologie | Rôle / Role |
|---|---|
| HTML5 | Structure de l'interface / UI structure |
| CSS3 | Mise en page & responsive / Layout & responsive |
| JavaScript ES6+ | Logique & appels API / Logic & API calls |
| [TheMealDB API](https://www.themealdb.com/api.php) | Source de données / Data source |
| Google Fonts | Poppins, Space Mono, Unbounded… |

---

## Structure du projet / Project Structure

```
api-food-searcher/
├── index.html      # Point d'entrée / Entry point
├── styles.css      # Feuille de styles / Stylesheet
└── app.js          # Logique JavaScript & appels API / JS logic & API calls
```

---

## Installation & lancement / Getting Started

Aucune dépendance ni serveur requis — le projet s'ouvre directement dans le navigateur.

*No dependencies or server needed — open it straight in the browser.*

```bash
# Cloner le dépôt / Clone the repository
git clone https://github.com/votre-username/api-food-searcher.git

# Ouvrir dans le navigateur / Open in the browser
open index.html
```

Pour éviter d'éventuels problèmes CORS en développement, utilise un serveur local via l'extension **Live Server** (VS Code) ou :

*To avoid potential CORS issues in development, run a local server with the **Live Server** VS Code extension or:*

```bash
npx serve .
```

---

## Utilisation de l'API / API Usage

```
GET https://www.themealdb.com/api/json/v1/1/search.php?s={nom_du_plat}
```

La réponse JSON contient le nom, la photo, la catégorie, l'origine, les ingrédients (jusqu'à 20) avec leurs quantités, les instructions et le lien YouTube.

*The JSON response includes the name, photo, category, origin, up to 20 ingredients with measurements, cooking instructions, and a YouTube link.*

---

## Exemples / Demo

| Recherche / Search | Résultat / Result |
|---|---|
| `arrabiata` | Penne Arrabiata — Pasta / Italian |
| `sushi` | Sushi — Japanese |
| `chicken` | Chicken Handi — Indian |

---

## Auteur / Author

**Eden G** — Développeur Web & Mobile Full Stack

[GitHub](https://github.com/eguediche) · [Portfolio](https://eguediche.github.io) · [LinkedIn](https://linkedin.com/in/eguediche)
