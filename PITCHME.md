---
marp: true
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
---

![bg contain](assets/initial_cover.jpeg "Cover image")
![bg](rgb(0,0,0))

---
<!-- backgroundColor: #f7f7f7 -->
![bg left contain](assets/articoli_dark_bottoni_non_visibili.jpeg)

# Bottoni non visibili in dark mode
# Semantica dei controlli
# Ordine di navigazione

---

![bg right contain](assets/logout_light.jpeg)
![bg right contain](assets/logout_dark.jpeg)

# Colore testi hardcoded bianco/nero
Alcuni testi non possono più essere letti

---

![bg left contain](assets/bottone_non_accessibile.jpeg)

# Immagini che si comportano da bottoni
Che differenza c'è tra un bottone contenente un'immagine e un'immagine alla quale è stato assegnato un tap gesture recognizer? **Tantissimo!**

---

![bg right contain](assets/lista_ordini_light.jpeg)
![bg right contain](assets/lista_ordini_dark.jpeg)

# Elementi della lista senza semantica 
I campi dell'intestazione vengono letti **solo una volta** dallo screen reader. Poi, per ogni elemento della lista, vengono letti solo i valori.

---

![bg left contain](assets/bottone_non_accessibile.jpeg)
![bg left contain](assets/menu_lat_sx_non_rientra_correttamente.jpeg)

# Utilizza elementi di UI standard
- **L'accessibilità è gratis** ed è meno oneroso gestire le interazioni con l'utente (con meno bug)
    - In questo caso la view laterale quando è nascosta è comunque accessibile dallo screen reader
- L'app assume un aspetto più professionale

---

![bg right contain](assets/menu_laterale_light.jpeg)
![bg right contain](assets/menu_laterale_dark.jpeg)

# Utilizza elementi di UI standard (2)
I problemi di accessibilità possono emergere anche senza attivare lo screen reader

---

# Multi columns in Marp slide

<div class="columns">
<div>

## Column 1

Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas eveniet, corporis commodi vitae accusamus obcaecati dolor corrupti eaque id numquam officia velit sapiente incidunt dolores provident laboriosam praesentium nobis culpa.

</div>
<div>

## Column 2

Tempore ad exercitationem necessitatibus nulla, optio distinctio illo non similique? Laborum dolor odio, ipsam incidunt corrupti quia nemo quo exercitationem adipisci quidem nesciunt deserunt repellendus inventore deleniti reprehenderit at earum.

</div>
</div>