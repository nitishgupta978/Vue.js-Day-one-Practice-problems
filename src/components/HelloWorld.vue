<template>
<center>
 <div id="app">
  <input v-model="checkedNames" type="checkbox" id="john" value="John"/>
  <label for="john"> John</label>
  
  <input v-model="checkedNames" type="checkbox" id="paul" value="Paul"/>
  <label for="paul"> Paul</label>
  
  <input v-model="checkedNames" type="checkbox" id="george" value="George"/>
  <label for="george"> George</label>
  
  <input v-model="checkedNames" type="checkbox" id="ringo" value="Ringo"/>
  <label for="ringo"> Ringo</label>
  <br>
  <span> <h4>Checked names: {{ checkedNames }}</h4></span>
</div>
</center>
</template>


<script>
export default {
   name: 'HelloWorld',
   
  data() {
    return {
      checkedNames: ['Hi John now you  select !!']
}
  }
}
</script>



