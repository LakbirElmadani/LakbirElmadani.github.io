
<html>
  <head>
    <title>Lakbir Elmadani</title>
    <link rel="stylesheet" href="styles.css">
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
    width: 300px;
    height: 200px;
}

   </style>
   
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#about">A propos</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
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
         <p>-Vérifier la sélectivité et la sensibilité des appareille de protection.</p>  <p>08/2021 - 09/2021, Er-Rich</p>
        <img src="https://media.licdn.com/dms/image/C4E16AQGNrd5YY6QWng/profile-displaybackgroundimage-shrink_350_1400/0/1657199515466?e=1680134400&v=beta&t=aU3sjMS6PoVFsnxht5zf06nJp2cCcR0Q8uEL2q9L6Og" class="image">
	  </div>
    </li>
    <li>
      <div>
        <h2>TIPE:Optimiser la puissance produite par une hydrolienne</h2>
        <p>-Implimenter MPPT pour extraire la plus possible de puissance.</p>
           <img src="https://cdn.futura-sciences.com/cdn-cgi/image/width=1520,quality=50,format=auto/sources/images/glossaire/HydroliennePaimpol_EDF.jpg" class="image">
	  </div>
    </li>
  </ul>
</section>

    <section id="contact">
      <h1>Contactez-moi</h1>
      <form>
        <label for="name">Nom:</label>
        <input type="text" id="name" name="name"><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br>
        <label for="message">Message:</label>
        <textarea id="message" name="message"></textarea><br>
        <input type="submit" value="Envoyer">
      </form>
    </section>

  </body>


</html>

