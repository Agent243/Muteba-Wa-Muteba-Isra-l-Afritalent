#  AfriTalent - Plateforme de Freelances Tech en Afrique

**Projet Semestre 2 - Groupe ISI** 
***Classe: L1CS***
**Auteur :** Agent23  
**Date :** Mars 2026  

-----------------------------------------------------------------------------------------------------------------------------------

##  Description du Projet

**AfriTalent** est une plateforme fictive de mise en relation entre **freelances tech africains** et **entreprises**.  
Ce site vitrine complet présente la plateforme, ses fonctionnalités, ses tarifs, des profils de freelances et convainc les visiteurs (freelances ET entreprises) de s’inscrire.

Le projet respecte **toutes les exigences du sujet** :
- Design épuré et moderne (tendances 2026)
- Bento Grid
- Accessibilité
- Dark/Light Mode persistant
- Interactivité JavaScript vanilla
- Responsive 100%

-----------------------------------------------------------------------------------------------------------------------------------

##  Technologies Utilisées

| Technologie            | Utilisation                                      |
|------------------------|--------------------------------------------------|
| **HTML5**              | Structure sémantique rigoureuse                  |
| **CSS3**               | Variables, Flexbox, Grid, Bento Grid, animations |
| **Bootstrap 5**        | Navbar, Cards, Carousel, Accordion, Modal        |
| **JavaScript Vanilla** | Toutes les interactions (sans framework)         |
| **Google Fonts**       | `Inter` + `Space Grotesk`                        |
| **Bootstrap Icons**    | Toutes les icônes                                |
| **Git & GitHub**       | Versioning + GitHub Pages                        |

-----------------------------------------------------------------------------------------------------------------------------------

##  Fonctionnalités Principales

-  Navbar fixe et dynamique (changement au scroll)
-  **Dark/Light Mode** persistant (`localStorage`)
-  Compteurs animés au scroll (`IntersectionObserver`)
-  Filtrage dynamique des freelances (sans rechargement)
-  Validation complète du formulaire de contact
-  Bento Grid sur "Comment ça marche" et "Chiffres clés"
-  Carousel témoignages + Accordion FAQ
-  Bouton "Retour en haut" avec smooth scroll
-  Animations fade-in au scroll
-  Responsive parfait (mobile 375px → desktop)

---

##  Documentation Détaillée du Code

### 1. HTML5 – Structure Sémantique
- `<!DOCTYPE html>` → Déclare le document HTML5
- `<html lang="fr">` → Accessibilité et SEO
- Balises sémantiques (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) → Hiérarchie logique
- Attributs `alt` sur toutes les images → Accessibilité

### 2. CSS3 – Mise en Page Avancée
- **Variables CSS** (`:root`) → Minimum 6 variables pour cohérence
- **Bento Grid** → `display: grid` + `grid-template-areas` pour disposition asymétrique
- **Dark Mode** → Classe `.dark-mode` qui surcharge toutes les couleurs
- **Hover effects** → `transform`, `box-shadow` et `transition`
- **Responsive** → Media queries + classes Bootstrap

### 3. JavaScript Vanilla (`main.js`)
- **Dark Mode** → `localStorage` + bascule de classe sur `<html>`
- **Navbar dynamique** → Écoute du `scroll` + classe `.scrolled`
- **Compteurs animés** → `IntersectionObserver` + `setInterval`
- **Filtrage freelances** → `data-category` + affichage/masquage dynamique
- **Validation formulaire** → Regex email + vérification longueur + messages d’erreur
- **Bouton retour en haut** → Apparition conditionnelle + `scrollTo` smooth
- **Fade-in au scroll** → `IntersectionObserver`
---------------------------------------------------------------------------------------------------------------------------------
 
 
 #### Made By AGENT23 ####

##  Instructions pour Lancer le Projet

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/Agent23/Muteba-Wa-Muteba-Isra-l-AfriTalent.git
