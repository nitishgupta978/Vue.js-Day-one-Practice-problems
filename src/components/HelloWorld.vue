<template>
  <div id="app">
  <ul>
  <li v-for="value in myObject">
    {{ value }}
  </li>
</ul>
 
</div>
</template>


<script>
export default {
   name: 'HelloWorld',
   
  data() {
    return {
    myObject: {
      title: 'How to do lists in Vue',
      author: 'Jane Doe',
      publishedAt: '2016-04-10'
    }
  }
}
}
</script>
