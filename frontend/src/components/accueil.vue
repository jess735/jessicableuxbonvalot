<template>
<div class="back">

  <h1 class="titre"> ~ Jessica Bleux Bonvalot ~</h1>
<div class="intro">Développeuse Web Freelance à Caen<br> Donnez vie à vos projets !<br></div> 


</div>
</template>

<script>
export default {
        name: 'accueil'
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Lobster+Two:ital@1&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Nothing+You+Could+Do&display=swap');
.intro{
    font-family: 'Lobster Two', cursive;
    font-size: 1.8em;
    text-align: center;
    font-weight: bolder;
    color: black;
    background-color: rgba(128, 128, 128, 0.555);
    border-radius: 25px;
}
.titre{
    font-family: 'Nothing You Could Do', cursive;
    font-size: 2.8em;
    text-shadow: -2px 0 black, 0 2px black,
    2px 0 white, 0 -2px white;
    font-weight: bold;
    text-align: center;
    color: #bb1d7c;
    padding: 3%;
    margin-top: 6%;
}

.back{
  background-image: url(../assets/desk.jpg);
  background-attachment: fixed, no-repeat;
  width: 100%;
  height: 60%;
  padding: 3%;
  margin-top: 2%;
  box-shadow: 2px 2px 20px rgb(192, 70, 176);
}
</style>