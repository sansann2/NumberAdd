<template>
  <div id="app">
    <DisplayNumber />
    <AddNumber />

  </div>
</template>

<script>
import AddNumber from './components/AddNumber.vue'
import DisplayNumber from './components/DisplayNumber.vue'



export default {
  name: 'App',
  components: {
    AddNumber,
    DisplayNumber, 
  }
}
</script>

