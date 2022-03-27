<template>
  <h1>Inventario</h1>
  <h2>Sabores disponibles</h2>
  <table>
    <tr>
      <th>Ilustración</th>
      <th>Sabor</th>
      <th>Cantidad restante</th>
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
      <td>16</td>
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
      <td>12</td>
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
      <td>23</td>
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
      <td>32</td>
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
      <td>8</td>
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
      <td>19</td>
    </tr>
  </table>
  <br />
  <hr />
  <br />
  <h2>Adornos disponibles</h2>
  <table>
    <tr>
      <th>Ilustración</th>
      <th>Adorno</th>
      <th>Cantidad restante</th>
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
      <td>35</td>
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
      <td>20</td>
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
      <td>16</td>
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
      <td>12</td>
    </tr>
    <tr>
      <td>
        <img src="../assets/img/bombones.jpg" alt="Bombones" height="120px" />
      </td>
      <td>Bombones</td>
      <td>28</td>
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
      <td>22</td>
    </tr>
  </table>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
}

body {
  text-align: center;
}

table {
  margin: 0 auto;
}

a {
  font-size: 18px;
  text-align: center;
}

h1,
h2 {
  text-align: center;
}

h1 {
  font-size: 36px;
  color: brown;
  margin: 0px 0px 16px 0px;
  background-color: cornflowerblue;
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
</style>
