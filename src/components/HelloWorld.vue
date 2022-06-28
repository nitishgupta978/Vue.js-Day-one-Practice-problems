<template>
  <div id="app">
  
    <li v-for="(item, index) in items" :key="items">
  {{ parentMessage }} - {{ index }} - {{ item.message }}
</li>
 
</div>
</template>


<script>
export default {
   name: 'HelloWorld',
   
  data() {
   return {
       parentMessage: 'Parent',
       items: [{ message: 'Foo' }, { message: 'Bar' },{ message: 'Honey' },{ message: 'Party' }]
    }
  }
}
</script>
