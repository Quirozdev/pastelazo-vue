<template>
  <div id="contenedorInformacion">
    <h1>Sobre nosotros</h1>
    <p>
      Somos una pastelería que busca brindar los pasteles más deliciosos y con
      el mejor precio en Hermosillo.
    </p>
    <h2>Dirección</h2>
    <p>
      Topahue entre 12 de Octubre y De las Americas, colonia Jacinto López,
      número interior 365, código postal 83105, Hermosillo, Sonora, México.
    </p>
    <h2>Teléfono</h2>
    <!-- (Teléfono inventado) -->
    <p>6623092346</p>
    <h2>Horarios de atención</h2>
    <p>
      Lunes a viernes de 7:00 AM a 8:00 PM<br />Sábado de 10:00 AM a 9:00 PM
    </p>
  </div>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
}

body {
  text-align: center;
  background-color: coral;
}

h1,
h2 {
  color: crimson;
}

p {
  font-size: 20px;
  color: saddlebrown;
}

h1,
h2,
p {
  margin: 10px;
}

/* para centrar el logo y rellenar el fondo de ese rectangulo*/
#contenedorLogo {
  text-align: center;
  background-color: rgb(255, 174, 201);
}

a {
  font-size: 18px;
}
</style>
