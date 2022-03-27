<template>
  <h1>Realizar pedido</h1>
  <form action="prueba.js">
    <label for="nombre" class="etiquetasNoCheckbox">Nombre</label>
    <input type="text" id="nombre" name="nombre" />

    <label for="telefono" class="etiquetasNoCheckbox">Teléfono</label>
    <input type="tel" id="telefono" name="telefono" maxlength="10" />

    <label for="correo" class="etiquetasNoCheckbox">Correo electrónico</label>
    <input type="email" id="correo" name="correo" />

    <label for="descGeneral" class="etiquetasNoCheckbox"
      >Descripción general del pastel</label
    >
    <textarea
      name="descGeneral"
      id="descGeneral"
      cols="40"
      rows="10"
      placeholder="El pastel es para una boda y requiero que..."
    ></textarea>
    <div class="contenedorOpciones">
      <h3>Sabores</h3>
      <input
        type="checkbox"
        id="chocolate"
        name="chocolate"
        value="chocolate"
      />
      <label for="chocolate">Chocolate</label>
      <input type="checkbox" id="vainilla" name="vainilla" value="vainilla" />
      <label for="vainilla">Vainilla</label>
      <input type="checkbox" id="fresa" name="fresa" value="fresa" />
      <label for="fresa">Fresa</label>
      <input type="checkbox" id="limon" name="limon" value="limon" />
      <label for="limon">Limón</label>
      <input type="checkbox" id="oreo" name="oreo" value="oreo" />
      <label for="oreo">Oreo</label>
      <input
        type="checkbox"
        id="zanahoria"
        name="zanahoria"
        value="zanahoria"
      />
      <label for="zanahoria">Zanahoria</label>
    </div>
    <div class="contenedorOpciones">
      <h3>Adornos</h3>
      <input
        type="checkbox"
        id="chispitas-navidad"
        name="chispitas-navidad"
        value="chispitas-navidad"
      />
      <label for="chispitas-navidad">Chispitas de navidad</label>
      <input
        type="checkbox"
        id="adorno-boda"
        name="adorno-boda"
        value="adorno-boda"
      />
      <label for="adorno-boda">Adorno de boda</label>
      <input
        type="checkbox"
        id="flores-comestibles"
        name="flores-comestibles"
        value="flores-comestibles"
      />
      <label for="flores-comestibles">Flores comestibles</label>
      <input
        type="checkbox"
        id="topper-pascua"
        name="topper-pascua"
        value="topper-pascua"
      />
      <label for="topper-pascua">Topper de pascua</label>
      <input type="checkbox" id="bombones" name="bombones" value="bombones" />
      <label for="bombones">Bombones</label>
      <input
        type="checkbox"
        id="gominolas-azucar"
        name="gominolas-azucar"
        value="gominolas-azucar"
      />
      <label for="gominolas-azucar">Gominolas de azúcar variadas</label>
    </div>
  </form>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  text-align: center;
  background-color: bisque;
}

input {
  margin: 8px 0px 12px 6px;
}

h1 {
  margin: 10px 0px 10px 0px;
}

.etiquetasNoCheckbox {
  display: block;
}

.contenedorOpciones {
  margin: 20px 0px 20px 0px;
}
</style>
