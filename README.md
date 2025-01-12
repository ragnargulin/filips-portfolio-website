# Grattis på 30-årsdagen Filip!


Det här är en personlig portfolio-webbplats skapad för Filip Mellgren, en doktorand i ekonomi. Hemsidan är byggd med HTML, CSS och  JavaScript för att skapa en enkel och responsiv design. Här hittar du information om hur koden fungerar och hur du kan uppdatera eller bygga vidare på den.

Här kan du se en preview på sidan:
https://html-preview.github.io/?url=https://github.com/ragnargulin/filips-portfolio-website/blob/main/filipmellgren.html

---

## 🎯 **Vad gör hemsidan?**
Den här hemsidan presenterar information om dig. Varje område är en <section>. Om du vill lägga till något kan du göra en ny sektion och lägga till denna i din meny:
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
CSS styr designen. För enkelhets skull har jag lagt den i din html-fil, men egentligen vill du ha den i en egen fil med .css-format:
- **Typsnitt**: Google Fonts används för typsnitten "Roboto" och "Lora". Google fonts är gratis och väldigt bra. Om du inte gillar de typsnitt jag valt kan du kolla vidare på Google fonts och välja något annat.
- **Färger**: Bakgrunder, textfärger och skuggor ger sidan en elegant känsla. Dessa kan du ändra efter smak. Textfärg heter "color" och bakgrunder heter "background-color"
- **Responsiv design**: Layouten är optimerad för att se bra ut på både mobil och dator. Tänk på att ha dynamiska format om du anger storlekar. Exempelvis vill du inte ha bredden i pixlar, eftersom den då inte skalas dynamiskt.

Exempel:
- **Grid Layout**: Sektionen "About Me" använder en `grid` för att placera text bredvid bilden:
  ```css
  .about-container {
      display: grid;
      grid-template-columns: 1fr 2fr;
      gap: 20px;
  }
