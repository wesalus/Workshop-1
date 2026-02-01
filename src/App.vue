<template>
  <div>{{ amount }}</div>
  <button
   style="padding: 13px; background-color: blue;" @click="handleClick"> 
  
   Zähl hoch
    </button>


</template>

<script setup>
let amount = 0; 
function handleClick() {
amount++;
console.log(amount)
}

</script>

<style scoped>

</style>
