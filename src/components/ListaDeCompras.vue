<template>
  <div>
    <!-- Inicio de la tabla principal -->
    <br>
    <div class="col-md-12">
      <div class="card mt">
        <div class="card-header">
          <h2 class="titulo-general">
            Lista de compras
          </h2>
        </div>
        <div class="card-body">
          <table class="table-style">
            <thead class="table-dark">
              <tr>
                <th class="text-center">Imagen</th>
                <th class="text-center">Producto</th>
                <th class="text-center">Precio</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="text-center">
                  <img src="@/assets/COD.jpg" alt="COD" class="product-image" />
                </td>
                <td class="text-center">Call of Duty Modern Warfare III</td>
                <td class="text-center">MXN$1,399</td>
              </tr>
              <tr>
                <td class="text-center">
                  <img src="@/assets/Gears.jpg" alt="Gears" class="product-image" />
                </td>
                <td class="text-center">Gears</td>
                <td class="text-center">MXN$499</td>
              </tr>
              <tr>
                <td class="text-center">
                  <img src="@/assets/Fortnite.jpg" alt="Fortnite" class="product-image" />
                </td>
                <td class="text-center">Fortnite</td>
                <td class="text-center">Gratis</td>
              </tr>
              <tr>
                <td class="text-center">
                  <img src="@/assets/apex-legends.jpg" alt="Apex" class="product-image" />
                </td>
                <td class="text-center">Apex Legends</td>
                <td class="text-center">Gratis</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ListaDeCompras"
};
</script>

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
  text-shadow: 3px 3px 10px rgba(35, 29, 51, 0.5);
  text-align: center;
}

.card-body {
  padding: 20px;
}

.table-style {
  font-size: 1.2rem;
  width: 100%;
  margin: 0 auto;
  border-collapse: collapse;
}

.table-dark th, .table-dark td {
  padding: 15px;
  text-align: center;
}

.product-image {
  width: 350px; /* Mantén el tamaño original de las imágenes */
  height: auto;
  border-radius: 10px; /* Bordes redondeados para las imágenes */
}

/* Ajuste de la tarjeta */
.card {
  width: 80%;  /* Ajusta el ancho de la tarjeta */
  max-width: 800px;  /* Establece un tamaño máximo */
  background-color: #3a486e; /* Azul oscuro para la tarjeta */
  margin: 25; /* Centra la tarjeta */
  border-radius: 10px; /* Bordes redondeados */
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); /* Sombra de la tarjeta */
}

/* Estilos adicionales para las filas de la tabla */
tbody tr {
  background-color: #2C3E50;
  color: white;
}

tbody tr:hover {
  background-color: #34495E;
}
</style>