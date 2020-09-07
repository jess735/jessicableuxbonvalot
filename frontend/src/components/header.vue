<template>
  <div>

      <ul class="nav">
          <li class="btn btn-outline-secondary btn-nav"><router-link to='/'>Accueil 🏠</router-link></li>
          <li class="btn btn-outline-secondary btn-nav"><router-link to='/presentation'>A propos de moi 🌺</router-link></li>
          <li class="btn btn-outline-secondary btn-nav"><router-link to='/expertises'>Expertises 💻</router-link></li>
          <li class="btn btn-outline-secondary btn-nav"><router-link to='/contact'>Contact ☎</router-link></li>
      </ul>
  </div>
</template>

<script>
export default {
        name: 'header'
}
</script>

<style>
.nav{
    margin: auto;
    margin-top: 1%;
}
.btn-nav{
    margin: 0.7%;
}
.btn-nav a {
    color: rgb(168, 21, 112);
    font-family:'Lobster Two', cursive;
    font-size: 1.2em;
}
.btn-nav a:hover {
    text-decoration: none;
    color:rgb(168, 21, 112);

}

</style>