🌍 Resebyrå – HTML & CSS-projekt

🧭 Kort projektbeskrivning
Detta projekt är en responsiv och tillgänglig webbplats byggd med HTML och CSS, helt utan JavaScript.  
Sidan fungerar på både mobil, surfplatta och dator, och presenterar reseinformation om tre centraleuropeiska länder: Tyskland, Österrike och Schweiz.  

Webbplatsen är skapad med semantisk HTML, CSS Grid och Flexbox för layout, samt tillgänglighetsfunktioner som fokusstilar och lazy loading.  

 📸 Skärmdumpar
(Lägg till egna bilder här från projektet, exempelvis:)
<img width="1470" height="831" alt="Skärmavbild 2025-11-09 kl  15 02 38" src="https://github.com/user-attachments/assets/158089e6-13bf-4635-a169-0bc1923940a2" />
<img width="366" height="754" alt="Skärmavbild 2025-11-09 kl  15 03 10" src="https://github.com/user-attachments/assets/b61e54ba-33f4-46a2-be53-db4d5d5a97a9" />


🎨 Designbeslut & motivering

🎨 Färgval
- Primärfärg: Vinröd (#a94747) – ger en varm och reslig känsla, samtidigt som den kontrasterar väl mot vit text.  
- Bakgrund: Ljusrosa/beige (rgb(236, 212, 209)) – mjuk bakgrund som gör texten lättläst.  
- Textfärg: Vit på mörka ytor för hög kontrast.

✍️Typografi
- Typsnitt: Arial, sans-serif – enkelt, modernt och lättläst på alla enheter.  
- Rubriker: Stora, centrerade för att skapa struktur och tydlighet.  

 🧩 Layout
- CSS Grid används i huvudinnehållet för att skapa tre kolumner som anpassar sig efter skärmstorlek.  
- Flexbox används i navigation och footer för att centrera innehåll och ge jämna mellanrum.  
- Mobil-först-strategi med media queries (vid mindre än 768px  och större än 769 px) för god responsivitet.

---

🧠 CSS-mönster för interaktivitet
Projektet innehåller flera CSS-baserade interaktioner utan JavaScript:

- `:hover` och `:focus-visible` → används för länkar och knappar för tydlig användarfeedback.  
- `<details>/<summary>` → används för att expandera och visa mer information om varje land på ett tillgängligt sätt.  
- `@media` queries → används för att förändra layouten vid olika skärmstorlekar.  
- `loading="lazy"` → optimerar bildladdning och förbättrar prestandan.  


⚠️ Kända begränsningar & förbättringsidéer

🚧 Begränsningar
- Webbplatsen saknar JavaScript-funktionalitet (enligt krav) – vilket begränsar avancerad interaktivitet.  
- Bilder hämtas direkt från Wikimedia och saknar ibland konsekvent formatstorlek.  
- Ingen formell validering på kontaktformulär (än).  

💡Förbättringsidéer
- Implementera ett lättvikts-CSS-tema (ljus/mörk version) med `prefers-color-scheme`
- Skapa **fler sidor** för specifika städer med egna sektioner.  


👤 Skapad av
Abdinasir Yuusuf 
📧 abdinasir0520@gmail.com  

🔗https://www.linkedin.com/in/abdinasir-y-018452375 

💻(https://github.com/Abdinas1r

