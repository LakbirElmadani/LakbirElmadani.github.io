
<html>
  <head>
   <meta charset="utf-8">
    <title>Lakbir Elmadani</title>
    <link rel="stylesheet" href="styles.css">
	 <link rel="icon" type="image/png" href="https://media.licdn.com/dms/image/D4E03AQHBx7UuGxxiUw/profile-displayphoto-shrink_400_400/0/1669068581473?e=1680134400&v=beta&t=U5Kq6ldmngFnaTwSFH_I4D8XWeu0YeuuBSm68H0TIOU">
    <meta name="viewport" content="width=device-width, initial-scale=5.0">

  </head>
  <style>
   /* CSS */
body {
  font-family: Arial, sans-serif;
}
header {
  background-color: #333;
  color: white;
  padding: 20px;
}
header nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
header nav ul li {
  display: inline-block;
  margin-right: 10px;
}
header nav ul li a {
  color: white;
  text-decoration: none;
}
section {
  margin: 50px;
}

.image {
width: 400px;
height: 300px;
display: block;
margin-left: auto;
margin-right: auto;
}

        body {
            background-color: #fff;
            color: #000;
        }

        /* css pour le mode sombre */
        .dark-mode {
            background-color: #000;
            color: #fff;
        }

        /* css pour le bouton */
        .dark-mode-toggle {
            position: absolute;
            top: 10px;
            right: 10px;
            padding: 10px;
            background-color: #fff;
            color: #000;
            border: none;
            cursor: pointer;
        }
     footer {
  background-color: #FFFF00; /* couleur jaune */
  padding: 10px;
  text-align: center;
}

#icon {
    width: 5%;
    height:3%;
}
 p {
      font-family: Papyrus;
      font-size: 22px;
      color: blue;
    }
	
	   /* Add some styling for the button */
    #myBtn {
      display: none; /* Hidden by default */
      position: fixed; /* Fixed position */
      bottom: 20px; /* Place the button at the bottom of the page */
      right: 30px; /* Place the button 30px from the right */
      z-index: 99; /* Make sure it stays on top */
      border: none; /* Remove borders */
      outline: none; /* Remove outline */
      background-color: red; /* Set a background color */
      color: white; /* Text color */
      cursor: pointer; /* Add a mouse pointer on hover */
      padding: 15px; /* Some padding */
      border-radius: 10px; /* Rounded corners */
    }

    /* Add animation for the button */
    #myBtn.follow {
      animation: follow 0.5s ease-out;
    }

    /* Keyframe animation */
    @keyframes follow {
      from {bottom: 20px; right: 30px;}
      to {bottom: 50px; right: 50px;}
    }
	
	.clock {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  border: 20px solid #333;
  margin: 50px auto;
  position: relative;
  padding: 20px;
  box-shadow: 
    0 0 0 4px #fff, 
    inset 0 0 0 3px #999,
    inset 0 0 10px black,
    0 0 10px rgba(0,0,0,0.2); 
}

.clock-face {
  width: 100%;
  height: 100%;
  position: relative;
  transform: translateY(-3px); /* fix for safari */
}

.hand {
  width: 50%;
  height: 6px;
  background: #333;
  position: absolute;
  top: 50%;
  transform-origin: 100%;
  transform: rotate(90deg);
  transition: all 0.05s;
  transition-timing-function: cubic-bezier(0.1, 2.7, 0.58, 1);
}

   </style>
   
  <body>
   <button onclick="topFunction()" id="myBtn" title="Go to top">vers le haut</button>
   <button id="dark-mode-btn">
  <img src="https://cdn4.iconfinder.com/data/icons/other-elements-rounded-outline/24/outline_moon-512.png" id="icon" alt="Dark mode toggle icon">
</button>
    <header>
      <nav>
        <ul>
          <li><a href="#about">A propos</a></li>
          <li><a href="#services">Projets</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
	<!-- Add the clock element -->
<div class="clock">
  <div class="clock-face">
    <!-- Add the hour markers -->
    <div class="hand hour-hand"></div>
    <div class="hand minute-hand"></div>
    <div class="hand second-hand"></div>
  </div>
</div>
    <section id="about">
      <h1>A propos de moi</h1>
      <p>Je suis Lakbir Elmadani, un étudiant en génie électrique. Je suis très motivé pour apprendre de nouvelles choses et relever des défis dans ma carrière en tant qu'étudiant ingénieur. Mon ambition est de devenir un ingénieur électrique expérimenté et de contribuer à résoudre les problèmes énergétiques mondiaux à l'avenir. Je suis curieux de nature et j'aime explorer de nouvelles technologies et concepts. Actuellement, je suis à la recherche d'un stage professionnel pour acquérir de l'expérience pratique et développer mes compétences en tant qu'étudiant ingénieur. Je suis convaincu que mes connaissances théoriques et mes compétences techniques me permettront de relever les défis de l'industrie de l'énergie dans l'avenir.</p>
    </section>
   <section id="services">
  <h1>Mes projets</h1>
  <ul>
    <li>
      <div>
        <h2>Stage d'ingénieur:OCP (Office Chérifienne des Phosphates)</h2>
        <p>-Étude du système supervision d'un banc d'essai pour les moteurs  électriques triphase</p>
          <p> -Diminuer le nombre d'interventions de l'ouvrier et identification des défauts probables, en utilisant l'analyser spectral</p>      
           <p>-Faire une étude techno-économique détaillée sur les solutions dans les câbles et les protocoles de communication et le choix de variateurs de vitesse et des capteurs nécessaires.</p> 
		   <p>                                                                                                               07/2022 - 09/2022, Khouribga</p>
		<img src="https://upload.wikimedia.org/wikipedia/commons/1/1c/OCP_Group.svg" class="image">
      </div>
    </li>
    <li>
      <div>
        <h2>Stage d'initiation professionnelle:Coopérative Halib Rich</h2>
        <p>-Étude détaillée sur les appareillages de protections pour l'installation de coopérative</p>
         <p>-Vérifier la sélectivité et la sensibilité des appareille de protection.</p> 
         <p>Lors de ce stage, j'ai étudié les différents types d'appareillages de protection disponibles pour</p>
         <p>les installations électriques de la coopérative Halib Rich,en me concentrant sur les disjoncteurs,</p>
         <p> les fusibles et les relais de surintensité. J'ai évalué les caractéristiques de ces appareils et j'ai choisi ceux </p>
         <p>qui conviennent le mieux pour protéger les différents équipements de la coopérative,</p>
         <P>en prenant en compte les risques potentiels tels que les courts-circuits et les surcharges.</p>
         <p>J'ai également effectué une analyse détaillée de la sélectivité et de la sensibilité des appareils de protection choisis.</p>
		 <P>La sélectivité est la capacité des appareils de protection à isoler uniquement la zone défectueuse de l'installation,</p>
		 <p>sans perturber le reste de l'installation. La sensibilité est la capacité des appareils de protection à réagir rapidement </p>
		 <p>et efficacement aux défauts électriques. J'ai vérifié que les appareils de protection choisis répondent aux exigences de sélectivité </p>
		 <p>et de sensibilité requises pour protéger efficacement les équipements de la coopérative</p>
		 <p>08/2021 - 09/2021, Er-Rich</p>
        <img src="https://media.licdn.com/dms/image/C4E16AQGNrd5YY6QWng/profile-displaybackgroundimage-shrink_350_1400/0/1657199515466?e=1680134400&v=beta&t=aU3sjMS6PoVFsnxht5zf06nJp2cCcR0Q8uEL2q9L6Og" class="image">
	  </div>
    </li>
    <li>
      <div>
        <h2>TIPE:Optimiser la puissance produite par une hydrolienne</h2>
        <p>-Implimenter MPPT pour extraire la plus possible de puissance.</p>
		<p>J'ai choisi d'utiliser un MPPT pour maximiser la production d'énergie de l'hydrolienne en suivant </p>
		<p>le point de puissance maximale à différentes vitesse de vent. L'intérêt d'utiliser un MPPT est qu'il permet</p>
		<p>d'optimiser l'utilisation de l'énergie produite par l'hydrolienne en adaptant la tension de sortie à la vitesse de vent.</p>
		       <p>05/2020 CPGE-SETTAT</p>
           <img src="https://cdn.futura-sciences.com/cdn-cgi/image/width=1520,quality=50,format=auto/sources/images/glossaire/HydroliennePaimpol_EDF.jpg" class="image">
	  </div>
	  <li>
      <div>
        <h2>Contrôle d'objets connectés via une application mobile APK utilisant Firebase, MQTT et une ESP8266</h2>
        <p>Dans ce projet, j'ai développé une application mobile APK pour contrôler des objets connectés via une ESP8266,</p>
		<p>un module WiFi populaire utilisé pour les projets IoT. J'ai utilisé Firebase, une plateforme de développement</p>
		<p>d'applications mobiles de Google, pour stocker et récupérer les données de l'objet connecté. J'ai utilisé MQTT, </p>
		<p>un protocole de communication IoT léger, pour envoyer et recevoir des commandes entre l'application mobile </p>
        <p>et l'ESP8266.J'ai configuré l'ESP8266 pour se connecter au réseau WiFi et pour communiquer avec Firebase via MQTT. </p>
		<p>J'ai également développé des fonctionnalités dans l'application APK pour contrôler les différentes  </p>
		<p>fonctionnalités de l'objet connecté, comme l'allumer ou éteindre.</p> <p>2022 EHTP</p>
           <img src="https://fiverr-res.cloudinary.com/images/t_main1,q_auto,f_auto,q_auto,f_auto/gigs2/172492114/original/1863471e3f08f3560c27b1572f1254412d0c933d/do-iot-based-arduino-esp8266-esp32-and-nodemcu-projects.png" class="image">
	  </div>
	 <div>
	  <h2>Modélisation de la partie électrique de voiture électrique</h2>
        <p>Dans ce projet, j'ai étudié les problèmes qui freinent l'électrification du secteur automobile dans le monde, </p> 
		<p>comme les coûts élevés des batteries, la faible autonomie et les infrastructures de recharge insuffisantes.</p> 
		<p>J'ai également comparé les avantages et les inconvénients des voitures électriques et des voitures diesel en</p>  
		<p>termes de performance, d'empreinte carbone et de coûts d'exploitation. J'ai ensuite utilisé des outils de modélisation</p> 
         <p> et de simulation pour analyser et modéliser les composants de la transmission électrique (drivetrain) ,</p> 
		  <p>d'une voiture électrique tels que le moteur électrique, l'inverseur de fréquence et la transmission. </p> 
		  <p> J'ai simulé les performances de ces composants sous différentes conditions de conduite pour évaluer leur efficacité énergétique.</p> 
		 , <p>2022 EHTP</p>
           <img src="https://substance.etsmtl.ca//wp-content/uploads/2015/09/schema-THSeAF1.jpg" class="image">
	  </div>
    </li>
    </li>
  </ul>
</section>

    <section id="contact">
      <h1>Contactez-moi</h1>
     <form action="mailto:lmadanilkbir7@gmail.com" method="post" enctype="text/plain">
      <label for="nom">Nom :</label>
      <input type="text" id="nom" name="nom"><br><br>
      <label for="email">Email :</label>
      <input type="email" id="email" name="email"><br><br>
      <label for="message">Message :</label>
      <textarea id="message" name="message"></textarea><br><br>
      <input type="submit" value="Envoyer">
     </form>
    </section>
 <script>
 
 
 
 
 
 
 
 
 
 ////////////////////////////////
        let darkMode = false;
  const button = document.querySelector("#dark-mode-btn");
  const icon = document.querySelector("#icon");

  button.addEventListener("click", () => {
    darkMode = !darkMode;
    if (darkMode) {
      document.body.classList.add("dark-mode");
      icon.src = "https://cdn4.iconfinder.com/data/icons/other-elements-rounded-outline/24/outline_sun-512.png";
    } else {
      document.body.classList.remove("dark-mode");
      icon.src = "https://cdn4.iconfinder.com/data/icons/other-elements-rounded-outline/24/outline_moon-512.png";
    }
  });
     // When the user scrolls down 20px from the top of the document, show the button
    window.onscroll = function() {scrollFunction()};

    function scrollFunction() {
      if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
        document.getElementById("myBtn").style.display = "block";
        document.getElementById("myBtn").classList.add("follow"); // add the "follow" class
      } else {
        document.getElementById("myBtn").style.display = "none";
        document.getElementById("myBtn").classList.remove("follow"); // remove the "follow" class
      }
    }

    // When the user clicks on the button, scroll to the top of the document
    function topFunction() {
      document.body.scrollTop = 0;
      document.documentElement.scrollTop = 0;
    }
	
	
	
	//////////////////////////clock
	  "use strict";
    const cx = 100, cy = 100;  // Radius
    const _clockstyle = "width: " + (2 * cx) + "px;  height: " + (2 * cy) + "px;"
      + "border: 7px solid #282828; background: #585858;"
      + "border-radius: 50%; margin: 50px;"
      + "box-shadow: -4px -4px 10px rgba(67,67,67,0.5), inset 4px 4px 10px rgba(0,0,0,0.5),"
      + "inset -4px -4px 10px rgba(67,67,67,0.5), 4px 4px 10px rgba(0,0,0,0.3);"

    sidiv("", _clockstyle)
    let c = canvas2D({ width: px(2 * cx), height: px(2 * cy) })
    c.ctx.lineCap = "round"
    unselectBase()

    // Paint anything radial
    function tick(color, width, angle, length, innerlength = 0) {
      function ls(length) { return length * Math.sin(angle / 180.0 * Math.PI) }
      function lc(length) { return -length * Math.cos(angle / 180.0 * Math.PI) }
      c.setLineType(width, color)
      c.line(cx + ls(innerlength), cy + lc(innerlength), cx + ls(length), cy + lc(length))
    }

    // Draw clock
    function drawClock() {
      c.clear()
      // Draw ticks
      for (let i = 0; i < 360; i += 30)
        if ((i % 90) == 0) tick("#1df52f", 5, i, 88, 70)
        else tick("#bdbdcb", 3, i, 88, 75)

      // draw hands
      let t = new Date();  // get time
      tick("#61afff", 5, t.getHours() * 30, 50)  // hour
      tick("#71afff", 2, t.getMinutes() * 6, 70)  // min
      tick("#ee791a", 2, t.getSeconds() * 6, 80)  // s

      // drwa center
      c.setFillStyle("#4d4b63")
      c.circle(cx, cy, 10, { fill: true })
    }
    drawClock()
    setInterval(drawClock, 1000)
  
	
    </script>
	 <footer>
      <p>Copyright © 2023 Lakbir Elmadani</p>
    </footer>
	<!-- Add the JavaScript -->
<script>
const secondHand = document.querySelector('.second-hand');
const minuteHand = document.querySelector('.minute-hand');
const hourHand = document.querySelector('.hour-hand');

function setDate() {
  const now = new Date();

  const seconds = now.getSeconds();
  const secondsDegrees = ((seconds / 60) * 360) + 90;
  secondHand.style.transform = `rotate(${secondsDegrees}deg)`;

  const minutes = now.getMinutes();
  const minutesDegrees = ((minutes / 60) * 360) + ((seconds/60)*6) + 90;
  minuteHand.style.transform = `rotate(${minutesDegrees}deg)`;

  const hours = now.getHours();
  const hoursDegrees = ((hours / 12) * 360) + ((minutes/60)*30) + 90;
  hourHand.style.transform = `rotate(${hoursDegrees}deg)`;
}

setInterval(setDate, 1000);

setDate();
</script>
  </body>


</html>

