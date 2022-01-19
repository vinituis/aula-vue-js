<template>
  <div>
    <primeiro-componente />
    <p>Essa aplicação é: {{ testando }}</p>
  </div>
</template>

<script>
  import primeiroComponente from './components/primeiroComponente.vue'

  export default {
    name: 'App',
    components: {
      primeiroComponente
    },
    data() {
      return {
        testando: 'teste'
      }
    }
  }
</script>