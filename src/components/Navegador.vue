<script>
export default {
  name: "Navegador",
};
</script>

<template>
  <head>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="description" content="Explora los videojuegos más populares, compra tus títulos favoritos y mantente al tanto de las últimas novedades en el mundo de los videojuegos. ¡Disfruta de juegos como Fortnite, Apex Legends, Call of Duty, entre otros!">
        <title>Videojuegos</title>
        <link rel="stylesheet" href="estilos/estilos.css">
      </head>
      
</head>
  <div>
    <!-- Barra de navegación -->
    <nav class="navbar navbar-expand-lg bg-body-tertiary" data-bs-theme="dark">
      <div class="container-fluid">
        <a class="navbar-brand" href="#" 
          style="font-size: 3rem; font-family: 'Arial', sans-serif; font-weight: bold; color: red; text-shadow: 2px 2px 5px black;">
          GAMES
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav me-auto">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#" style="font-size: 2rem;">INICIO</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown1" role="button" data-bs-toggle="dropdown"
                aria-expanded="false" style="font-size: 1.75rem;">
                Nuevo y destacable
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown1">
                <li><a class="dropdown-item" href="#" style="font-size: 1.5rem;">Lo más vendido</a></li>
                <li><a class="dropdown-item" href="#" style="font-size: 1.5rem;">Lo más jugado</a></li>
                <li><a class="dropdown-item" href="#" style="font-size: 1.5rem;">Novedades</a></li>
                <li><a class="dropdown-item" href="#" style="font-size: 1.5rem;">Próximos lanzamientos</a></li>
                <li><hr class="dropdown-divider"></li>
                <li><a class="dropdown-item" href="#" style="font-size: 1.5rem;">Noticias y actualizaciones</a></li>
                <li><a class="dropdown-item" href="#" style="font-size: 1.5rem;">Próximos eventos</a></li>
              </ul>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown2" role="button" data-bs-toggle="dropdown"
                aria-expanded="false" style="font-size: 1.75rem;">
                Categorías
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown2">
                <li><a class="dropdown-item" href="#" style="font-size: 1.5rem;">Acción</a></li>
                <li><a class="dropdown-item" href="#" style="font-size: 1.5rem;">Arcade</a></li>
                <li><a class="dropdown-item" href="#" style="font-size: 1.5rem;">Aventura</a></li>
                <li><a class="dropdown-item" href="#" style="font-size: 1.5rem;">Estrategia</a></li>
                <li><a class="dropdown-item" href="#" style="font-size: 1.5rem;">Rol</a></li>
                <li><a class="dropdown-item" href="#" style="font-size: 1.5rem;">Simulación</a></li>
              </ul>
            </li>
          </ul>
          
          <!-- Buscador -->
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Buscar" aria-label="Search" style="font-size: 1.1rem;">
            <button class="btn btn-outline-light" type="submit" style="font-size: 1.1rem;">Buscar</button>
          </form>
        </div>
      </div>
    </nav>
  </div>
</template>

<style scoped>
body {
  font-family: 'Arial', sans-serif;
  background-color: #1a1a2e;
  color: #e94560;
  margin: 0;
  padding: 0;
  text-align: center;
}
</style>


