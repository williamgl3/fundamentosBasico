<template>
<div class="row mt-4">
      <div class="col-md-4">
        <div class="card equal-card">
          <img src="https://nupec.com/wp-content/uploads/2022/02/cat-watching-2021-08-26-15-42-24-utc.jpg" class="card-img-top" alt="Gato">
          <div class="card-body text-center">
            <p class="card-text">Información sobre gatos.</p>
            <button class="btn btn-warning">Más información</button>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card equal-card">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQlZWS4D8bkxRd3sMjza8fzi_bXAfP6isJcww&s" class="card-img-top" alt="Gato y Perro">
          <div class="card-body text-center">
            <p class="card-text">Los perros y gatos no se llevan bien.</p>
            <button class="btn btn-primary">Like</button>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card equal-card">
          <img src="https://vitakraft.es/wp-content/uploads/2020/12/Blog_HistoriaPerros-1110x600.jpg" class="card-img-top" alt="Perro">
          <div class="card-body text-center">
            <p class="card-text">Información sobre perros.</p>
            <button class="btn btn-danger">Acerca de</button>
          </div>
        </div>
      </div>
    </div>
</template>
<style scoped>
.container {
  background-color: #e3f2fd;
  padding: 20px;
  border-radius: 10px;
}
.card {
  background-color: #fff3cd;
}
.card h6, .card p {
  font-family: 'Arial', sans-serif;
}
.equal-card {
  height: 100%;
}
</style>
