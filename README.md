[README-DIGIY-SOLAIRE.md](https://github.com/user-attachments/files/28573526/README-DIGIY-SOLAIRE.md)[Uploading README-DIGIY-SOLAIRE.md…# ☀️ DIGIY SOLAIRE — Installation & dépannage

Fiche publique autonome pour présenter un service solaire local : installation, dépannage, entretien, diagnostic et conseil énergie.

Cette fiche est pensée pour un dépôt GitHub Pages simple : un seul fichier `index.html`, partageable par lien, WhatsApp ou QR.

---

## 🌍 Vision

**DIGIY SOLAIRE** aide un professionnel du terrain à être visible, joignable et crédible sans passer par une plateforme à commission.

Le client arrive sur une fiche claire, comprend les services, contacte directement le professionnel et garde une relation humaine.

> Contact direct · Paiement direct · 0% commission

---

## 🧰 Services présentés

- ☀️ Installation solaire
- 🔧 Dépannage solaire
- 🧽 Entretien & contrôle
- 💡 Conseil énergie
- 🏠 Maison, boutique, chambre, atelier, chantier ou petit commerce

---

## 📁 Structure du dépôt

```txt
DIGIY-SOLAIRE/
└── index.html
```

Le dépôt fonctionne avec un seul fichier principal :

```txt
index.html
```

---

## 🚀 Mise en ligne avec GitHub Pages

1. Créer un dépôt GitHub, par exemple :

```txt
DIGIY-SOLAIRE
```

2. Ajouter le fichier :

```txt
index.html
```

3. Aller dans :

```txt
Settings → Pages
```

4. Choisir :

```txt
Deploy from branch
Branch: main
Folder: /root
```

5. Attendre quelques instants, puis ouvrir l’URL GitHub Pages.

---

## ✏️ Modifier les informations du professionnel

Dans `index.html`, cherche le bloc :

```js
const BUSINESS_NAME = "DIGIY SOLAIRE";
const PHONE_DISPLAY = "+221 77 134 28 89";
const PHONE_DIGITS = "221771342889";
const WHATSAPP_TEXT = "Bonjour, je souhaite un renseignement pour une installation ou un dépannage solaire.";
const ZONE = "Sénégal · Saly · Dakar · Petite-Côte";
```

Tu peux modifier :

```txt
BUSINESS_NAME   → nom affiché
PHONE_DISPLAY   → numéro visible
PHONE_DIGITS    → numéro WhatsApp sans + ni espace
WHATSAPP_TEXT   → message WhatsApp prêt
ZONE            → zone d’intervention
```

---

## 🖼️ Modifier la photo principale

La photo principale est dans la balise :

```html
<img
  class="heroPhoto"
  src="https://images.unsplash.com/photo-1508514177221-188b1cf16e9d?auto=format&fit=crop&w=1400&q=80"
  alt="Panneaux solaires installés sous le soleil"
/>
```

Remplace simplement l’URL `src` par une autre image.

Conseil DIGIY : utiliser une image claire, lumineuse, solaire, avec panneaux, toit, terrain ou installation réelle.

---

## 🔳 QR intégré

La fiche génère automatiquement un QR vers l’adresse publique de la page.

Le QR permet de partager la fiche sur :

- affiche
- sticker
- WhatsApp
- vitrine
- chantier
- carte de visite
- groupe local

---

## 📱 Mobile-first

La fiche est pensée pour téléphone :

- gros boutons
- lecture claire
- WhatsApp visible
- appel direct
- QR intégré
- peu de scroll inutile
- message simple pour le client

---

## 🦅 Doctrine DIGIY

DIGIY ne remplace pas le professionnel.

DIGIY lui donne des bras numériques :

- une présence claire
- un lien partageable
- un QR
- un contact direct
- une fiche digne
- une relation client protégée

Le professionnel garde :

```txt
son nom
son client
son argent
sa relation
```

---

## ✅ Résultat attendu

Une fois publié, le dépôt donne une fiche publique du type :

```txt
https://USERNAME.github.io/DIGIY-SOLAIRE/
```

Cette fiche peut être envoyée directement aux clients ou imprimée via QR.

---

## DIGIYLYFE

Architecture économique du terrain.

**Wave a mis l’argent dans la main.  
DIGIY met l’organisation du business dans la main.**
]()
