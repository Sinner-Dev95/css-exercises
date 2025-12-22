# Holy Grail Mockup with Grid

Now that you've made your Holy Grail layout responsive, we are going to have some fun making it a bit more complicated and adding some features. You might find this to be a bit more challenging than you expected. You might even be tempted to use Flexbox. But for the sake of this practice assignment, try and see if you can figure out how to recreate this entire mockup using only Grid. Feel free to add in your own dummy content or styling too!

### Hints
- For this exercise you will need to add some CSS declaration blocks to the style.css file. Look through the HTML to see what selectors and combinators you can use.
- Take the layout one section at a time
- You don't need to add or change anything to the HTML, but it will be helpful to look through the parent and child relationships between elements
- Just like with Flexbox, you can easily center an item by making it into a grid
- Don't worry about the placeholder image element stretching when resizing the browser window. This will be covered in the Responsive lessons

## Desired Outcome

![desired outcome](./desired-outcome.png)

If you use the tools in the Advanced Grid Properties lesson you should be able to get your article cards to automatically fit as the browser window is adjusted:

![desired outcome stretched](./desired-outcome-stretched.png)

### Self Check
- The container element has two columns
- The container's second column is 4 times larger than the first column
- The container element has a gap of 4px
- The header element has two columns
- The `ul` inside the menu element contains another grid
- The `ul` inside the nav element contains another grid
- The sidebar element has a gap of 50px
- The text elements in the sidebar are centered with grid
- The article element should set grid columns using `repeat` along with the `auto-fit` and `minmax` properties
- The article columns should have a minimum value of 250px and a maximum of 1fr unit
- The article element has a gap of 15px
- The card elements inside the article container have a height of 200px
- The header and footer span across both columns
- The sidebar only spans across the first column
- The nav and article elements only span across the second column

---

# Mockup Holy Grail con Grid

Ora che hai reso il tuo layout Holy Grail responsivo, ci divertiremo a renderlo un po' più complicato aggiungendo alcune funzionalità. Potresti trovare questo esercizio un po' più difficile di quanto previsto. Potresti essere tentato di usare Flexbox. Ma per questo esercizio pratico, prova a vedere se riesci a ricreare l'intero mockup usando solo Grid. Sentiti libero di aggiungere il tuo contenuto fittizio o stilizzazione!

### Suggerimenti
- Per questo esercizio dovrai aggiungere alcuni blocchi di dichiarazioni CSS al file style.css. Guarda nell'HTML per vedere quali selettori e combinatori puoi usare.
- Prendi il layout una sezione alla volta
- Non devi aggiungere o modificare nulla nell'HTML, ma sarà utile esaminare le relazioni tra elementi parent e child
- Proprio come con Flexbox, puoi facilmente centrare un elemento trasformandolo in una grid
- Non preoccuparti se l'elemento immagine segnaposto si allunga quando ridimensioni la finestra del browser. Questo sarà trattato nelle lezioni sulla Responsività

## Risultato Desiderato

![desired outcome](./desired-outcome.png)

Se usi gli strumenti della lezione sulle Proprietà Avanzate di Grid, dovresti essere in grado di far adattare automaticamente le card dell'articolo quando la finestra del browser viene regolata:

![desired outcome stretched](./desired-outcome-stretched.png)

### Autoverifica
- L'elemento container ha due colonne
- La seconda colonna del container è 4 volte più grande della prima colonna
- L'elemento container ha un gap di 4px
- L'elemento header ha due colonne
- Il `ul` dentro l'elemento menu contiene un'altra grid
- Il `ul` dentro l'elemento nav contiene un'altra grid
- L'elemento sidebar ha un gap di 50px
- Gli elementi di testo nella sidebar sono centrati con grid
- L'elemento article dovrebbe impostare le colonne della grid usando `repeat` insieme alle proprietà `auto-fit` e `minmax`
- Le colonne dell'articolo dovrebbero avere un valore minimo di 250px e un massimo di 1fr unit
- L'elemento article ha un gap di 15px
- Gli elementi card dentro il container article hanno un'altezza di 200px
- Header e footer si estendono su entrambe le colonne
- La sidebar si estende solo sulla prima colonna
- Gli elementi nav e article si estendono solo sulla seconda colonna
