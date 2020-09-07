<template>

<div class="cadre">

  <h1  class="onglet">~ Contact ~</h1>

  <hr>
  <div class="container-md">
        <form>
            <div class="form-row">
              <div class="col-md-6 mb-3">
                <label for="validationServer">Prénom</label>
                <input type="text" class="form-control" id="validationServer01" placeholder="Votre Prénom" required>
              </div>

              <div class="col-md-6 mb-3">
                <label for="validationServer">Nom</label>
                <input type="text" class="form-control" id="validationServer02" placeholder="Votre Nom" required>
              </div>

              <div class="col-md-12 mb-3">
                <label for="validationServer">Adresse Mail</label>
                <input type="text" class="form-control" id="validationServer02" placeholder="Votre adresse mail" required>
              </div>
            </div>

            <div class="form-row">
              <div class="col-md-12 mb-3">
                <label for="validationServer">Votre Ville</label>
                <input type="text" class="form-control" id="validationServer03" placeholder="Votre ville" required>
              </div>
            </div>
                <div class="mb-3">
                  <label for="Textarea">Votre Message</label>
                  <textarea class="form-control"  rows="3" placeholder="Quelle est votre demande ?" required></textarea>
                </div>

            <button class="btn btn-outline-secondary btn-validate" type="submit">Envoyer</button>
            
        </form>
  </div>
</div>

</template>

<script>
export default {
        name: 'contact'
}
</script>

<style>
hr{
  border: 1px solid rgb(156, 23, 68);
  width: 80%;

}
.btn-validate {
    color: rgb(168, 21, 112);
    font-family:'Lobster Two', cursive;
    font-weight: bold;
    font-size: 1.2em;
    margin-left: 80%;
}
.btn-validate:hover {
    text-decoration: none;
    color:rgb(168, 21, 112);
}
label, input, textarea{
  font-family:'Lobster Two', cursive;
  font-size: 1.2em;
}
</style>