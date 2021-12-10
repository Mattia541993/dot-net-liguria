---
marp: true
---

![bg contain](assets/initial_cover.jpeg)
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

