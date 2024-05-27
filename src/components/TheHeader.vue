<script setup>

</script>

<template>
  <header >
<div class="header-start">
   <router-link :to="{name:'main'}"><img src="../assets/image/лого.png" alt="" width="200px"></router-link>
  <router-link :to="{name:'OurActor'}"><p>Актёры</p></router-link>
  <router-link :to="{name:'About'}"><p>О нас</p></router-link>
</div>
  </header>
</template>

<style scoped>
header{
width: 100%;
  background-color: darkred;
  margin-right: 10em;
}
.header-start{
  align-items: center;
  display: flex;
  justify-content: space-evenly;
}
p{
  color:gold;
  font-size:1.5em;
}
</style>