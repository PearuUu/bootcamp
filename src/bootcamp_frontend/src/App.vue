<script>
export default {
  data()
  {
    return {
      licznik: 0
    }
  },
  methods: {
    increase()
    {
      this.licznik++;
    }
  }
}

</script>

<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <br>
    <button @click="increase">Increase</button>
    <span>{{ licznik }}</span>
  </main>
</template>
