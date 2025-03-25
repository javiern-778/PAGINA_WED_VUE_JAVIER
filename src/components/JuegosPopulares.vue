<template>
  <!-- Inicio del row principal -->
  <div class="row">
    <!-- Inicio del col-md-6 para los juegos más populares -->
    <div class="col-md-6">
      <div class="card mt-4 ms-0"> <!-- ms-0 es para eliminar el margen a la izquierda -->
        <div class="card-header">
          <h1 class="titulo-general">  
            VIDEOJUEGOS MÁS POPULARES  
          </h1>
        </div>
        <div class="card-body">
          <!-- Inicio de carrusel de reproducción automática -->
          <div id="carouselExampleAutoplaying" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-inner">
              <!-- Primer juego: Fortnite -->
              <div class="carousel-item active">
                <img src="@/assets/fortnite.jpg" class="d-block w-100" alt="Fortnite">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Fortnite</h5>
                  <p>Acción, Disparos - Gratis</p>
                </div>
              </div>
              <!-- Segundo juego: Apex Legends -->
              <div class="carousel-item">
                <img src="@/assets/apex-legends.jpg" class="d-block w-100" alt="Apex Legends">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Apex Legends</h5>
                  <p>Acción - Gratis</p>
                </div>
              </div>
              <!-- Tercer juego: PUBG -->
              <div class="carousel-item">
                <img src="@/assets/pubg.jpg" class="d-block w-100" alt="PUBG">
                <div class="carousel-caption d-none d-md-block">
                  <h5>PUBG</h5>
                  <p>Acción, Disparos - Gratis</p>
                </div>
              </div>
              <!-- Cuarto juego: Gears -->
              <div class="carousel-item">
                <img src="@/assets/Gears.jpg" class="d-block w-100" alt="Gears">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Gears</h5>
                  <p>Disparos - MXN$499</p>
                </div>
              </div>
              <!-- Quinto juego: Call of Duty -->
              <div class="carousel-item">
                <img src="@/assets/COD.jpg" class="d-block w-100" alt="Call of Duty">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Call of Duty Modern Warfare III</h5>
                  <p>Juego de disparos de acción - MXN$1,399</p>
                </div>
              </div>
            </div>
            <!-- Botón para ir al anterior juego -->
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying"
              data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <!-- Botón para ir al siguiente juego -->
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying"
              data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>
          <!-- Fin del carrusel de reproducción automática -->
        </div>
      </div>
    </div>
    <!-- Fin del col-md-6 -->
  </div>
  <!-- Fin del row principal -->
</template>

<style scoped>
.card-header {
  background-color: #E94560;
}

.titulo-general {
  color: beige;
  font-size: 40px;
  font-family: 'Open Sans', sans-serif;
  text-transform: uppercase;
  letter-spacing: 3px;
  text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.5);
  text-align: center;
}

.card {
  width: 100%; /* Ajustado para que ocupe todo el espacio disponible */
  background-color: #3a486e !important; /* Azul oscuro para el fondo de la tarjeta */
}

.juegos-populares {
  margin-top: 20px; /* Corregido, ajusta la separación según se necesite */
}

/* Esto alinea la tarjeta a la izquierda */
.ms-0 {
  margin-left: -10 !important;
}
</style>
