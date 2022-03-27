<template>
  <h1>Información sobre pedidos</h1>
  <table>
    <tr>
      <th>Nombre del cliente</th>
      <th>Teléfono</th>
      <th>Correo electrónico</th>
      <th>Descripción general del pastel</th>
      <th>Selección de sabores</th>
      <th>Selección de adornos</th>
    </tr>
    <tr>
      <td>Luis Manuel</td>
      <td>6645317869</td>
      <td>luismanuel123@gmail.com</td>
      <td>Requiero de un pastel para mi boda, con presentación elegante.</td>
      <td>Chocolate, Vainilla y Fresa</td>
      <td>Adorno de boda</td>
    </tr>
    <tr>
      <td>Juan Pérez</td>
      <td>6625792351</td>
      <td>juanitop@outlook.com</td>
      <td>
        Necesito un pastel para el cumpleaños de mi hijo, que esté decorado en
        base a un superhéroe.
      </td>
      <td>Oreo</td>
      <td>Bombones y Gominolas de azúcar variadas</td>
    </tr>
    <tr>
      <td>Ángela León</td>
      <td>6621580247</td>
      <td>leonangela15@hotmail.com</td>
      <td>Necesito un pastel con temática navideña.</td>
      <td>Zanahoria y Vainilla</td>
      <td>Chispitas de navidad</td>
    </tr>
  </table>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
}

table {
  margin: 0 auto;
}

body {
  text-align: center;
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
