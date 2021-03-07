<html lang="en">
<head>
	
<style>
/*-------------------------------*/
/*            Typography            */
/*-------------------------------*/
body{background-color: #007ea7;
background-image: linear-gradient(315deg, #007ea7 0%, #80ced7 74%);
}


h1 {
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
  font-size: 50px;
  letter-spacing: -1px;
  margin-top: 44px;
  margin-bottom: 0;
}

h2 {
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: 400;
  font-size: 30px;
  letter-spacing: 0;
  margin-bottom: 22px;
}

h4 {
  font-family: 'Source Code Pro', monospace;
  font-weight: 400;
  font-size: 14px;
  padding-top: 44px;
}

h5 {
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: 600;
  font-size: 14px;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.name {
  text-transform: uppercase;
}

p {
  font-family: 'PT Serif', serif;
  font-size: 22px;
  line-height: 150%;
  padding-bottom: 44px;
}

.intro {
 
}


.text {
  padding-top: 20px;
}

.viz {
  min-height: 400px;
  border-top: 1px #d2d2d2 solid;
  border-bottom: 1px #d2d2d2 solid;
  margin: 20px auto 70px;
}

.viz img {
  min-width: 100%;
  max-width: 100%;
}

.howTo {
  
  min-height: 300px;
  padding-top: 44px;
  padding-bottom: 88px;
}

.howTo p{
  font-size: 16px;
  line-height: 150%;
  padding-bottom: 0px;
}

.howToSide p{
  font-family: 'Source Code Pro', monospace;
  font-size: 14px;
  padding-bottom: 0px;
  letter-spacing: -1px;
  margin: 0 0 0px;
}

#tools {
  margin-top: 44px;
}

a {
  color: #FFA500;
}

a:hover {
  color: #c74446;
}
</style>
	
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
  <meta name="description" content="">
  <meta name="author" content="">
  <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700|PT+Serif:400,400i,700,700i|Source+Code+Pro|Source+Sans+Pro:200,200i,300,300i,400,400i,600,600i,700,700i,900,900i" rel="stylesheet">
  <link rel="icon" href="../../favicon.ico">

  <title>Data Viz Lab</title>
 
  <!-- Just for debugging purposes. Don't actually copy these 2 lines! -->
  <!--[if lt IE 9]><script src="../../assets/js/ie8-responsive-file-warning.js"></script><![endif]-->
  <script src="../../assets/js/ie-emulation-modes-warning.js"></script>

  <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
  <!--[if lt IE 9]>
  <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
  <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
  <![endif]-->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
</head>

<body>

    <!-- Intro con titolo e immagine. Inserire immagine in /media/ con il nome cover.png
    Al posto dei segna posto aggiungere il vostro nome e matricola negli <span> -->
      <div class="intro">
        <div class="container">
          <div class="row">
            <div class="col-md-8 col-md-offset-2 text">
              <h5 class="text-center">Università degli Studi Milano-Bicocca - 2020/2021</h5><i class="fa fa-twitch fa-5x"></i>
              <h1 class="text-center">Twitch TV</h1>
	   	
			  <h2 class="text-center">Un'analisi dell'andamento della piattaforma di streaming Twitch </h2>
              <h4 class="text-center">Report a cura di:
                <span class="name">Mario Pedol 830296</span>, <br>
		<span class="name">Alessandro Fontanella 872590 </span>,<br>
                <span class="name">Nabil El Asri 826040 </span>,<br>
   

      <!-- Primo blocco di testo -->

	  <div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5>Introduzione</h5>
            <p>L’obiettivo di questo report è sviluppare un’analisi dell'andamento dei videogiochi sulla piattaforma di streaming Twitch. <br> Si sono raccolti dati riguardanti il numero di ore viste, canali attivi, spettatori, streamer e altri dettagli riguardanti le caratteristiche dei primi 200 videogiochi per numero di visualizzazioni dal 2016 al 2020.<br>
		</p>
          </div>
        </div>
      </div>





	<div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5></h5>
            <p>La prima visualizzazione è costituita da 2 grafici a dispersione che mettono a confronto la media dei canali più attivi per ogni genere con la media dei relativi spettatori. In particolare, nella prima si prendono in considerazione tutti i generi mentre nella seconda si è voluto porre un focus maggiore solamente sui generi che sono vicino alle 2 mediane.
			</p>
          </div>
		  </div>
      </div>

      <!-- PRIMA VIZ -->

<div class='tableauPlaceholder' id='viz1612892393199' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;St&#47;Storia_16128670805480&#47;Storia3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Storia_16128670805480&#47;Storia3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;St&#47;Storia_16128670805480&#47;Storia3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1612892393199');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1116px';vizElement.style.height='1191px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>








	<div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5></h5>
            <p>La seconda Infografica invece è composta da uno stacked area graph per le visualizzazioni di ogni videogioco e genere per ogni mese di ogni anno a nostra disposizione. Si è deciso di accostare anche un Dot Plot che riporta il numero di visualizzazioni di ogni gioco per genere.
	Inoltre, è stata mantenuta sempre una distinzione tra generi outlier, individuati al punto precedente, che quindi risultano essere più frequentati e i generi meno frequentati.


      <!-- SECONDA VIZ -->
      <div class="container viz">
        <div class="row">
	<div class='tableauPlaceholder' id='viz1612892511953' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Infografica2_16128674860610&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Infografica2_16128674860610&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Infografica2_16128674860610&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1612892511953');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1400px';vizElement.style.height='1027px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1400px';vizElement.style.height='1027px';} else { vizElement.style.width='100%';vizElement.style.height='827px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
     			  </div>
      </div>







      <div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5></h5>
            <p>In quest'ultima visualizzazione si è voluto costruire un Bump Chart che evidenziasse come si è evoluto il Rank,calcolato come somma totale delle visualizzazioni per ogni anno, dei videogiochi più visti per le principali case produttrici. Si è inoltre deciso di calcolare tale Rank da un punto di partenza comune da luglio 2017 fino ad ottobre 2020.

      <!-- TERZA VIZ -->
      <div class="container viz">
     <div class='tableauPlaceholder' id='viz1612892555928' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Info3_16128905855910&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Info3_16128905855910&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Info3_16128905855910&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1612892555928');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1400px';vizElement.style.height='927px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1400px';vizElement.style.height='927px';} else { vizElement.style.width='100%';vizElement.style.height='927px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
      </div>



	<div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
           




      <!-- Quarto blocco di testo con le conlusioni-->
      <div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5>CONCLUSIONI</h5>
            <p>Queste visualizzazioni mostrano come si è evoluta fino a ottobre 2020 la piattaforma di streaming, nata per i videogiochi, Twitch.
	In particolare, si sono rilevati i giochi di maggior successo come Fortnite, i generi che attirano maggior attenzione e le case produttrici che sviluppano i migliori videogame. Non è possibile svolgere analisi più approfondite a causa della mancanza di dati dovuta principalmente alla riservatezza della piattaforma e degli sviluppatori, comunque sia questi dati rappresentano una possibile base per sviluppare modelli predittivi al fine di individuare il miglior gioco per aprire un canale.

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
			<p> Il report è stato sviluppato utilizzando dati provenienti dal sito <a href="https://sullygnome.com/">Twitch analytics and statistics</a> e successivamente arrichiti con altri dati provenienti da <a href="https://www.vgchartz.com/gamedb/">Games DataBase</a> ed inoltre con dati da <a href="https://it.wikipedia.org/wiki/The_Game_Awards">The Game Awards</a>  . Per approfondire si faccia riferimento a questo documento. I dati sono stati inizialmente esportati dal database MongoDB in formato json e convertiti in formato csv per poter essere utilizzati su Tableau.</p>
		<h5> PreProcessing </h5>
		<p> Durante la fase di preprocessing sono state effettuate diverse operazioni per pulire i dati grezzi raccolti attraverso web scraping provenienti da <a href="https://www.vgchartz.com/gamedb/">Games DataBase</a> e <a href="https://it.wikipedia.org/wiki/The_Game_Awards">The Game Awards</a>.
		In particolare rispetto al primo dataset si è dovuta effettuare una modifica dello schema con cui i dati erano stati immagazzinati: droppando diversi campi che non indicavano informazioni per noi utili, inoltre si è resa necessaria la formattazione dei nomi dei videogiochi e delle dati di rilascio degli stessi in un formato standard. Successivamente per il secondo dataset proveniente da <a href="https://it.wikipedia.org/wiki/The_Game_Awards"> wikipedia italia</a>  si è effettuata un'operazione di traduzione delle informazioni ricavate dallo scraping in lingua inglese così da uniformare i dati rispetto alla lingua del dataset principale  </p>
              <h5>Caveat</h5>
              <p> Le infografiche sono state create tenendo conto dei caveat presentati a lezione. In alcuni casi si riscontrano comunque leggere anomalie dettate da motivazioni differenti
		<ul> 
		<li> Nella prima infografica, non è stata possibile inserire un legenda che indicasse i differenti generi dei videogiochi, il problema risiede nel  numero elevato che li caratterizza. Si è preferito quindi inserire dei riferimenti scritti che contestualizzassero meglio il contesto.</li>
		<li> Nella serie storica non è stato possibile inserire, per ogni gioco presente, una descrizione dettagliata riguardante gli eventi salienti nell'arco del periodo osservato. La complessità, non è tanto da attribuire alla ricerca dei punti significativi lungo la serie temporale, bensì alla selezione delle numerosi fonti da cui ricavare le date degli avvenimenti. Si è deciso così, al posto di considerare tutti i singoli giochi, di analizzare soltanto "Counter-Strike: Global Offensive" (genere Shooter) poiché presenta un andamento che influisce non poco sulla linea temporale generica.</li>
		<li> Nella terza infografica nel Bump Chart l'asse delle ordinate e' invertito, 
	sebbene possa risultare controintuitivo tale scelta è stata adottata,sulla base di feedback, al fine di rappresentare al meglio il concetto di classifica</li></ul></p>
              <h2>Questionari</h2>
              <p>Per verificare la qualità delle nostre infografiche sono stati effettuati tre tipologie di assessment: la valutazione qualitativa delle euristiche, il questionario psicometrico e lo user test.
			  </p>


			  <h5>Valutazione qualitativa delle euristiche</h5>
			  <p> Sono stati intervistati sei utenti, i quali hanno interagito mediamente un minuto con le diverse infografiche.I principali problemi evidenziati sono la poca semplicità e chiarezza della seconda e terza infografica. Mentre la prima è stata apprezzata per la sua intuitività.
			  </p>


              <h5>Questionario psicometrico</h5>
              <p> Per poter valutare la nostra prima visualizzazione abbiamo sottoposto il questionario psicometrico Cabitza-Locoro a 32 utenti. Le tre infografiche sono state valutate attraverso una scala da 1 (Poco) a 6 (Molto) rispetto agli attributi qualitativi “Utilità”, “Intuitività”, “Chiarezza”, “Informatività”, “Bellezza” e “Valutazione Generale”. Successivamente i valori sono stati suddivisi per poter effettuare un'analisi più approfondita:
	<ul>
	  <li>1 e 2 -> “Valutazione negativa”;</li>
 	  <li>3 e 4 -> "Valutazione neutra";</li>
	  <li>5 e 6 -> “Valutazione positiva”.</li>
	</ul></p>
	<h5> Prima infografica </h5>
	<div class='tableauPlaceholder' id='viz1612901775396' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Info1val&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Info1val&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Info1val&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1612901775396');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
	<a href="https://ibb.co/CsjLJys"><img src="https://i.ibb.co/n8Xp3y8/Screenshot-2021-02-09-R-Graphics-Output-info1-pdf.png" alt="Screenshot-2021-02-09-R-Graphics-Output-info1-pdf" border="0"></a><br /><a target='_blank' href='https://it.imgbb.com/'></a><br/>
	<h5> Seconda infografica </h5>
	<div class='tableauPlaceholder' id='viz1612902153664' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Info2Val&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Info2Val&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Info2Val&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1612902153664');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
	<a href="https://ibb.co/Tmycq8k"><img src="https://i.ibb.co/0h5qVMc/Screenshot-2021-02-09-R-Graphics-Output-info2-pdf.png" alt="Screenshot-2021-02-09-R-Graphics-Output-info2-pdf" border="0"></a><br /><a target='_blank' href='https://it.imgbb.com/'></a><br />
	<h5> Terza infografica </h5>
	<div class='tableauPlaceholder' id='viz1612902200632' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;in&#47;info3val&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='info3val&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;in&#47;info3val&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1612902200632');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
	<a href="https://ibb.co/SJrtWDb"><img src="https://i.ibb.co/g6VSHbN/Screenshot-2021-02-09-R-Graphics-Output-info3-pdf.png" alt="Screenshot-2021-02-09-R-Graphics-Output-info3-pdf" border="0"></a><br /><a target='_blank' href='https://it.imgbb.com/'></a><br />
              <h5>Test Utente</h5>
              <p>  Persone coinvolte 6 <br>
	Inoltre per effettuare una verifica sulla fruizione generale del report è stato richiesto lo svolgimento di tre semplici task a diversi utenti, registrando le risposte ed il tempo impiegato. <br>
	<ol>
	<li>Task 1 - Quale genere in media ha più canali e spettatori attivi?</li>
	<li>Task 2 - Quale tra i generi outlier è il gioco più variabile tra i più visti?</li>
	<li>Task 3 - Quale publisher ha il gioco che migliora di più?</li> </ol>
	In tabella sono riportati i tempi di esecuzione dei tre compiti (in verde i tempi delle persone che hanno necessitato di un aiuto nel completamento del task):
	
	<a href="https://imgbb.com/"><img src="https://i.ibb.co/y571pnB/photo-2021-03-07-18-17-23.jpg" alt="photo-2021-03-07-18-17-23" border="0"></a><br /><a></a><br />
	
	<a href="https://ibb.co/YtY2NZt"><img src="https://i.ibb.co/tbkBHXb/media-mediana.jpg" alt="media-mediana" border="0"></a>
	
	<br> Nel seguente grafico sono riportati i tempi di esecuzione dei tre compiti:
	
	<a href="https://ibb.co/ZK3vZ4D"><img src="https://i.ibb.co/d6SXhCY/Violin-Plot.jpg" alt="Violin-Plot" border="0"></a>
	</p>
