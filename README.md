# Portfolio – Adrien Stiévenart (AS)

> **Portfolio personnel** présentant mes projets et compétences en développement web. Design dark, dégradés lumineux, animations fluides et mise en avant des stacks techniques principales : **HTML, CSS, JavaScript, Vue3, Django, React Native, .NET**.

---

## 🚀 Aperçu

Ce portfolio a pour objectif de présenter mes projets phares et de servir de vitrine professionnelle pour trouver des missions freelance.

**Lien de démo (à venir)** : `https://adrienstievenart.github.io/`

### Aperçu visuel

![Preview du portfolio](./assets/preview.jpg)

Le design mise sur :
- Un **thème dark moderne** avec dégradés violets et turquoises.
- Des **blobs lumineux animés** en fond pour un effet fluide.
- Des **cartes de projets dynamiques** avec effet hover et ouverture en modal.
- Une **section contact** simplifiée (formulaire avec fallback mailto).

---

## 🛠️ Technologies utilisées

| Catégorie | Outils & Frameworks |
|------------|----------------------|
| **Front-end** | HTML5, CSS3 (animations, gradients, glassmorphism), JavaScript (vanilla) |
| **Frameworks** | Vue3, Django, React Native, .NET (selon projets présentés) |
| **Outils** | VSCode / IntelliJ IDEA, GitHub Pages pour le déploiement |

---

## 🧩 Structure du projet

```
📁 portfolio-as/
│
├── index.html          # Fichier principal (le portfolio complet)
├── assets/
│   ├── img/            # Captures des projets
│   └── preview.jpg     # Image d’aperçu (optionnelle)
└── README.md           # Ce fichier
```

---

## 🧠 Sections du site

### 🏠 Hero
Présentation rapide, compétences techniques (HTML, CSS, JS, Vue3, Django, React Native, .NET), et lien vers contact ou projets.

### 💼 Projets
Liste de projets avec cartes interactives :
- **Nicole Nisol** — Site d’auteure locale (Vue3 / .NET / Stripe)
- **JustGaming** — Réseau social pour gamers (Django)
- **Chronocraft** — App mobile d’entraînement (React Native / .NET)
- **Projet Mystère** — Concept confidentiel, captures partielles.

### 📬 Contact
Formulaire simple (mailto fallback) + liens directs.

---

## ⚙️ Installation & lancement local

1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/adrienstievenart/portfolio-as.git
   cd portfolio-as
   ```

2. **Ouvrir localement** :
   ```bash
   # Sous VSCode ou tout éditeur
   # Ouvrir index.html dans le navigateur
   ```

3. (Optionnel) **Lancer un serveur local** :
   ```bash
   npx serve .
   ```
   Le site sera accessible sur `http://localhost:3000`

---

## 🌐 Déploiement

Déploiement rapide sur GitHub Pages :

```bash
git add .
git commit -m "Initial commit"
git push origin main
gh pages publish . --branch main --dist .
```

---

## 💡 Personnalisation

- Modifier les **couleurs d’accentuation** (violet / turquoise) dans le bloc `:root` du CSS.
- Remplacer les **placeholders SVG** des projets par des images réelles dans `/assets/img/`.
- Mettre à jour les **liens LinkedIn / email** dans la section contact.
- (Optionnel) Ajouter des **témoignages** ou un **CV téléchargeable**.

---

## 🧾 Licence

Projet open-source, librement réutilisable à des fins personnelles ou de démonstration.

---

👨‍💻 **Auteur : Adrien Stiévenart**  
📍 Basé en **Wallonie**  
💬 Contact : [adrien@example.com](mailto:adrien@example.com)
