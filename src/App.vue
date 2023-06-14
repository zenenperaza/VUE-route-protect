<template>
<div> 
  <input type="text" name="" id="" v-model="note" />
  <button v-on:click="sendToServe">Enviar notas</button>
</div>
</template>

<script lang="ts" setup>
import { ref  } from "vue";

let note = ref('')

const sendToServe = () => {
  alert("funciona")
}
   
</script>

<style scoped>

</style>