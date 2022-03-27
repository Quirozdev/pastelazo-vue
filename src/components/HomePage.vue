<template>
  <header>
    <img
      src="../assets/img/logoPastelazo.png"
      alt="Logo de Pastelazo"
      width="180px"
      id="logo"
    />
    <h1>Pasteleando pasteles pastelosos</h1>
  </header>
  <h2>Sabores disponibles</h2>
  <table>
    <tr>
      <th>Ilustración</th>
      <th>Sabor</th>
      <th>Precio</th>
    </tr>
    <tr>
      <td>
        <img
          src="../assets/img/pastelChocolate.jpg"
          alt="Pastel sabor a chocolate"
          height="120px"
        />
      </td>
      <td>Chocolate</td>
      <td>$400 pesos</td>
    </tr>
    <tr>
      <td>
        <img
          src="../assets/img/pastelVainilla.jpg"
          alt="Pastel sabor a vainilla"
          height="120px"
        />
      </td>
      <td>Vainilla</td>
      <td>$400 pesos</td>
    </tr>
    <tr>
      <td>
        <img
          src="../assets/img/pastelFresa.jpg"
          alt="Pastel sabor a fresa"
          height="120px"
        />
      </td>
      <td>Fresa</td>
      <td>$400 pesos</td>
    </tr>
    <tr>
      <td>
        <img
          src="../assets/img/pastelLimon.jpg"
          alt="Pastel de limón"
          height="120px"
        />
      </td>
      <td>Limón</td>
      <td>$385 pesos</td>
    </tr>
    <tr>
      <td>
        <img
          src="../assets/img/pastelOreo.jpg"
          alt="Pastel de galleta Oreo"
          height="120px"
        />
      </td>
      <td>Galleta Oreo</td>
      <td>$550 pesos</td>
    </tr>
    <tr>
      <td>
        <img
          src="../assets/img/pastelZanahoria.jpg"
          alt="Pastel de zanahoria"
          height="120px"
        />
      </td>
      <td>Zanahoria</td>
      <td>$375 pesos</td>
    </tr>
  </table>
  <hr />
  <h2>Adornos disponibles</h2>
  <table>
    <tr>
      <th>Ilustración</th>
      <th>Adorno</th>
      <th>Precio</th>
    </tr>
    <tr>
      <td>
        <img
          src="../assets/img/christmasSprinkles.jpg"
          alt="Chispitas de navidad"
          height="120px"
        />
      </td>
      <td>Chispitas de navidad</td>
      <td>$250 pesos</td>
    </tr>
    <tr>
      <td>
        <img
          src="../assets/img/adornoBoda.jpg"
          alt="Adorno de boda"
          height="120px"
        />
      </td>
      <td>Adorno de boda</td>
      <td>$80 pesos</td>
    </tr>
    <tr>
      <td>
        <img
          src="../assets/img/floresComestibles.jpg"
          alt="Flores de papel comestibles"
          height="120px"
        />
      </td>
      <td>Flores de papel comestibles</td>
      <td>$200 pesos</td>
    </tr>
    <tr>
      <td>
        <img
          src="../assets/img/topperPascua.jpg"
          alt="Toppers de pascua para pastel"
          height="120px"
        />
      </td>
      <td>Toppers de pascua para pastel</td>
      <td>$175 pesos</td>
    </tr>
    <tr>
      <td>
        <img src="../assets/img/bombones.jpg" alt="Bombones" height="120px" />
      </td>
      <td>Bombones</td>
      <td>$150 pesos</td>
    </tr>
    <tr>
      <td>
        <img
          src="../assets/img/gominolasAzucar.jpg"
          alt="Gominolas de azúcar variadas"
          height="120px"
        />
      </td>
      <td>Gominolas de azúcar variadas</td>
      <td>$135 pesos</td>
    </tr>
  </table>
  <footer>
    <p>Copyright 2022</p>
  </footer>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
  margin: 0;
  padding: 0;
}

table {
  margin: 0 auto;
}

h1,
h2,
footer {
  text-align: center;
}

h1 {
  font-size: 36px;
  color: red;
  opacity: 0.75;
  text-shadow: 1px 2px 3px yellow;
}

h2 {
  font-size: 28px;
  color: brown;
}

table,
th,
td {
  border: solid 2px red;
}

tr {
  background-color: pink;
}

th {
  font-size: 24px;
  color: purple;
}
td {
  width: 200px;
  font-size: 20px;
  text-align: center;
}

#logo,
h1 {
  display: inline;
}

header,
footer {
  background-color: rgb(255, 174, 201);
}

ul {
  /* para quitar los "puntitos"/viñetas detrás de cada elemento de la lista*/
  list-style-type: none;
  text-align: center;
}

a {
  display: block;
  height: 40px;
}

#ligaInicio {
  background-color: white;
}

#ligaPedido {
  background-color: greenyellow;
}

#ligaSobre {
  background-color: yellow;
}

#ligaInventario {
  background-color: cornflowerblue;
}

#ligaInformacionPedidos {
  background-color: springgreen;
}

.ligaNav {
  text-decoration: none;
  font-size: 20px;
  color: firebrick;
}
</style>
