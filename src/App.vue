<script>
import Navegador from './components/Navegador.vue';
import Estilos from './components/Estilos.vue';
import JuegosPopulares from './components/JuegosPopulares.vue';
import ListaDeCompras from './components/ListaDeCompras.vue';
import ListaDeVideojuegos from './components/ListaDeVideojuegos.vue';
import Footer from './components/Footer.vue';

export default {
  components: {
    Navegador,
    Estilos,
    JuegosPopulares,
    ListaDeCompras,
    ListaDeVideojuegos,
    Footer
  }
};
</script>

<template>
  <div class="fondo"> <!-- Se agrega un contenedor con la clase fondo -->
    <!-- Navegador y Estilos -->
    <Navegador />
    <Estilos />
    <JuegosPopulares />
    
    <!-- Contenedor para las listas -->
    <div class="listas-container">
      <ListaDeCompras class="ListaDeCompras" />
      <ListaDeVideojuegos class="ListaDeVideojuegos" />
    </div>

    <Footer />
  </div>
</template>

<style>
/* Aplicar el fondo al body */
body {
  background-color: #3a486e !important; /* Fondo azul oscuro */
  color: white; /* Texto en blanco */
  margin: 0;
  padding: 0;
  font-family: 'Arial', sans-serif;
}

/* Asegurar que el fondo cubra toda la pantalla */
.fondo {
  background-color: #3a486e !important; /* Fondo azul oscuro */
  min-height: 100vh; /* Cubrir toda la pantalla */
  display: flex;
  flex-direction: column;
}

/* Contenedor que maneja la distribución de las listas */
.listas-container {
  display: flex; /* Usa Flexbox */
  justify-content: space-between; /* Espacio entre las listas */
  width: 100%; /* Ocupa todo el ancho disponible */
  gap: 20px; /* Espacio entre las listas */
  padding: 20px; /* Espaciado alrededor del contenedor */
  margin-top: -545px; /* Ajusta el valor según lo necesites */
}

/* Si necesitas controlar el tamaño de las listas */
.ListaDeVideojuegos {
  flex: 1; /* Ambas listas ocupan el mismo tamaño */
}
.ListaDeCompras {
  margin-top: 555px; /* Ajusta este valor según lo necesites */
}


</style>
