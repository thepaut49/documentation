<template>
<div class="CV">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <h1>CV</h1>
  <section>
    <h2>Qui suis-je ?</h2>
    <p>Je m'appelle Antoine Thépaut, je suis né en France en 1992. J'habite à Nantes.
      Je suis développeur web.
    </p>
  </section>

  <section>
    <h2>Expériences professionnelles</h2>

    <div class="formation">
      <div class="logo"><img src="../assets/logo-sopra-banking.png" width="100%"/></div>  
      <div class="nom-formation">
        <p>Ingénieur d’études</p>
        <p>Nantes</p>
        <p>Depuis septembre 2019</p>
        <div class="description-formation">
          <p>Membre de l'équipe R&D Cassiopae</p>
        </div>
        <br/>
        <p>Ingénieur débutant Java ee</p>
        <p>Rodez</p>
        <p>Novembre 2016 - Septembre 2019</p>
        <div class="description-formation">
          <p>Maintenance d'un progiciel bancaire de gestion des échanges et transactions internationales
- Réalisation de correctifs via l’outil Jira
- Réponses aux interrogations des utilisateurs
- Réalisation de scénarios de test lancer quotidiennement via Jenkins</p>
        </div>
      </div>
    </div> 
    <br/>

    <div class="formation">
      <div class="logo"><img src="../assets/logo-adaming.png" width="100%"/></div>  
      <div class="nom-formation">
        <p>Ingénieur étude et développement java ee chez Adaming</p>
        <p>Rodez</p>
        <p>Avril 2016 - Novembre 2016</p>
        <div class="description-formation">
          <p>En mission chez Sopra Banking Software pour renforcer les équipes de développement sur le site de Rodez. </p>
        </div>
      </div>
    </div> 
    <br/>

    <div class="formation">
      <div class="logo"><img src="../assets/logo-geonx.png" width="100%"/></div>  
      <div class="nom-formation">
        <p>Ingénieur calcul stagiaire</p>
        <p>Gosselies, Belgique</p>
        <p>Février 2015 - Septembre 2015</p>
        <div class="description-formation">
          <p>Réalisation de scripts python pour automatiser les tests de performances et de non régression lors des mises à jour du logiciel Morfeo Crack (logiciel de simulation numérique de procédés industriels).</p>
        </div>
      </div>
    </div> 
    <br/>
  </section>

  
  <section> 
    <h2>Formations</h2>

    <div class="formation">
      <div class="logo"><img src="../assets/logo-inti-formation.png" width="100%"/></div>  
      <div class="nom-formation">
        <p>Formation de reconversion pour devenir ingénieur d'étude et développement java EE</p>
        <p>Lille</p>
        <p>Février 2016 - Avril 2016</p>
        <div class="description-formation">
          <p>Programmation orientée object Java EE dans eclipse en utilisant les frameworks Java de références (Spring, JSF, Hibernate) <br/>
            Réalisation de webservice (Rest/SOAP)<br/>
            Initiation au langage Javascript<br/>
            Méthode d'architecture d'application Web java (UML, design patterns) 
          </p>
        </div>
      </div>
    </div>
    <br/>

    <div class="formation">
      <div class="logo"><img src="../assets/logo-univ-angers.png" width="100%"/></div>  
      <div class="nom-formation">
        <p>Master Ingénierie mathématiques option calcul scientifique</p>
        <p>Angers</p>
        <p>2013 - 2015</p>
        <div class="description-formation">
        <p>Apprentissage de la méthode des éléments finis,  des volumes finis et des différences finies <br/>
Initiation au C++, et au SQL<br/>
Pratique du parallélisme en Fortran 90 avec les librairies OpenMP, et MPI</p>
      </div>
      </div>
    </div>
    <br/>
    <div class="formation">
      <div class="logo"><img src="../assets/logo-univ-angers.png" width="100%"/></div>  
      <div class="nom-formation">
        <p>Licence Sciences, Technologies, Santé, Mention Mathématiques</p>
        <p>Angers</p>
        <p>2010 - 2013</p>
        <div class="description-formation">
          <p>Pratique d'outils de simulation numérique (Scilab) et de langages informatiques (Pascal, C, HTML/CSS) </p>
        </div>
      </div>
    </div> 
    <br/>
    <div class="formation">
      <div class="logo"><img src="../assets/logo-lycee-bergson.jpeg" width="100%" /></div>  
      <div class="nom-formation">
        <p>Baccalauréat Scientifique option mathématique</p>
        <p>Angers</p>
        <p>2010</p>
      </div>
    </div>      
  </section>

  <section>
    <h2>Mes compétences</h2>
    <h3>Langues</h3>
    <ul>
      <li>
        <label for="file">English : </label>
        <progress id="file" value="90" max="100"> 90% </progress>
      </li>

      <li>
        <label for="file">日本語 : </label>
        <progress id="file" value="60" max="100"> 60% </progress>
      </li>

      <li>
        <label for="file">Español : </label>
        <progress id="file" value="20" max="100"> 20% </progress>
      </li>

      <li>
        <label for="file">Deutsch : </label>
        <progress id="file" value="10" max="100"> 10% </progress>
      </li>
    </ul>

    <h3>Langage de programmation</h3>
    
    <h4>Java EE
      <span class="fa fa-star checked"></span>
      <span class="fa fa-star checked"></span>
      <span class="fa fa-star checked"></span>
      <span class="fa fa-star checked"></span>
      <span class="fa fa-star"></span>
    </h4>

    <ul>
      <li>Maven</li>
      <li>Spring</li>
      <li>Hibernate (ORM)</li>
      <li>JSF (Primefaces)</li>
      <li>JSP</li>
    </ul>

    <h4>Javascript
      <span class="fa fa-star checked"></span>
      <span class="fa fa-star checked"></span>
      <span class="fa fa-star checked"></span>
      <span class="fa fa-star"></span>
      <span class="fa fa-star"></span>
    </h4>
    <ul>
      <li>NodeJS</li>
      <li>VueJS</li>
    </ul>

    <h4>Html5 / Css3
        <span class="fa fa-star checked"></span>
        <span class="fa fa-star checked"></span>
        <span class="fa fa-star checked"></span>
        <span class="fa fa-star"></span>
        <span class="fa fa-star"></span>
    </h4>
    <ul>
      <li>
        
      </li>
    </ul>


    <h3>IDE</h3>
    <ul>
      <li>
        <label for="file">Eclipse : </label>
        <progress id="file" value="90" max="100"> 90% </progress>
      </li>

      <li>
        <label for="file">IntelliJ IDEA : </label>
        <progress id="file" value="60" max="100"> 60% </progress>
      </li>

      <li>
        <label for="file">Visual Studio Code : </label>
        <progress id="file" value="20" max="100"> 20% </progress>
      </li>
    </ul>
  </section>

  <section>
    <h2>Mes projets personnels</h2>
    <h3>Traducteur Japonais => Anglais</h3>
    <h4>Buts de l'application</h4>
      <ul>
        <li>Traduction mot à mot de phrase en japonais en anglais</li>
        <li>Liste et recherche de kanji</li>
        <li>Liste et recherche de mot de vocabulaire</li>
        <li>Clavier japonais</li>
      </ul>
    <h4>Technologies employées</h4>
    <ul>
      <li>Language de programmation utilisées : Java EE, Javascript</li>
      <li>Framework java utilisés : Spring, Hibernate (ORM), JSF (Primefaces)</li>
      <li>Base de données: MySQL</li>
    </ul>
    
    <h3>Mon site web personnel</h3>
    <h3>Application de gestion d'une entreprise</h3>
  </section>



  
</div>

  
</template>

<script>
export default {
  
}
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.CV {
  font-family: Garamond;
  text-align: left;
}

h1  {
  color: blue;
  text-align: center;
}

section {
  background-color: beige;
}


.logo { 
  grid-area: logo; 
  text-align: center;
  place-self: center;
}
.nom-formation { 
  font-weight: bold ;
  grid-area: nomFormation; 
  text-align: left;
}
.description-formation { 
  font-weight: 100 ;
  text-align: left;
}

.formation {
  display: grid;
  grid-template-columns: 10% 90%;
  grid-template-areas:
    'logo nomFormation nomFormation nomFormation nomFormation nomFormation nomFormation nomFormation';
  grid-gap: 10px;
  background-color: #2196F3;
  padding: 5px;
  
}

.formation > div {
  background-color: rgba(255, 255, 255, 0.8);
  padding: 5px 5px;
  font-size: 12px;
}

.checked {
  color: orange;
}


</style>