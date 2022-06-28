<template>
<center>
 <div id="app">
  <h3>Type here:</h3>
  <textarea v-model="message" class="message" rows="5" maxlength="72"/>
  <br>
  <p class="booktext">{{ message }} </p>
</div>
</center>
</template>


<script>
export default {
   name: 'HelloWorld',
   
  data() {
    return {
      message: 'This is a good place to type things.'
}
  }
}
</script>



