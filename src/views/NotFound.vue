<template>
  <h2>404</h2>
  <h3>Page not found</h3>

  <div class="return">
      <router-link :to="{ name: 'Home' }">Return to home</router-link>
  </div>
</template>

<style>
.return {
    background: rgb(190, 169, 169);
    padding: 20px;
    border-radius: 10px;
    max-width: 200px;
    margin: 10px auto;
}

#a.router-link {
  color: black;  
}
</style>