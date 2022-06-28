<template>
 <p>Using text interpolation: {{ rawHtml }}</p>
<p>Using v-html directive: <span v-html="rawHtml"></span></p>
<h3>
<span style="color: red">This should be red.</span>
</h3>
</template>


<script>
export default {
   name: 'HelloWorld',
   
  data() {
  return {
   rawHtml:' red'
  }
},
}
</script>


