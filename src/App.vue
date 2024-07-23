<template>
  <div id="app">
    <header>
      <h1>Welcome to My Vue App</h1>
    </header>
    <main>
      <PriyanshComponent />
    </main>
  </div>
</template>

<script>
import PriyanshComponent from './components/Priyansh.vue'

export default {
  name: 'App',
  components: {
    PriyanshComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  display: flex;
  flex-direction: column;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
