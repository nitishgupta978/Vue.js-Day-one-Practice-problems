<template>
<center>
  <button @click="awesome = !awesome">Toggle</button>
 <h1 v-if="awesome">Vue is awesome!</h1>
 <h1 v-else>oh no 😢</h1>
 </center>
</template>

<script>
export default {
   name: 'HelloWorld',
   
  data() {
   return {
       awesome: true
    }
  }
}
</script>
