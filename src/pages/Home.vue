<script setup lang="ts">
    let contador:number = 0;
    function increment() {        
        contador = contador+1;
        console.log('ta vindo aqui', contador);

    }
</script>

<template>
<h2 >Essa é a home: {{ contador }}</h2>
{{ contador }}
<button v-on:click="increment">Clicador</button>
</template>