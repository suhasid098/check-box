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
  <input
    v-model="tutorials"
    type="checkbox"
    value="Video"
    name="video"/>
  <label for="video">Video</label><br />
  <input v-model="tutorials" 
          type="checkbox" 
          value="Text" 
          name="text" />
  <label for="text">Text</label><br />
  <input
    v-model="tutorials"
    type="checkbox"
    value="Examples"
    name="examples"/>
  <label for="examples">Examples</label><br />
  <input
    v-model="tutorials"
    type="checkbox"
    value="QnA"
    name="qna"/>
  <label for="qna">QnA</label>
  <p>Tutorials: {{ tutorials }}</p>
</template>