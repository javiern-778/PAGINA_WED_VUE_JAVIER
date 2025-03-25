<script>
export default {
  name: "Estilos",
};
</script>

<template>
  <div class="container">
    <div class="card">
      <h1>Bienvenido a nuestra página de Videojuegos</h1>
      <p>
        "Descubre los videojuegos más populares, adquiere tus títulos preferidos
        y mantente actualizado con las últimas novedades del mundo gamer.
        ¡Sumérgete en juegos como Fortnite, Apex Legends, Call of Duty y muchos
        más!"
      </p>
    </div>
  </div>
</template>

<style scoped>
/* Cambiar el fondo de toda la página */
body {
  font-family: 'Arial', sans-serif;
  background-color: #3a486e !important; /* Fondo azul oscuro */
  color: #ffffff; /* Texto en blanco */
  margin: 0;
  padding: 0;
  text-align: center;
}

/* Diseño del título */
h1 {
  font-size: 3rem;
  color: #e94560; /* Título en rosa */
  font-family: 'Open Sans', sans-serif;
  margin-bottom: 20px;
}

/* Estilos del párrafo */
p {
  font-size: 1.25rem;
  color: #f0f0f0; /* Texto en gris claro para mejor visibilidad */
  line-height: 1.6;
  max-width: 800px;
  margin: 10px auto;
}

/* Tarjeta con fondo más oscuro */
.card {
  background-color: #2c3654; /* Un tono más oscuro para destacar la tarjeta */
  border-radius: 10px;
  box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
  padding: 30px;
  color: #fff; /* Texto blanco dentro de la tarjeta */
  margin-top: 50px;
}

/* Botón personalizado */
.btn-custom {
  color: #fff;
  background-color: #e94560; /* Botón en rosa */
  padding: 10px 20px;
  font-size: 1.1rem;
  border-radius: 5px;
  margin-top: 20px;
  border: none;
  cursor: pointer;
}

.btn-custom:hover {
  background-color: #ff5277; /* Hover en rosa más claro */
}
</style>
