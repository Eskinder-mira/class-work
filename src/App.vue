<template>
 
  <div class="cover-container d-flex w-100 h-100 p-3 mx-auto flex-column">
    <header class="masthead mb-auto">
      <div class="inner">
        <nav class="nav nav-masthead justify-content-center">
          <a class="nav-link active mx-2" href="#"> {{ $t('home') }} </a>
          <a class="nav-link mx-2" href="mailto:eskesophe@gmail.com">Contact</a>
          <a @click="$i18n.locale = 'en'" class="mx-2"> <img  src="@/assets/Kingdom.png" height="15px" style="width: 20px"></a>
          <a @click="$i18n.locale = 'fr'" class="mx-2"> <img  src="@/assets/France.png" height="15px" style="width: 20px"></a>
        </nav>
      </div>
    </header>
    
    <main role="main" class="inner cover">
      <div class="px-4  my-4 bg-white" id="headstyle">
      <h1 id="metal" class="cover-heading mt-3">Eskindir Sophonias</h1>
      <p class="text-dark">
        Place du tunnel 5 <br>
        1005 Lausanne <br>
        <a style="color: black;" href="mailto:eskesophe@gmail.com">eskesophe@gmail.com</a><br>
        079 838 01 71
      </p></div>
      <h2 class="px-4 bg-white text-dark" style="border-radius: 2px;"> {{ $t('experience') }} </h2>
      <p> <b>{{ $t('experience.fablab.time') }}:</b> {{ $t('experience.fablab.description') }}</p>
      <p> <b>2018:{{ $t('assistant.departement.electricite')}}</b>,{{ $t('Festival.Vevey')}}</p>
       <p> <b>2017:{{ $t('Assistant.laboratoire')}}</b>,{{ $t('Tests.machines')}}</p>
        <p> <b>2010-12:{{ $t('Employe')}}</b>,{{ $t('Addis.Ababa')}}</p>
      <h2 class="px-4 bg-white text-dark" style="border-radius: 2px;"> {{ $t('Education')}} </h2>
       <p> <b>2019:{{ $t('Powercoders')}}</b>,{{ $t('Programmation.Internet')}}</p>
       <p> <b>2017:{{ $t('Cap.Horizon')}}</b>,{{ $t('Cours.francais')}}</p>
      <p><b>2016:{{ $t('Pole.Sud')}}</b>,{{ $t(' Cours.français')}}</p>
       <p><b>2013-15:{{ $t('Evam')}}</b>,{{ $t('Renens.Cours.français')}}</p>
       <p><b>2013-15:{{ $t('obligatoire')}}</b>,{{ $t('Ethiopie')}}</p>
      <hr class="my-4">
      <div class="row">
        <div class="side">
          <div> Html/Css</div>
        </div>
        <div class="middle">
          <div class="bar-container">
            <div class="bar-5"></div>
          </div>
        </div>
        <div class="side right">
          <div>5</div>
        </div>
        <div class="side">
          <div>Sketch-Up</div>
        </div>
        <div class="middle">
          <div class="bar-container">
            <div class="bar-4"></div>
          </div>
        </div>
        <div class="side right">
          <div>5</div>
        </div>
        <div class="side">
          <div>Bootstrap</div>
        </div>
        <div class="middle">
          <div class="bar-container">
            <div class="bar-3"></div>
          </div>
        </div>
        <div class="side right">
          <div>4</div>
        </div>
        <div class="side">
          <div>JavaScript</div>
        </div>
        <div class="middle">
          <div class="bar-container">
            <div class="bar-2"></div>
          </div>
        </div>
        <div class="side right">
          <div>3.5</div>
        </div>
        <div class="side">
          <div>PHP</div>
        </div>
        <div class="middle">
          <div class="bar-container">
            <div class="bar-1"></div>
          </div>
        </div>
        <div class="side right">
          <div>3</div>
        </div>
        <div class="side">
          <div>Ms-office</div>
        </div>
        <div class="middle">
          <div class="bar-container">
            <div class="bar-1"></div>
          </div>
        </div>
        <div class="side right">
          <div>4</div>
        </div>
        <div class="side">
          <div>Blender  </div>
        </div>
        <div class="middle">
          <div class="bar-container">
            <div class="bar-0"></div>
          </div>
        </div>
        <div class="side right">
          <div>3</div>
        </div>
      </div>
      <hr class="my-4">
       <p>{{ $t('Langue.maternelle')}} Amharic</p>
       <p>{{ $t('France')}}  niveau B1</p>
       <p>{{ $t('anglais')}}  niveau B2</p>
      <hr class="my-4">
      <div class="my-4">
     <div class="flooter">
       <h2>{{ $t('References')}}</h2>
      <p>Christine Theround, Bénévole à Pouvoir d'agir (chrstherond@yahoo.com)</p>
      <p>Daniel Peppicelli, Ingénieur en informatique EPFL (daniel.peppicelli@gmail.com)</p></div></div>
    </main>
    <br>
    <footer class="mastfoot mt-auto">
    </footer>
  </div>

</template>

<script>
export default {
  name: 'App',
  }
</script>

<style>

/* Links */
a,
a:focus,
a:hover {
  color: #fff;
}

/* Custom default button */
.btn-secondary,
.btn-secondary:hover,
.btn-secondary:focus {
  color: #333;
  text-shadow: none; /* Prevent inheritance from `body` */
  background-color: #fff;
  border: .05rem solid #fff;
}

hr{
  box-shadow: 5px 2px 3px 3px rgba(0,0,0,0.2);
  background-color: rgb(192, 157, 0);
  width: 80%;
}

#headstyle{
  box-shadow: 5px 5px 5px 10px rgba(0,0,0,0.2);
  border-radius: 2px; border-top-left-radius: 30px;
  border-top-right-radius: 178px;
    border-bottom-left-radius: 30px;
  border-bottom-right-radius: 178px;
  background: linear-gradient(to top right, #f7e0eb -4%, #faf3df 95%);
  border-bottom: 3px solid whitesmoke;
border-top: 2px solid whitesmoke;
border-left: 3px solid rgb(235, 233, 233);
border-right: 4px solid white;

}
/*
 * Base structure
 */

html,
body {
  height: 100%;
  background-color: #232F3E;
}

body {
  display: -ms-flexbox;
  display: flex;
  color: #fff;
  text-shadow: 0 .05rem .1rem rgba(0, 0, 0, .5);
}

.cover-container {
  max-width: 42em;
}


/*
 * Header
 */
.masthead {
  margin-bottom: 2rem;
}

.masthead-brand {
  margin-bottom: 0;
}

.nav-masthead .nav-link {
  padding: .25rem 0;
  font-weight: 700;
  color: rgba(255, 255, 255, .5);
  background-color: transparent;
  border-bottom: .25rem solid transparent;
}

.nav-masthead .nav-link:hover,
.nav-masthead .nav-link:focus {
  border-bottom-color: rgba(255, 255, 255, .25);
}

.nav-masthead .nav-link + .nav-link {
  margin-left: 1rem;
}

.nav-masthead .active {
  color: #fff;
  border-bottom-color: #fff;
}

@media (min-width: 48em) {
  .masthead-brand {
    float: left;
  }
  .nav-masthead {
    float: right;
  }
}


/*
 * Cover
 */
.cover {
  padding: 0 1.5rem;
}
.cover .btn-lg {
  padding: .75rem 1.25rem;
  font-weight: 700;
}


/*
 * Footer
 */
.mastfoot {
  color: rgba(37, 37, 37, 0.918);
}

img{
  border-radius: 1px;
}

.flooter{
  box-shadow: 5px 5px 5px 10px rgba(0,0,0,0.2);
  background-color: rgb(230, 230, 230);
   color: black;padding: 20px;
     border-radius: 10px; 
     border-bottom: 3px solid whitesmoke;
     border-top: 2px solid whitesmoke;
     border-left: 3px solid rgb(235, 233, 233);
     border-right: 4px solid white;
}


/* Three column layout */
.side {
  font-size: 13px;
  float: left;
  width: 15%;
  margin-top:10px;
}
@media screen and (max-width: 601px) {
  .side {
    font-size: 11px;
  }
}
.middle {
  
  margin-top:10px;
  float: left;
  width: 70%;
}

/* Place text to the right */
.right {
  text-align: right;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* The bar container */
.bar-container {
  border-bottom: 1px solid rgb(197, 197, 197);
  border-top: 1px solid rgb(231, 231, 231);
  border-left: 2px solid rgb(235, 233, 233);
  border-right: 2px solid rgb(197, 197, 197);
  border-radius: 10px;
  width: 100%;
  background-color: #f1f1f1;
  text-align: center;
  color: white;
}

/* Individual bars */
.bar-5 {width: 96%;  border-radius: 10px; height: 18px; background-color: rgb(0, 255, 8);}
.bar-4 {width: 90%;   border-radius: 10px;height: 18px; background-color: rgb(0, 202, 51);}
.bar-3 {width: 80%;  border-radius: 10px; height: 18px; background-color: #14aa00;}
.bar-2 {width: 74%;   border-radius: 10px;height: 18px; background-color: #1ba500;}
.bar-1 {width: 75%;   border-radius: 10px;height: 18px; background-color: #0a7001;}
.bar-0 {width: 60%;   border-radius: 10px;height: 18px; background-color: #0e4600;}

/* Responsive layout - make the columns stack on top of each other instead of next to each other */
@media (max-width: 400px) {
  .side, .middle {
    width: 100%;
  }
  .right {
    display: none;
  }
}

#metal{
  text-align: left;
  font-size:2em;
  text-transform: uppercase;
  letter-spacing: 2px;
  background:linear-gradient(#262626,#eaeaea,#262626);
  -webkit-background-clip: text;
  color:transparent;
}

</style>
