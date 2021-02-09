

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
              <h5 class="text-center">Università degli Studi Milano-Bicocca - 2020/2021</h5>
              <h1 class="text-center">Twitch TV</h1>
			  <h2 class="text-center">Un'analisi dell'andamento della piattaforma di streaming Twitch </h2>
              <h4 class="text-center">Report a cura di:
                <span class="name">Mario Pedol 830296</span>. <br>
		<span class="name">Alessandro Fontanella 872590 </span>,<br>
                <span class="name">Nabil El Asri 826040 </span>,<br>
            
                
            



      <!-- Primo blocco di testo -->

	  <div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5>Introduzione</h5>
            <p>L’obiettivo di questo report è sviluppare un’analisi sull'andamento dei videogiochi sulla piattaforma di streaming Twitch. <br> Si sono raccolti dati riguardanti il numero di ore viste, canali attivi, spettatori, streamer e altri dettagli riguardanti le caratteristiche dei primi 200 videogiochi per numero di visualizzazioni dal 2016 al 2020.<br>
		</p>
          </div>
        </div>
      </div>





	<div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5></h5>
            <p>La prima visualizzazione è costituita da 2 grafici a dispersione che mettono a confronto la media dei canali più attivi per ogni genere con la media dei relativi spettatori. In particolare, nella Prima Si prendono in considerazione tutti i generi mentre nella seconda si è voluto porre un focus maggiore solamente sui generi che sono vicino alle 2 mediane.
			</p>
          </div>
		  </div>
      </div>

      <!-- PRIMA VIZ -->
 	<iframe 
	frameborder="0" 
	height="400" 
	width="575" 

	scrolling="no" src=""https://public.tableau.com/profile/nabil2453#!/vizhome/Storia_16128670805480/Storia3?:embed=yes"">
	</iframe>
			  </div>







	<div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5></h5>
            <p>La seconda Infografica invece è composta da una serie temporale per le visualizzazioni di ogni videogioco e genere per ogni mese di ogni anno a nostra disposizione. Si è deciso di accostare anche un Dot Plot che riporta il numero di visualizzazioni di ogni gioco per genere.
	Inoltre, è stata mantenuta sempre una distinzione tra generi outlier, individuati al punto precedente, che quindi risultano essere più frequentati e i generi meno frequentati.


      <!-- SERIE STORICA -->
      <div class="container viz">
        <div class="row">
	<iframe 
	frameborder="0" 
	height="400" 
	width="575" 

	scrolling="no" src=""https://public.tableau.com/profile/nabil2453#!/vizhome/Infografica2_16128674860610/Dashboard1?:embed=yes"">
	</iframe>
     			  </div>
      </div>







      <div class="container">
        <div class="row">
          <div class="col-md-8 col-md-offset-2">
            <h5></h5>
            <p>In quest'ultima visualizzazione si è voluto costruire un Bump Chart che evidenziasse come si è evoluto il Rank (calcolato come somma totale delle visualizzazioni per ogni anno) dei videogiochi più visti per le principali case produttrici.
          </div>
        </div>
      </div>

      <!-- REGION -->
      <div class="container viz">
        <div class="row">
          <iframe width="1200" height="700" src="" frameborder="0" allowFullScreen="true"></iframe>
        </div>
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
	In particolare, si sono rilevati i giochi di maggior successo come Fortnite, i generi che attirano maggior attenzione e le case produttrici che sviluppano i miglior videogame. Non è possibile svolgere analisi più approfondite a causa della mancanza di dati dovuti principalmente alla riservatezza della piattaforma e degli sviluppatori, comunque sia questi dati rappresentano una possibile base per sviluppare modelli predittivi al fine di individuare, il miglior gioco per aprire un canale.

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
			<p> INSERIRE NOTE METODOLOGICHE</p>
	<h5>Euristiche e Caveat</h5>
             <p>

	</p>
              <!-- Seguire indicazioni prof Cabitza. Aggiungere immagini con taf img se necessario-->
              <h2>Questionari</h2>
              <p>Per fare un check sulla qualità delle nostre infografiche sono stati effettuati tre tipologie di assessment: la valutazione qualitativa delle euristiche, il questionario psicometrico e lo user test.
			  </p>


			  <h5>Valutazione qualitativa delle euristiche</h5>
			  <p>
			  </p>


              <h5>Questionario psicometrico</h5>
              <p> PSICO</p>



              <h5>Test Utente</h5>
              <p>  TEST UTENTE </p>

	</body>
	</html>

