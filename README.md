# 🌐 MaaSify Gateway — Prototype Front-End

## 🧭 Présentation

**MaaSify Gateway** est une plateforme destinée à faciliter l’ouverture des **Systèmes Numériques de Vente (SNV)** aux **Fournisseurs de Services Numériques Multimodaux (FSNM)**, conformément aux exigences de la **Loi d’Orientation des Mobilités (LOM)** et à la future doctrine de l’**Autorité de Régulation des Transports (ART)**.

Ce dépôt contient un **prototype front-end** (HTML / CSS / JS) illustrant les interfaces principales de la solution :

- Interface **AOM / Exploitant**
- Interface **FSNM**
- Interface **Éditeur billettique**

L’objectif du prototype est de **démontrer l’expérience utilisateur** et de **produire des captures** pour les supports de présentation (RNTP, investisseurs, partenaires industriels).

---

## 🧱 Structure du dépôt

maasify-prototype-ui/
├─ index.html # Page d’accueil — sélection du rôle utilisateur
├─ aom.html # Interface AOM / exploitant
├─ fsnm.html # Interface Fournisseur de Services Numériques Multimodal
├─ editor.html # Interface Éditeur billettique
├─ assets/
│ ├─ css/tailwind.css # Fichier CSS principal (chargé via CDN)
│ ├─ js/dashboard.js # Scripts communs (interactions, graphiques)
│ └─ img/ # Ressources visuelles et icônes
└─ README.md # Ce document

---

## ⚙️ Technologies utilisées

Ce prototype est 100 % statique et ne requiert **aucune installation serveur**.  
Toutes les dépendances sont chargées via CDN.

| Composant | Usage principal | Source CDN |
|------------|------------------|-------------|
| **TailwindCSS** | Mise en page et style responsive | [https://cdn.tailwindcss.com](https://cdn.tailwindcss.com) |
| **Chart.js** | Graphiques et visualisations | [https://cdn.jsdelivr.net/npm/chart.js](https://cdn.jsdelivr.net/npm/chart.js) |
| **Material Symbols (Google Fonts)** | Icônes cohérentes et légères | [https://fonts.google.com/icons](https://fonts.google.com/icons) |
| **Alpine.js** *(optionnel)* | Interactions simples (onglets, menus) | [https://cdn.jsdelivr.net/npm/alpinejs](https://cdn.jsdelivr.net/npm/alpinejs) |

---

## 🚀 Utilisation

### 1. Cloner le dépôt
```bash
git clone https://github.com/<ton-organisation>/maasify-prototype-ui.git
cd maasify-prototype-ui
