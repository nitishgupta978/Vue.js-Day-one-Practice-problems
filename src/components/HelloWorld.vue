<template>
<center>
 <div id="app">
  <h3>Type here:</h3>
  <textarea v-model.lazy="message" class="message" rows="6" maxlength="100" />
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
      message: 'Hi John now you can type here only your numbers!!'
}
  }
}
</script>



