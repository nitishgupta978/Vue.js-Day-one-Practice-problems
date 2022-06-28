<template>
<center>
 <h1 v-if="awesome">Vue is awesome!</h1>
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
