<template>
  <div id="app">
  <ul>
  <li v-for="value in myObject">
    {{ value }}
  </li>
  <li v-for="(value, key) in myObject">
  {{ key }}: {{ value }}
</li>
</ul>
<br>
<br>
<h2>Index</h2>
<li v-for="(value, key, index) in myObject">
  {{ index }}. {{ key }}: {{ value }}
</li>
 
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
