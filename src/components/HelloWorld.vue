<template>
  <div id="app">
  <li v-for="{ message } in items">
  {{ message }}
</li>

<!-- with index alias -->
<li v-for="({ message }, index) in items">
  {{ message }} {{ index }}
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
