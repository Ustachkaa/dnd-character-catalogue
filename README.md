# Dungeons & Dragons Character Cards Catalogue

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Features](#features)  
3. [Project Structure](#project-structure)  
4. [How to Use](#how-to-use)  
5. [Customization](#customization)  
6. [Technologies Used](#technologies-used)  
7. [Credits](#credits)  

---

## Project Overview
This project is a **Dungeons & Dragons character catalogue** featuring 9 character classes. Users can:

- View character cards in a **3x3 grid layout**  
- Flip cards to see detailed stats and descriptions  
- Use a **fixed “Return” button** to flip the card back  

The project is fully built with **HTML, CSS, and JavaScript**, featuring 3D card flips and a visually immersive fantasy theme.

---

## Features
- **Interactive flip cards**: Click "See Details" to view character stats  
- **Fixed-position buttons**: “See Details” and “Return” buttons stay in the same spot  
- **Unique character images** for each class  
- **Modern dark theme** with gradient backgrounds and subtle shadows  
- **Responsive grid layout**: 3x3 card arrangement  

---

## Project Structure
```
D&D-Character-Cards/
│
├─ index.html # Landing page
├─ catalogue.html # Character catalogue page
├─ css/
│ └─ cards.css # Styles for catalogue and cards
├─ js/
│ ├─ landing.js # Landing page script
│ └─ cards.js # Card flip script
└─ assets/
└─ images/ # Character images
```

---

## How to Use
1. Open `index.html` in a web browser.  
2. Click anywhere on the landing page to navigate to `catalogue.html`.  
3. Click **See Details** on a character card to flip it and view stats.  
4. Click **Return** to flip the card back to the front.  

**Note:** Works on desktop and mobile devices with smooth flip animations.

---

## Customization
- **Add new characters**:  
  1. Add a new card in `catalogue.html` following the existing card structure  
  2. Add the character image in `assets/images/`  
  3. Add a CSS class for the character image in `cards.css`  

- **Change styling**:  
  - Modify gradients, shadows, fonts, and card sizes in `cards.css`  
  - Button colors and positions are easily adjustable  

- **Edit stats or descriptions**:  
  Update the content inside `.back .inner` for each card in `catalogue.html`

---

## Technologies Used
- HTML5  
- CSS3 (Flexbox, Grid, 3D transforms)  
- JavaScript (Vanilla JS for flip interactions)  
- Google Fonts ([Cinzel](https://fonts.google.com/specimen/Cinzel))  
- Font Awesome ([https://fontawesome.com/](https://fontawesome.com/))  

---

## Credits
- Character images sourced from [Cosmos](https://www.cosmos.so)
- Font: [Cinzel](https://fonts.google.com/specimen/Cinzel)  
- Icons: [Font Awesome](https://fontawesome.com/)  

---

## Optional Enhancements
- Add hover glow or animation effects on cards and buttons  
- Add more responsive mobile-friendly design features  
- Animate stats or descriptions for extra interactivity  
