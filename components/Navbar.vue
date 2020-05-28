<template>
  <div class="link-container">
      
       <div class="links">


        <nuxt-link

        to="/about" 
        class="inactive-link"
        exact>About</nuxt-link>
       
        <nuxt-link
        to="/" 
        class="inactive-link"
        exact>Home</nuxt-link>

      </div>
      
      </div>   
  
</template>

<script>
export default {

}
</script>

<style scoped>

.links {
  justify-content: center;
  align-items: center;
  text-align: center;
}


.nuxt-link-exact-active {
 
  background-color: #3b8070;

  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #fff;
  text-decoration: none;
  padding: 10px 30px;
}


.inactive-link {
  background-color: #fff;

  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.inactive-link:hover {
  color: #fff;
  border: 1px solid #3b8070;

  background-color: #3b8070;
}

</style>