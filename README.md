
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
  width: 200px;
  height: 200px;
  border-radius: 30%;
  border: 20px solid #333;
  margin: 50px auto;
  position: relative;
  left: 400;
  top: 0;
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
      <p>Je suis Lakbir Elmadani, un ??tudiant en g??nie ??lectrique. Je suis tr??s motiv?? pour apprendre de nouvelles choses et relever des d??fis dans ma carri??re en tant qu'??tudiant ing??nieur. Mon ambition est de devenir un ing??nieur ??lectrique exp??riment?? et de contribuer ?? r??soudre les probl??mes ??nerg??tiques mondiaux ?? l'avenir. Je suis curieux de nature et j'aime explorer de nouvelles technologies et concepts. Actuellement, je suis ?? la recherche d'un stage professionnel pour acqu??rir de l'exp??rience pratique et d??velopper mes comp??tences en tant qu'??tudiant ing??nieur. Je suis convaincu que mes connaissances th??oriques et mes comp??tences techniques me permettront de relever les d??fis de l'industrie de l'??nergie dans l'avenir.</p>
    </section>
   <section id="services">
  <h1>Mes projets</h1>
  <ul>
    <li>
      <div>
        <h2>Stage d'ing??nieur:OCP (Office Ch??rifienne des Phosphates)</h2>
        <p>-??tude du syst??me supervision d'un banc d'essai pour les moteurs  ??lectriques triphase</p>
          <p> -Diminuer le nombre d'interventions de l'ouvrier et identification des d??fauts probables, en utilisant l'analyser spectral</p>      
           <p>-Faire une ??tude techno-??conomique d??taill??e sur les solutions dans les c??bles et les protocoles de communication et le choix de variateurs de vitesse et des capteurs n??cessaires.</p> 
		   <p>                                                                                                               07/2022 - 09/2022, Khouribga</p>
		<img src="https://upload.wikimedia.org/wikipedia/commons/1/1c/OCP_Group.svg" class="image">
      </div>
    </li>
    <li>
      <div>
        <h2>Stage d'initiation professionnelle:Coop??rative Halib Rich</h2>
        <p>-??tude d??taill??e sur les appareillages de protections pour l'installation de coop??rative</p>
         <p>-V??rifier la s??lectivit?? et la sensibilit?? des appareille de protection.</p> 
         <p>Lors de ce stage, j'ai ??tudi?? les diff??rents types d'appareillages de protection disponibles pour</p>
         <p>les installations ??lectriques de la coop??rative Halib Rich,en me concentrant sur les disjoncteurs,</p>
         <p> les fusibles et les relais de surintensit??. J'ai ??valu?? les caract??ristiques de ces appareils et j'ai choisi ceux </p>
         <p>qui conviennent le mieux pour prot??ger les diff??rents ??quipements de la coop??rative,</p>
         <P>en prenant en compte les risques potentiels tels que les courts-circuits et les surcharges.</p>
         <p>J'ai ??galement effectu?? une analyse d??taill??e de la s??lectivit?? et de la sensibilit?? des appareils de protection choisis.</p>
		 <P>La s??lectivit?? est la capacit?? des appareils de protection ?? isoler uniquement la zone d??fectueuse de l'installation,</p>
		 <p>sans perturber le reste de l'installation. La sensibilit?? est la capacit?? des appareils de protection ?? r??agir rapidement </p>
		 <p>et efficacement aux d??fauts ??lectriques. J'ai v??rifi?? que les appareils de protection choisis r??pondent aux exigences de s??lectivit?? </p>
		 <p>et de sensibilit?? requises pour prot??ger efficacement les ??quipements de la coop??rative</p>
		 <p>08/2021 - 09/2021, Er-Rich</p>
        <img src="https://media.licdn.com/dms/image/C4E16AQGNrd5YY6QWng/profile-displaybackgroundimage-shrink_350_1400/0/1657199515466?e=1680134400&v=beta&t=aU3sjMS6PoVFsnxht5zf06nJp2cCcR0Q8uEL2q9L6Og" class="image">
	  </div>
    </li>
    <li>
      <div>
        <h2>TIPE:Optimiser la puissance produite par une hydrolienne</h2>
        <p>-Implimenter MPPT pour extraire la plus possible de puissance.</p>
		<p>J'ai choisi d'utiliser un MPPT pour maximiser la production d'??nergie de l'hydrolienne en suivant </p>
		<p>le point de puissance maximale ?? diff??rentes vitesse de vent. L'int??r??t d'utiliser un MPPT est qu'il permet</p>
		<p>d'optimiser l'utilisation de l'??nergie produite par l'hydrolienne en adaptant la tension de sortie ?? la vitesse de vent.</p>
		       <p>05/2020 CPGE-SETTAT</p>
           <img src="https://cdn.futura-sciences.com/cdn-cgi/image/width=1520,quality=50,format=auto/sources/images/glossaire/HydroliennePaimpol_EDF.jpg" class="image">
	  </div>
	  <li>
      <div>
        <h2>Contr??le d'objets connect??s via une application mobile APK utilisant Firebase, MQTT et une ESP8266</h2>
        <p>Dans ce projet, j'ai d??velopp?? une application mobile APK pour contr??ler des objets connect??s via une ESP8266,</p>
		<p>un module WiFi populaire utilis?? pour les projets IoT. J'ai utilis?? Firebase, une plateforme de d??veloppement</p>
		<p>d'applications mobiles de Google, pour stocker et r??cup??rer les donn??es de l'objet connect??. J'ai utilis?? MQTT, </p>
		<p>un protocole de communication IoT l??ger, pour envoyer et recevoir des commandes entre l'application mobile </p>
        <p>et l'ESP8266.J'ai configur?? l'ESP8266 pour se connecter au r??seau WiFi et pour communiquer avec Firebase via MQTT. </p>
		<p>J'ai ??galement d??velopp?? des fonctionnalit??s dans l'application APK pour contr??ler les diff??rentes  </p>
		<p>fonctionnalit??s de l'objet connect??, comme l'allumer ou ??teindre.</p> <p>2022 EHTP</p>
           <img src="https://fiverr-res.cloudinary.com/images/t_main1,q_auto,f_auto,q_auto,f_auto/gigs2/172492114/original/1863471e3f08f3560c27b1572f1254412d0c933d/do-iot-based-arduino-esp8266-esp32-and-nodemcu-projects.png" class="image">
	  </div>
	 <div>
	  <h2>Mod??lisation de la partie ??lectrique de voiture ??lectrique</h2>
        <p>Dans ce projet, j'ai ??tudi?? les probl??mes qui freinent l'??lectrification du secteur automobile dans le monde, </p> 
		<p>comme les co??ts ??lev??s des batteries, la faible autonomie et les infrastructures de recharge insuffisantes.</p> 
		<p>J'ai ??galement compar?? les avantages et les inconv??nients des voitures ??lectriques et des voitures diesel en</p>  
		<p>termes de performance, d'empreinte carbone et de co??ts d'exploitation. J'ai ensuite utilis?? des outils de mod??lisation</p> 
         <p> et de simulation pour analyser et mod??liser les composants de la transmission ??lectrique (drivetrain) ,</p> 
		  <p>d'une voiture ??lectrique tels que le moteur ??lectrique, l'inverseur de fr??quence et la transmission. </p> 
		  <p> J'ai simul?? les performances de ces composants sous diff??rentes conditions de conduite pour ??valuer leur efficacit?? ??nerg??tique.</p> 
		 , <p>2022 EHTP</p>
           <img src="https://substance.etsmtl.ca//wp-content/uploads/2015/09/schema-THSeAF1.jpg" class="image">
	  </div>
	  	 <div>
	  <h3>Optimisation de la performance de la machine asynchrone via la commande vectorielle</h3>
        <p>Dans ce projet, j'ai ??tudi?? la commande de machine asynchrone en utilisant un onduleur autonome. Tout d'abord, j'ai effectu?? la mod??lisation de la machine asynchrone en r??gime transitoire, ce qui m'a permis de comprendre les caract??ristiques dynamiques de la machine. J'ai utilis?? des techniques de simulation pour visualiser les diff??rents comportements de la machine en fonction de diff??rents param??tres.

Ensuite, j'ai impl??ment?? la commande vectorielle pour commander la machine asynchrone. La commande vectorielle est une m??thode de commande de moteur qui permet d'optimiser les performances de la machine en utilisant des algorithmes de contr??le avanc??s. Cette technique permet de contr??ler la vitesse et le couple du moteur en temps r??el, ce qui est essentiel pour garantir une performance optimale de la machine.

L'impl??mentation de la commande vectorielle a n??cessit?? une compr??hension approfondie de la th??orie de la commande de moteur et des algorithmes de contr??le avanc??s. J'ai utilis?? des outils tels que Matlab pour d??velopper et tester les algorithmes de contr??le. Les r??sultats ont montr?? une am??lioration significative des performances de la machine, en termes de pr??cision de vitesse et de couple.

En conclusion, ce projet a ??t?? tr??s enrichissant pour moi en termes de d??veloppement de comp??tences en mod??lisation et en commande de machine. J'ai acquis une connaissance approfondie de la machine asynchrone et des diff??rentes techniques de commande disponibles. Je suis fier des r??sultats obtenus et je suis convaincu que ces connaissances seront utiles pour mes futurs projets dans ce domaine.</p>
           <img src="https://upload.wikimedia.org/wikipedia/commons/c/c4/Vector_control_three-phase_AC-Motor_fr.svg" class="image">
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
      <p>Copyright ?? 2023 Lakbir Elmadani</p>
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

