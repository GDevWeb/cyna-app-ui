# Cyna – Frontend e-commerce (React)

Projet vitrine développé dans le cadre d’un projet académique fil rouge (Bachelor Développeur Informatique et Coordinateur de Projet, 2024).  
**Stack : React + Redux Toolkit + Tailwind CSS**

> Ce dépôt contient uniquement la partie **frontend** (React).  
> Les fonctionnalités dynamiques (auth, paiement, profils, panier) sont désactivées par absence d’API.  
> Le rendu est donc partiel, mais fidèle au design initial et aux exigences du cahier des charges.

---

## Fonctionnalités clés

- Intégration UI complète (home, catégories, produits, recherche)
- Moteur de recherche avec filtres et tri (mock fallback si API absente)
- Architecture modulaire et scalable (Redux Toolkit, composants réutilisables)
- Responsive et accessible (navigation clavier, roles ARIA, messages dynamiques)
- Comportement hybride : fallback automatique en cas d’erreur backend

---

## Aperçu

| HomePage                    | Page produit               | Recherche                 |
| --------------------------- | -------------------------- | ------------------------- |
| ![](./screens/homepage.png) | ![](./screens/product.png) | ![](./screens/search.png) |

---

## Pages couvertes

| Page              | Description                                            |
| ----------------- | ------------------------------------------------------ |
| `/`               | Accueil (hero + catégories + produits phares)          |
| `/categories/:id` | Affichage dynamique des produits liés à une catégorie  |
| `/products`       | Liste paginée de tous les produits                     |
| `/products/:id`   | Détail complet du produit (infos, specs, galerie, CTA) |
| `/search`         | Page de recherche avancée avec filtres et tri          |

---

## Limitations techniques

- Authentification désactivée (pas d'accès aux routes privées)
- Panier et paiement Stripe inactifs
- Backend non connecté (fallback mock ou erreur affichée proprement)

---

## Installation

```bash
git clone https://github.com/votre-nom/cyna-frontend.git
cd cyna-frontend
npm install
npm start
```

---

## Pour les recruteurs

Ce projet démontre mes compétences en :

- Conception d’UI e-commerce accessibles et modernes
- Gestion des états complexes avec Redux Toolkit
- Mise en place de fallback robustes et debuggables
- Intégration modulaire et clean code orienté composants
- Travail en autonomie dans un contexte semi-professionnel

---

## Contact

- GitHub : [GDevWeb](https://github.com/GDevWeb)
- LinkedIn : [Gaëtan Dammaretz](https://www.linkedin.com/in/ga%C3%ABtan-dammaretz/)
- Email : gaetan.dammaretz.dev@gmail.com
# cyna-app-ui
