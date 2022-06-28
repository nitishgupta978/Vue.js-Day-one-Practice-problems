<template>
  <div id="app">
  <ul>
    <li v-for="item in items" :key="item">
      {{ item }}
    </li>
  </ul>
</div>
</template>


<script>
export default {
   name: 'HelloWorld',
   
  data() {
   return {
    
       items: [
       'you find me','good',
       'nice to meet you'
       ]
    }
  }
}
</script>
