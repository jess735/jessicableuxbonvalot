<template>
<div class="cadre">
  <h1 class="onglet">~ A propos de moi ~</h1>

  <div class="container-lg apropos">
            <div class="row">
              <div class="col">
               <h3 class="description"> | Qui suis-je ?</h3><br>
                <p class="text1">Je suis Jessica Bleux Bonvalot, freelance, jeune entrepreneur basée sur CAEN. Je vous conseille et vous accompagne dans le succès de vos projets digitaux.
                Je suis développeuse back-end et front-end ( VueJS / NodeJS / MySql / HTML / CSS / JavaScript) depuis 2020.
                De mon parcours atypique et aux expériences multiples, j’ai su acquérir une certaine pluridisciplinarité venant ainsi compléter mon profil.
                Ma recette au quotidien – curiosité, passion et engagement sur les projets, une bonne dose de connaissances techniques, voilà ce que j’inclus dans chacune de mes prestations.</p>
              </div>
              <div class="col align-self-end profil">
                <img src="../assets/profil.jpg" class="photopro" alt="photo profil">
              </div>
            </div>
            <div class="row">
               <div class="col logo">
                <img src="../assets/css.png" class="photo" alt="logo css">
                <img src="../assets/html.jpg" class="photo" alt="logo html">
                <img src="../assets/js.png" class="photo" alt="logo js">
                <img src="../assets/bootstrap.png" class="photo" alt="logo bootstrap">
              </div>
              <div class="col align-self-end">
               <h3 class="description">| Ce que je fais...</h3><br>
                <p class="text1">Que ce soit pour une création de site web, une refonte, une création de boutique en ligne/e-commerce, distinguez-vous de vos concurrents en proposant la meilleure expérience digitale à vos utilisateurs.
                Je suis à votre écoute pour évaluer vos besoins, vos contraintes et ainsi établir ensemble une stratégie commerciale sur internet performante et efficace.
                En effet, concevoir un site internet est une chose, le mettre en avant, le rendre visible sur la toile en est une autre.
                Soyez donc bien accompagné sur votre référencement naturel, SEO, l’analyse et le webmarketing.
                Que vous soyez une entreprise, une agence ou un particulier, je saurai répondre à vos besoins en développement et/ou en design et stratégie de référencement naturel.</p>
              </div>
            </div>
          </div>
</div>
</template>

<script>
export default {
    name: 'presentation'
}
</script>

<style>
.onglet{
    font-family: 'Nothing You Could Do', cursive;
    font-size: 2.5em;
    text-shadow: -2px 0 black, 0 2px black,
    2px 0 white, 0 -2px white;
    font-weight: bold;
    text-align: center;
    color: #bb1d7c;
    padding: 2%;
}
.description{
  font-family: 'Lobster Two', cursive;
    font-size: 1.8em;
    color: black;
    text-decoration: underline;
}
.text1{
  text-align: justify;
  font-size: 1em;
  color: black;
  font-weight: 500;
}
.cadre{
  background-image: url(../assets/line.png);
  background-attachment: fixed, no-repeat;
}
.photopro{
  box-shadow: 2px 2px 20px rgb(192, 70, 176);
  border-radius: 25px;
  margin-left: 30%;
  width: 40%;
}
.photo{
  width: 30%;
  border-radius: 25px;
  margin: 2%;
}
.logo{
  padding-top: 5%;
  margin-left: 7%;
}


</style>