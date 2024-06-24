
<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    xDDD
    <br/>
    <button @click="podbij"> +1</button>
    {{ licznik }}
  </main>
</template>

<script>
    export default{
      data() {
        return {
          licznik: 0
        }
      },
      methods: {
        podbij(){
          this.licznik++
        }
      },
    }
</script>