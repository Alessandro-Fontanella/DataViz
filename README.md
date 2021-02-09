<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
  <meta name="description" content="">
  <meta name="author" content="">
  <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700|PT+Serif:400,400i,700,700i|Source+Code+Pro|Source+Sans+Pro:200,200i,300,300i,400,400i,600,600i,700,700i,900,900i" rel="stylesheet">
  <link rel="icon" href="../../favicon.ico">

  <title>Data Viz Lab</title>

  <!-- Bootstrap core CSS -->
  <link href="css/bootstrap.min.css" rel="stylesheet">

  <!-- IE10 viewport hack for Surface/desktop Windows 8 bug -->
  <link href="css/ie10-viewport-bug-workaround.css" rel="stylesheet">

  <!-- Custom styles for this template -->
  <link href="css/style.css" rel="stylesheet">

  <!-- Just for debugging purposes. Don't actually copy these 2 lines! -->
  <!--[if lt IE 9]><script src="../../assets/js/ie8-responsive-file-warning.js"></script><![endif]-->
  <script src="../../assets/js/ie-emulation-modes-warning.js"></script>

  <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
  <!--[if lt IE 9]>
  <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
  <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
  <![endif]-->
</head>

<body>

    <!-- Intro con titolo e immagine. Inserire immagine in /media/ con il nome cover.png
    Al posto dei segna posto aggiungere il vostro nome e matricola negli <span> -->
      <div class="intro">
        <div class="container">
          <div class="row">
            <div class="col-md-8 col-md-offset-2 text">
              <h5 class="text-center">Università degli Studi Milano-Bicocca - 2018/2019</h5>
              <h1 class="text-center">STREAMTRAINS</h1>
			  <h2 class="text-center">Un'analisi dei ritardi delle Frecce di Trenitalia nel mese di maggio 2019</h2>
              <h4 class="text-center">Report a cura di:
                <span class="name">Giulia Chiaretti (800928)</span>,
                <span class="name">Federica Fiorentini (807124)</span>,
                <span class="name">Riccardo Maganza (808053)</span>e
                <span class="name">Alberto Monaco (803669)</span>.
              </div>
          </div>
          </div>
      </div>



      <!-- Primo blocco di testo -->

	  <div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5>Introduzione</h5>
            <p>L’obiettivo di questo report è sviluppare un’analisi sull'andamento dei ritardi delle Frecce di Trenitalia.
			<br>Sono stati analizzati i percorsi effettuati nel mese di maggio 2019 dai treni Frecciabianca, Frecciarossa, Frecciargento e Frecciarossa 1000.
			<br> Si è posta particolare attenzione sui ritardi realizzati dai treni nelle diverse stazioni, regioni e tratte italiane.
			<br> Dai risultati ottenuti è stato calcolato un indice per confrontare la puntualità dei treni nazionali italiani con quelli francesi (TGV).
			<br>
			</p>
          </div>
        </div>
      </div>





	<div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5></h5>
            <p>La prima visualizzazione è costituita da una flow map in cui è possibile visualizzare le tratte di tutte le Frecce di Trenitalia, colorate in base al ritardo mediano che i treni accumulano nelle stazioni di passaggio.
			<br>È possibile selezione la categoria e/o il numero del treno a cui si è interessati, piuttosto che inserire la stazione di partenza o di arrivo dello stesso. Nel grafico a barre, invece, viene riportato il ritardo mediano di tutte le stazioni italiane e, tramite l'effetto hover del mouse, viene mostrato l'andamento giornaliero del ritardo mediano.
			</p>
          </div>
		  </div>
      </div>

      <!-- ITINERARIO -->
      <div class="container viz">
        <div class="row">
          <iframe width="1200" height="700" src="https://app.powerbi.com/view?r=eyJrIjoiMTQ4MzI3MDEtMmUxYS00ZGY2LWI4NjEtMDI1NzI2NTQ2ZTBiIiwidCI6IjdmMmY4NzQwLWZkZWYtNGEzOS1iNjgyLTI4NWI1NWI2OWE0MCIsImMiOjh9" frameborder="0" allowFullScreen="true"></iframe>
		  </div>







	<div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5></h5>
            <p>La seconda infografica riporta la serie storica del ritardo medio nel mese di maggio delle Frecce.
			<br>Se si preferisce, è possibile visionare l'andamento del ritardo medio per una determinata ripartizione geografica, tipologia di Freccia o fascia oraria.
			<br>Se si desidera conoscere il motivo di ritardi eccezionali registrati il 5 e il 13 maggio, si può cliccare sul pulsante “Info”
			</div>
        </div>
      </div>

      <!-- SERIE STORICA -->
      <div class="container viz">
        <div class="row">
          <iframe width="1200" height="700" src="https://app.powerbi.com/view?r=eyJrIjoiY2Q3ODEwNDctOWEzZC00ZmM1LTk1ZWMtMmZkZjVjMmE0ZTU0IiwidCI6IjdmMmY4NzQwLWZkZWYtNGEzOS1iNjgyLTI4NWI1NWI2OWE0MCIsImMiOjh9" frameborder="0" allowFullScreen="true"></iframe>
		  </div>
      </div>







      <div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5></h5>
            <p>Nella terza infografica si può visualizzare un grafico a barre in cui viene rilevato, per ogni regione, il numero di treni arrivati in orario e in ritardo al capolinea.
			<br>Nel coropleto, invece, le regioni sono colorate in base all'indice di puntualità dei treni.
			<br>Infine, nella nota metodologica è indicato il criterio con cui si definisce la puntualità o il ritardo di un treno e la formula con cui è stato concepito l'indice di puntualità.
			  <hr>
			NB: sia nel coropleto che nel grafico a barre alcune regioni non compaiono, questo è duvuto al fatto che non esistono Frecce che completano il loro itinerario in quella regione.
          </div>
        </div>
      </div>

      <!-- REGION -->
      <div class="container viz">
        <div class="row">
          <iframe width="1200" height="700" src="https://app.powerbi.com/view?r=eyJrIjoiOGY1NmM4YWQtZWRmYS00YzhkLTg1YTUtM2FhNzZiYzBhMmI3IiwidCI6IjdmMmY4NzQwLWZkZWYtNGEzOS1iNjgyLTI4NWI1NWI2OWE0MCIsImMiOjh9" frameborder="0" allowFullScreen="true"></iframe>
        </div>
      </div>




	<div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5>"Dicci dove vuoi andare e ti diremo quanto ritardo farai!"</h5>
            <p>
			<br> Infine è stato deciso di creare, sulla base dei dati raccolti, una visualizzazione interattiva che ricorda il sito ufficiale di Trenitalia che permette all'utente di conoscere il ritardo medio della tratta di interesse.
			<br> E' possibile inserire la città da cui si desidera partire e quella dove si vuole arrivare e se si preferisce conoscere il ritardo medio nel weekend o nei giorni infrasettimanali.
          </div>
        </div>
      </div>

      <!-- GIOCO -->
      <div class="container viz">
        <div class="row">
          <iframe width="1200" height="600" src="https://app.powerbi.com/view?r=eyJrIjoiOTQ5MjVmZDMtYTA3Yy00MjkxLTk3Y2UtNDgwZjk4MDE1YTc0IiwidCI6IjdmMmY4NzQwLWZkZWYtNGEzOS1iNjgyLTI4NWI1NWI2OWE0MCIsImMiOjh9" frameborder="0" allowFullScreen="true"></iframe>
		  </div>
      </div>





      <!-- Quarto blocco di testo con le conlusioni-->
      <div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5>CONCLUSIONI</h5>
            <p>Queste visualizzazioni riportano una descrizione completa della situazione delle Frecce di Trenitalia.
			<br>L'obiettivo del report è rendere più trasparente uno dei servizi nazionali più diffusi e utilizzati. Infatti, tramite le nostre visualizzazioni interattive, l'utente ottiene informazini utili che gli permettono di essere informato riguardo uno specifico treno, una particolare tratta o una determinata stazione.
			<br>E' stato possibile vedere che nel mese di maggio la regione meno puntuale è stata l'Abruzzo dove si è registrato un indice di puntualità del 60%, mentre la regione più puntuale si è dimostrata la Calabria, con un indice del 97%.
			<br>Dalla prima infografica,invece, è stato possibile concludere che sulla tratta adriatica i ritardi sono magigori rispetto alla tratta tirrenica.
			<br>Al momento ci siamo limitati ad un'analisi descrittiva, ma sviluppi futuri potrebbero portare ad un progetto molto più ampio.
			<br>Si potrebbe analizzare la correlazione del ritardo con diverse variabili come, ad esempio:
			<br> - le condizioni metereologiche;
			<br> - il periodo dell'anno;
			<br> - la presenza di festività nazionali o locali;
			<br> - la congestione delle linee ferroviarie;
			<br> - la presenza di compagnie concorrenti che offrono un servizio analogo.
			</ul>
			</p>
			</div>

          </div>
        </div>



      <div class="howTo">
        <div class="container">
          <div class="row">
            <div class="col-md-6 col-md-offset-2">

              <!-- In questa parte descrivere il processo di raccolta, pulizia e visualizzazione dei dati. Che tipo di dati avevo? Che tipo di operazioni sono state effettuate per poter visualizzare i dati. Come si leggono le visualizzazioni?-->
              <h2>Note Metodologiche</h2>
              <h5>Dati Utilizzati</h5>
			<p>Questo report è stato sviluppato a partire da dati raccolti per tutto il mese di Maggio dalle API ufficiali di Trenitalia. La particolare natura e il complesso meccanismo di questi strumenti ha reso necessario l'impiego di un'architettura in grado di raccogliere i dati in tempo reale. Per approfondire si faccia riferimento a questo <a href="documentationMANAGEMENT.pdf"> documento</a>.
<br> I dati sono stati inizialmente esportati dal database in formato json e successivamente convertiti in formato csv compatibile con il software utilizzato (PowerBI).
</p>
<h5>Preprocessing</h5>
<p>Durante una prima fase di preprocessing i dati grezzi sono stati "puliti" per ovviare a inconsistenze intrinseche al sistema di Trenitalia.
<br>E' stata effettuata una modifica dello <a href="schema_dati.pdf"> schema</a> con cui sono stati importati i dati in modo da renderli relazionali e, quindi, compatibili con PowerBi.
<br>Una delle modifiche più consistenti è stata l'eliminazione di alcune stazioni a seguito del confronto tra le stazioni presenti nelle tratte regolari di Trenitalia e quelle effettivamente rilevate dal nostro sistema.
<br>Più nello specifico sono state eliminate le seguenti stazioni: Torricola, Rimini Fiera, Milano Rho Fiera, Castel Bolognese, Imola e Lambrate. Tutte queste fermate sono state effettuate dalle Frecce per eventi straordinari come l'alluvione in Romagna registrata nel 13 maggio per cui alcuni treni della tratta adriatica sono stati dirottati eccezionalmente sulle stazioni di Imola e Castel Bolognese.
</p>
<h5>Indice di puntualità</h5>
<p>Per stilare un ranking delle regioni in base alla puntualità dei treni interessati, è stato creato un'indice di puntualità. Questo indice è stato creato in maniera confrome alle regole utilizzate dalla SSF, compagna nazionale francese, in modo da poter confrontare i due indici di puntualit nazionali.
<br>In particolare, i treni sono stati classificati come puntuali secondo le seguenti condizioni:
<ul>
<li>un treno è puntuale se termina il percorso con un ritardo inferiore a 5 minuti se la durata prevista dell'intera tratta è inferiore a 90 minuti;
<li>un treno è puntuale se termina il percorso con un ritardo inferiore a 10 minuti se la durata prevista dell'intera tratta è compresa tra 90 minuti e 180 minuti;
<li>un treno è puntuale se termina il percorso con un ritardo inferiore a 15 minuti se la durata prevista dell'intera tratta è superiore a 180 minuti.
</ul>
<br>Dopo aver classificato i treni in puntuali e non, l'indice di puntualità regionale è la percentuale dei treni puntuali giunti a destinazione rispetto al totale dei treni che terminano il percorso nella rispettiva regione
<br>Come si nota dal grafico, per le isole e per la Valle d'Aosta l'indice non è stato calcolato perchè non sono interessate dai percorsi delle frecce. Per il Molise e la Basilicata, invece, non è stato possibile calcolare l'indice di puntualità perchè non esistono Frecce che terminano in queste due regioni, ma vengono effettuate solamente fermate intermedie.
</p>
<h5>Euristiche e Caveat</h5>
             <p>Sono state create le infografiche in modo tale da rispettare le seguenti euristiche di Shneiderman:
			<br>“Overview first, zoom and filter, then details-on-demand”<br>
				<ul>
				<li>Overview first: in ogni inforgrafica è stata inserita un'introduzione per permettere all'utente di orientarsi al meglio.
				<li>Zoom and Filter: attraverso i filtri presenti nella maggior parte delle infoviz l’utente ha la possibilità di scegliere la stazione di interesse, il numero e la tipologia del treno, la fascia oraria o la regione di interesse. Inoltre, in ogni visualizzazione i grafici sono vicendevolmente collegati quindi selezionando un elemento da un grafico, viene immediatamente filtrato anche l'alro.</li>
				<li>Details-on-demand: nei grafici è possibile visualizzare le caratteristiche di un singolo elemento o avere informazioni più dettagliate tramite l'effetto hover del mouse. Grazie all'inserimento di tooltip, infatti, è stato ad esempio possibile visualizzare sulla serie storica il violin plot giornaliero con la distribuzione dei ritardi differenziati per tipologia treno.
				<li>History: nelle visualizzazioni interattive è possibile effettuare diverse operazioni tramite i diversi filtri presenti. E' stato inserito, inoltre, un pulsante a rappresentato da una freccia che permette di tornare allo stato iniziale della visualizzazione.</li>
				</ul>
				<br>Inoltre si è tenuto conto dei <a href="ChecklistCAVEAT.pdf"> caveat</a> per ceare "buone" visualizzazioni.
<br>Nonostante l'impegno nel rispettare queste euristiche e porre attenzione ai caveat, in alcuni casi sono stati riscontrate delle mancanze dovute a limitazioni del software utilizzato (PowerBI)
<br>I problemi riscontrati sono stati:
<ul>
<li> Nella prima infografica c'era la necessità di impostare una formattazione condizionale per i colori, in modo da ottenere una scala divergente con il bianco come colore centrale corrispondente al valore zero. Tuttavia la flow map utilizzata non mette a disposizione questa funzionalità.
<li> Non essendo a disposizione una mappa riferita alle linee ferroviarie italiane, è stata utilizzata una normale flow map. Quindi le tratte sono rappresentate da segmenti e non seguono l'andamento reale delle ferrovie.
<li> Nella serie storica non è stato possibile inserire in corrispondenza del ritardo medio giornaliero la rispettiva deviazione standard, quindi è stato scelto di inserire in un violin tutta la distribuzione grazie ad un tooltip.
<li> Nella serie storica non è stato possibile inserire delle precisazioni sul grafico stesso che spiegassero i picchi in quanto è una serie storica interatttiva. Quindi filtrano per una specifica tipologia di treno il grafico muta e a quel punto i commenti non sarebbero stati più coerenti. Per ovviare al problema sono stati inseriti,in corrispondenza dei giorni caratterizzati da picchi alti di ritardo medio, due pulsanti "info" che rimandano a spiegazioni aggiuntive circa le cause di questi ritardi eccezionali.
<li> Il sofware PowerBi, a differenza di Tablueau, non ha una funzione automatica che tenga traccia di tutti i filtri applicati. Quindi è stato creata manualmente un pulsante "segnalibro", rappresentato da una freccia, ch permette di tornare allo stato iniziale della visualizzazione, ma non nei passaggi intermedi.
</ul>
</p>
              <!-- Seguire indicazioni prof Cabitza. Aggiungere immagini con taf img se necessario-->
              <h2>Questionari</h2>
              <p>Per fare un check sulla qualità delle nostre infografiche sono stati effettuati tre tipologie di assessment: la valutazione qualitativa delle euristiche, il questionario psicometrico e lo user test.
			  </p>


			  <h5>Valutazione qualitativa delle euristiche</h5>
			  <p>Sono state intervistati tre utenti a cui è stato chiesto di interagire con le infografiche per qualche minuto e di commentare ad alta voce i diversi grafici.
			  <br>Grazie a questo tipo di attività è stato possibile individuare i seguenti problemi delle infografiche:
			  <ul>
			  <li>Non risultava immediato rimuovere i numerosi filtri presenti nella prima infografica. Per questo motivo è stata inserita, tramite il pulsante freccia "back" la possibilità di tornare allo stato iniziale della visualizzazione, nonostante queste non fosse una funzione automatica di PowerBI, come spiegato precedentemente.
			  <li>Sempre nella prima infografica, selezionando una stazione di partenza, vengono automaticamente visualizzate le stazioni di arrivo (capolinea) dei treni in questione. In alcuni casi, invece, gli utenti pensavano di poter vedere tutte le fermate intermedie del treno. Non è stato possibile, tuttavia, assecondare questi suggerimenti per vincoli legati allo schema relazionale dei dati stessi.
			  <li>Nella flow map, oltre alle tratte, erano state inizialmente inserite anche le stazioni, colorate in base al ritardo medio accumulato, ma risultava troppo pesante come visualizzazione quindi si è scelto di rimuoverle.
			  </ul>
              <br>
			  </p>


              <h5>Questionario psicometrico</h5>
              <p>Per poter valutare la nostra prima visualizzazione abbiamo sottoposto il <a href="https://docs.google.com/forms/d/e/1FAIpQLSe4B_khiC9HyWXn34ZYxHb-4Moc4bylp4l34V4tu-bl0cZlpA/viewform?usp=sf_link"> questionario psicometrico</a> Cabitza-Locoro a 32 utenti.
			  E' stato chiesto loro di valutare le tre infografiche principali attraverso una scala da 1 (Pochissimo) a 6 (Moltissimo) relativamente agli attributi qualitativi “Utilità”, “Intuitività”, “Chiarezza”, “Informatività”, “Bellezza” e “Valutazione Generale”.
			  <br>Essendo la scala da 1 a 6, i valori sono stati suddivisi in:
<ul>
<li>1 e 2 -> “Valutazione negativa”;
<li>3 e 4 -> "Valutazione neutra";
<li>5 e 6 -> “Valutazione positiva”.
<ul>
			  <br>A questo punto i risultati sono stati rappresentati tramite tre stacked bar charts:
			  <hr><img src="Infografica1.jpeg"><hr><hr><img src="Infografica2.jpeg"><hr><hr><img src="Infografica3.jpeg"><hr>

			  <p>Analizzando i barchart, il risultato più rilevante è che, in generale, la prima infografica è stata di più difficile comprensione. Risulta esserci una percentuale significativa di risposte negative, soprattutto relativamente alla "Chiarezza" e "Intuitività" dell'infografica.
			  <br>Per quanto riguarda le altre due infografiche, invece, si nota una significativa maggioranza di giudizi positivi sia rispetto alle risposte neutre che negative.
			  <p>Per valutare la correlazione tra gli attributi qualitativi presenti nel questionario abbiamo ritenuto opportuno l’utilizzo di un correlogramma.

			  <hr><img src="corrplot1.png"><hr><hr><img src="corrplot2.png"><hr><hr><img src="corrplot3.png"><hr>
			  <p>Nel triangolo superiore sono presenti dei corrplot, che si differenziano tra loro per forma e colore. Questi ultimi indicano la forza della correlazione, che varia da -1 a 1.
Più la forma è simile ad un ellisse, maggiore è la correlazione, che a seconda dell’inclinazione verso l’alto o il basso può essere rispettivamente positiva o negativa.
Più la forma è simile ad un cerchio, invece, più tale attributo si avvicina allo 0.
Il blu corrisponde a valori positivi mentre il rosso a quelli negativi; in questo caso tutte le correlazioni presenti sono positive.
Si può notare in tutte e tre le infografiche la coppia di attributi "Chiara" e "Intuitiva" risultano avere la correlazione più alta, mediamente pari all'87%.



              <h5>Test Utente</h5>
              <p>Per ottenere un feedback sull’efficienza generale e sull'usabilità del report è stato chiesto a 16 utenti di svolgere 3 <a href="domandeTask.png"> task</a> differenti (uno per ogni infografica), registrando la correttezza delle risposte e il tempo impiegato, misurandolo in secondi.
			  Si è scelto in questo caso di focalizzare l'attenzione sulla tipologia di utente che si interagisce con l'infografica; per questo motivo è stato chiesto agli utenti di auto-definirsi "esperti" o "non esperti" di dati in base al campo di studio/lavoro.
			  Questo ha permesso di verificare se ci fossero differenze significative tra i due gruppi.<br>
			  Per valutare la differenza dei tempi di risposta e la relativa distribuzione, è stato ritenuto opportuno l’utilizzo di violin plot riportati di seguito.
				<hr><img src="ViolinTask1.png"><hr><hr><img src="ViolinTask2.png"><hr><hr><img src="ViolinTask3.png"><hr>
				<p>È possibile notare che, per tutti e tre i task, i tempi di risposta di chi si ritiene non esperto di dati, sono maggiori rispetto a chi, invece, si ritiene esperto.
			  <br>In particolare, la differenza tra i tempi di esecuzione medi tra gli utenti esperti e non risulta essere di 23,7 secondi per il task 1, di 11,6 secondi per il task 2 e di 17,1 secondi per il task riferito all'ultima infografica.
			  <br>Per valutare la significatività di queste quantità sono stati effettuati test t da cui è emerso, appunto, che tale differenza tra i tempi medi di esecuzione è statisticamente significativa per tutti e tre i task. (p value Task1= 0.000174, p-value Task2= 8.324e-05, p-value Task3 = 0.00359)
			  <br>
			  <br>
			  <hr>







            <div class="col-md-3 col-md-offset-1 howToSide">
            <h5>Dati utilizzati</h5>
            <p><a href="train.xlsx">Train</a></p>
			<p><a href="streamtrains.csv">Streamtrains</a></p>
			<p><a href="punctuality.csv">Punctuality</a></p>
            <h5 id="tools">Strumenti utilizzati</h5>
            <p><a href="https://powerbi.microsoft.com/it-it/">PowerBI</a></p>
			<p><a href="https://cran.r-project.org/">R</a></p>
            </div>
          </div>
        </div>
      </div>

    </div>













  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script>window.jQuery || document.write('<script src="../../assets/js/vendor/jquery.min.js"><\/script>')</script>
  <script src="js/bootstrap.min.js"></script>
  <script src="js/ie10-viewport-bug-workaround.js"></script>
  <script>$(document).ready(function () {
    var trigger = $('.hamburger'),
    overlay = $('.overlay'),
    isClosed = false;

    trigger.click(function () {
      hamburger_cross();
    });

    function hamburger_cross() {

      if (isClosed == true) {
        overlay.hide();
        trigger.removeClass('is-open');
        trigger.addClass('is-closed');
        isClosed = false;
      } else {
        overlay.show();
        trigger.removeClass('is-closed');
        trigger.addClass('is-open');
        isClosed = true;
      }
    }

    $('[data-toggle="offcanvas"]').click(function () {
      $('#wrapper').toggleClass('toggled');
    });
  });
  </script>

</body>
</html>
