<script>
import PlaceholderComponent from './components/PlaceholderComponent.vue'
</script>

<template>

  <header>
    <div>Yu-Gi-Oh API</div>
  </header>

  <main>
    <select name="Type" id="cardsType">
      <option value="alien">Alien</option>
    </select>
    <div id="cardsDisplay">
      content
    </div>
  </main>
 
</template>

<style scoped>
  header div {
    width: 100%;
    background-color: white;
    color: black;
    padding: 1rem 10vw;
    font-size: 2rem;
  }
  main {
    padding: 2rem 10vw;
    background-color: orange;
  }
  select {
    margin-bottom: 1rem;
  }
  #cardsDisplay {
    background-color: white;
    padding: 1.5rem;
    color: black;
  }
</style>
