<template lang="html">
  <div>
    <form id="pago" @submit.prevent>
        <fieldset>
        <legend>Datos del comprador</legend>
        <ol>
        <li>
        <label for="nombre">Nombre</label>
        <input id="nombre" name="nombre" type="text" placeholder="Escribe tu nombre completo"  autofocus>
        </li>
        <li>
        <label for="email">Email</label>
        <input id="email" name="email" type="email" placeholder="ejemplo@um.es" >
        </li>
        <li>
        <label for="telefono">Teléfono</label>
        <input id="telefono" name="telefono" type="tel" placeholder="Ej. +34668899999" >
        </li>
        <li>
        <label for="pais">País</label>
        <input id="pais" name="pais" type="text" >
        </li>
        </ol>
        </fieldset>
        <button type="submit" @click="clicBtn">Confirmar pedido</button>
    </form>
  </div>
</template>
<script>

export default {
  data () {
    return {
   
    }
  },
 created: function () { 
     
  },
  mounted: function () {
    
  },
  methods: {
   clicBtn: function () {
    
   }
  }
}
</script>


