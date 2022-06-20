<script>
export default {
  data() {
  return {
    tutorials: [],
  }
},
}
</script>
<template>
  <center>
    <input
      v-model="tutorials"
      type="checkbox"
      value="Data Structures"
      name="ds"/>
    <label for="ds">Data Structures</label><br />
    <input v-model="tutorials" 
           type="checkbox" 
           value="Algorithms" 
           name="al" />
    <label for="al">Algorithms</label><br />
    <input
      v-model="tutorials"
      type="checkbox"
      value="Machine Learning"
      name="ml"/>
    <label for="ml">Machine Learning</label>
    <p>Tutorials: {{ tutorials }}</p>
  </center>
</template>