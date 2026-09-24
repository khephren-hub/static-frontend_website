# Frontend — Vitrine Web Minimaliste

Site web statique responsive, conçu exclusivement en HTML5 et CSS3 pur (aucun framework, aucun script JavaScript).  
La direction artistique s'inspire du design épuré, typographique et fonctionnel de la marque Patagonia (palette terreuse, contrastes marqués, structure sobre).

---

## Arborescence du projet

```text
.
├── adress.html
├── authentification.html
├── cart.html
├── index.html
├── login.html
├── payment.html
├── register.html
├── validation.html
└── assets/
    ├── adress.css
    ├── authentification.css
    ├── cart.css
    ├── payment.css
    ├── styles.css
    └── validation.css

# Consultation locale & méthode de lancement

## Option 1 — Lancement direct

Ouvrez simplement le fichier `index.html` dans le navigateur web de votre choix (double-clic ou glisser-déposer).

## Option 2 — Serveur local (recommandé)

Pour tester le site dans des conditions proches d'un hébergement réel, lancez un serveur HTTP léger depuis la racine du dossier :

### Avec Python 3

```bash
python -m http.server 8000

http://localhost:8000
