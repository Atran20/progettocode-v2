### CSS Cheat Sheet

## Selettori CSS

I selettori CSS sono utilizzati per identificare gli elementi HTML a cui applicare le regole di stile.

- `elemento`: Seleziona tutti gli elementi HTML corrispondenti a un determinato tipo di elemento. Ad esempio, `p` seleziona tutti gli elementi `<p>` (paragrafo).
- `#id`: Seleziona un elemento HTML con un determinato ID. Ad esempio, `#header` seleziona un elemento con l'ID "header".
- `.classe`: Seleziona tutti gli elementi HTML con una determinata classe. Ad esempio, `.button` seleziona tutti gli elementi con la classe "button".

## Proprietà CSS

Le proprietà CSS sono utilizzate per definire l'aspetto e la formattazione degli elementi HTML.

- `color`: Imposta il colore del testo.
- `font-size`: Imposta la dimensione del carattere.
- `font-family`: Imposta la famiglia di caratteri.
- `background-color`: Imposta il colore di sfondo.
- `margin`: Imposta i margini esterni dell'elemento.
- `padding`: Imposta lo spazio interno dell'elemento.
- `border`: Imposta lo stile, lo spessore e il colore del bordo dell'elemento.
- `width` e `height`: Impostano la larghezza e l'altezza dell'elemento.

## Valori CSS

I valori CSS sono utilizzati per specificare colori, dimensioni e altri attributi.

- **Colori**: I colori possono essere specificati utilizzando nomi di colore, codici esadecimali (`#RRGGBB`), codici RGB (`rgb(red, green, blue)`) o codici RGBA (`rgba(red, green, blue, alpha)`).
- **Dimensioni**: Le dimensioni possono essere specificate utilizzando unità come pixel (`px`), percentuali (`%`), em (`em`), rem (`rem`), e altre.

## Pseudo-classi e pseudo-elementi

Le pseudo-classi e i pseudo-elementi sono utilizzati per applicare stili in base a stati o posizioni particolari degli elementi.

- `:hover`: Applica uno stile quando l'elemento viene selezionato con il mouse.
- `:active`: Applica uno stile quando l'elemento è attivo.
- `:focus`: Applica uno stile quando l'elemento ha lo stato di focus.
- `::before` e `::after`: Aggiunge contenuto prima e dopo il contenuto di un elemento.

## Layout e posizionamento

Le proprietà di layout e posizionamento sono utilizzate per controllare la disposizione degli elementi sulla pagina.

- `display`: Imposta il tipo di display dell'elemento (come `block`, `inline`, `inline-block`, `flex`, `grid`, ecc.).
- `position`: Imposta il tipo di posizionamento dell'elemento (come `static`, `relative`, `absolute`, `fixed`).
- `float`: Imposta l'allineamento laterale dell'elemento.
- `clear`: Imposta il comportamento di pulizia delle fluttuazioni.

# Esempi di codici

- **Colori principali**

body {
background-color: #f8f9fa;
color: #333;
}

- **Link**
  a {
  color: #007bff;
  text-decoration: none;
  }

a:hover {
text-decoration: underline;
}

- **Testo evidenziato**
  .highlight {
  background-color: #ffc107;
  color: #333;
  } `

- **Dimensione del testo**
  h1 {
  font-size: 24px;
  }

p {
font-size: 16px;
}

- **Famiglia di caratteri**
  body {
  font-family: Arial, sans-serif;
  }

- **Grassetto**
  strong {
  font-weight: bold;
  }
  /_ Menu di navigazione _/
  .navbar {
  background-color: #333;
  padding: 10px 0;
  }

- **Elementi del menu**
  .navbar ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  }

.navbar li {
display: inline-block;
}

- **Link del menu**
  .navbar a {
  color: white;
  text-decoration: none;
  padding: 10px 15px;
  }

.navbar a:hover {
background-color: #555;
}
