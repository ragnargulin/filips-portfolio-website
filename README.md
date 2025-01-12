Grattis på 30-årsdagen Filip!


# Filip Mellgren Portfolio

Det här är en personlig portfolio-webbplats skapad för Filip Mellgren, en doktorand i ekonomi. Hemsidan är byggd med HTML, CSS och lite JavaScript för att skapa en enkel och responsiv design. Här hittar du information om hur koden fungerar och hur du kan uppdatera eller bygga vidare på den.

---

## 🎯 **Vad gör hemsidan?**
Den här hemsidan presenterar information om Filip:
- **About Me**: Kort beskrivning av Filip och hans arbete.
- **Research**: En översikt av forskningsområden.
- **CV**: En nedladdningsbar version av CV:t.
- **Contact**: Kontaktinformation och länkar till sociala medier.

---

## 🛠 **Hur koden fungerar**

### **HTML (Struktur)**
HTML-koden skapar strukturen för hemsidan:
- **`<header>`**: Visar namnet och titeln.
- **`<nav>`**: Skapar en meny med länkar till olika delar av sidan (ex. `#about` för sektionen "About Me").
- **`<main>`**: Innehåller de fyra huvudsakliga sektionerna.
- **`<footer>`**: Visar copyright-text och sociala medie-länkar.

### **CSS (Utseende och layout)**
CSS styr designen:
- **Typsnitt**: Google Fonts används för typsnitten "Roboto" och "Lora".
- **Färger**: Bakgrunder, textfärger och skuggor ger sidan en elegant känsla.
- **Responsiv design**: Layouten är optimerad för att se bra ut på både mobil och dator.

Exempel:
- **Grid Layout**: Sektionen "About Me" använder en `grid` för att placera text bredvid bilden:
  ```css
  .about-container {
      display: grid;
      grid-template-columns: 1fr 2fr;
      gap: 20px;
  }
