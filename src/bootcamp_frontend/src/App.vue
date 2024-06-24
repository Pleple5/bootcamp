<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    Cześć
    <br/>
    <button @click="klik">kliknij</button>
      {{ licznik }}
  </main>
</template>

<script>
export default {
  data() {
    return {
      licznik: 0
    }
  },
  methods: {
    klik() {
      this.licznik++
    }
  }
}
</script>