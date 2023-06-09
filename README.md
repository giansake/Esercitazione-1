## Esercitazione 1 - E-commerce card layout

Partendo dal file `index.html` in `./problem/index.html` modificate il file di stile nella stessa cartella per replicare il layout della carta numero 2 in `assets/mock-up.pdf`.

![Esercitazione 1 - prima e dopo](./assets/prima:dopo.gif "Prima e dopo")

**Non è necessario modificare la struttura HTML**, in questa esercitazione concentratevi sul CSS.:

### Obiettivi

1. Posizionare il badge giallo affinchè sia in sovrapposizione all'immagine della carta.

2. Centrare verticalmente il testo segnaposto della carta

#### Obiettivi bonus

1. Replicare le carte e costruire una griglia di _prodotti_

![Esercitazione 1 - bonus grid](./assets/bonus/grid-mock-up.png "Grid layout")

2.  Aggiungere una sezione di intestazione, con titolo e call to action (bottone)

3.  Cambiare foto e lunghezze dei testi per rendere le carte diverse tra loro e verificare la solidità del CSS scritto.

4.  Aggiungere i tag `<navbar>` e `<navitem>`, per creare una barra di navigazione con il logo e degli ipotetici link alle altre pagine del sito.
5.  Aggiungere un footer con il logo e il nome dell'azienda.

![Esercitazione 1 - bonus page](./assets/bonus/page-mock-up.png "Grid layout")

```html
<navbar>
  <nav>
    <img src="..path-to-logo" alt="site-brand" />

    <ul>
      <li>...</li>
      <li></li>
      <li>...</li>
      <li></li>
      <li>...</li>
      <li></li>
    </ul>
  </nav>
</navbar>
...
<footer>...</footer>
```

---

---

---

---

# Tips

Analizzate la struttura HTML prima di iniziare a scrivere il CSS.
Procedete per step, non cercate di fare tutto in una volta.
Seguite gli obiettivi, partite dalla carta senza badge, poi aggiungete il badge, poi il testo segnaposto, poi il testo vero, poi il bottone, poi la griglia, poi la navbar, poi il footer.

```css
position: relative;
position: absolute;
```

```css
object-fit: cover;

background: url(...);
background-repeat: no-repeat;
background-size: cover;
background-position: center;
```

```css
top: 0;
left: 0;
```

```css
display: flex;
flex-direction: column;
```

```css
box-shadow: ...;
border-radius: ...;
```
