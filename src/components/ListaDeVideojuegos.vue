<template>
  <div class="row">
    <div class="col-md-12">
      <div class="card mt-4">
        <div style="background-color:#E94560;" class="card-header">
          <h2 style="color: beige; font-size: 40px; font-family: 'Open Sans', sans-serif; text-transform: uppercase; letter-spacing: 3px; text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.5);">
            Lista de videojuegos
          </h2>
        </div>
        <div class="card-body">
          <div class="row">
            <div class="col-md-4" v-for="(game, index) in games" :key="index">
              <div class="card mt-4">
                <img :src="game.image" class="card-img-top" style="object-fit: cover; width: 100%; height: 350px;" :alt="game.name">
                <div class="card-body">
                  <h5 class="card-title" style="text-align: left;">{{ game.name }}</h5>
                  <p class="card-text" style="text-align: left;">{{ game.description }}</p>
                  <p style="color:aliceblue;text-align: left;">{{ game.rating }} | {{ game.size }} | {{ game.price }}</p>
                  <button class="btn w-100" style="background-color: #E94560; color: white;">{{ game.buttonText }}</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// Importa las imágenes desde la carpeta 'src/assets'
import PUBGImage from '@/assets/pubg.jpg';  // Ajusta la ruta según la ubicación
import CODImage from '@/assets/COD.jpg';    // Ajusta la ruta según la ubicación
import FortniteImage from '@/assets/fortnite.jpg';  // Ajusta la ruta según la ubicación
import ApexImage from '../assets/apex-legends.jpg';  // Ajusta la ruta según la ubicación
import DeltaForceImage from '@/assets/Delta-force.jpg';  // Ajusta la ruta según la ubicación
import GearsImage from '@/assets/gears.jpg';  // Ajusta la ruta según la ubicación

export default {
  data() {
    return {
      games: [
        {
          name: 'PUBG',
          description: 'Acción, Disparos',
          rating: '4.0 ★',
          size: '40 GB',
          price: 'Gratis',
          buttonText: 'Obtener ahora',
          image: PUBGImage
        },
        {
          name: 'CALL OF DUTY MODERN WARFARE III',
          description: 'Juego de disparos de acción',
          rating: '4.4 ★',
          size: '234.9 GB',
          price: 'MXN$1,399',
          buttonText: 'Comprar ahora',
          image: CODImage
        },
        {
          name: 'Fortnite',
          description: 'Acción, Disparos',
          rating: '4.7 ★',
          size: '99 GB',
          price: 'Gratis',
          buttonText: 'Obtener ahora',
          image: FortniteImage
        },
        {
          name: 'Apex Legends',
          description: 'Acción',
          rating: '4.2 ★',
          size: '75 GB',
          price: 'Gratis',
          buttonText: 'Obtener ahora',
          image: ApexImage
        },
        {
          name: 'Delta Force',
          description: 'Aventura, multijugador masivo',
          rating: '3.9 ★',
          size: '88 GB',
          price: 'Gratis',
          buttonText: 'Obtener ahora',
          image: DeltaForceImage
        },
        {
          name: 'Gears',
          description: 'Disparos',
          rating: '4.5 ★',
          size: '88 GB',
          price: 'MXN$499',
          buttonText: 'Comprar ahora',
          image: GearsImage
        }
      ]
    };
  }
};
</script>

<style scoped>
.card-img-top {
  object-fit: cover;
  width: 100%;
  height: 250px;
}

.card-title {
  text-align: left;
}

.card-text {
  text-align: left;
  color: aliceblue;
}

.card-body {
  background-color: #2C3E50;
  color: white;
}
</style>