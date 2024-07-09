# Curriculum

## Descrizione

Questo è un progetto di portfolio personale che include una sezione di codici referral, un curriculum, progetti, link a GitHub e una sezione di contatti. È costruito utilizzando HTML, CSS, JavaScript e Bootstrap per garantire un design reattivo e moderno.

## Struttura del Progetto

- `index.html`: Pagina principale del sito.
- `curriculum.html`: Pagina del curriculum.
- `projects.html`: Pagina dei progetti.
- `github.html`: Pagina dei repository GitHub.
- `referrals.html`: Pagina dei codici referral.
- `contact.html`: Pagina di contatto.
- `assets/css/styles.css`: File CSS personalizzato.
- `assets/js/scripts.js`: File JavaScript personalizzato (se necessario).

## Installazione
Se non disponi di un account github, registrati: (https://github.com/login) 

1. Clona il repository:

    ```bash
    git clone https://github.com/tuo-username/tuo-repository.git
    ```

2. Vai nella directory del progetto:

    ```bash
    cd tuo-repository
    ```

3. Crea un nuovo branch per personalizzare il tuo portfolio:

    ```bash
    git checkout -b my-portfolio
    ```

## Utilizzo

1. Apri il file `index.html` nel tuo browser per visualizzare la pagina principale del sito.
2. Naviga tra le varie pagine utilizzando la navbar per esplorare le diverse sezioni del portfolio.
3. Personalizza il file `curriculum.html` per aggiungere il tuo curriculum in formato PDF.

### Come Aggiungere il Curriculum in Formato PDF

1. Carica il tuo file PDF nella directory `assets/pdf/`.
2. Modifica il file `curriculum.html` per includere il link al tuo PDF:

    ```html
    <section class="curriculum">
        <h1>Il Mio Curriculum</h1>
        <p>Scarica il mio curriculum in formato PDF <a href="assets/pdf/tuo-curriculum.pdf" target="_blank">qui</a>.</p>
    </section>
    ```

## Tecnologie Utilizzate

- HTML5
- CSS3
- JavaScript
- [Bootstrap 5.3.3](https://getbootstrap.com/)

## Struttura della Navbar

La navbar è costruita utilizzando Bootstrap e include le seguenti voci:

- Home
- Curriculum
- Progetti
- GitHub
- Referral Codes
- Contatti

# Funzionalità Aggiuntive

## Caricamento dei Github

## Caricamento dei Codici Referral

I codici referral vengono caricati dinamicamente utilizzando jQuery. Il codice JSON è stato incluso direttamente nel file JavaScript per semplificare l'esempio.


# Contributi
I contributi sono benvenuti! Sentiti libero di inviare una pull request o aprire una issue per discutere le modifiche che desideri apportare.

# Licenza
Questo progetto è sotto licenza MIT. Vedi il file LICENSE per maggiori dettagli.

# Contatti
Per qualsiasi domanda, puoi contattarmi tramite la pagina Contatti.

# Ringraziamenti
Grazie per aver visitato il mio portfolio!
