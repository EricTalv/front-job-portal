<template>
  <div class="link-container">
      
       <div class="links">


        <nuxt-link
        to="/login" 
        class="inactive-link"
        exact>Login</nuxt-link>
       
        <nuxt-link
        to="/register" 
        class="inactive-link"
        exact>Register</nuxt-link>
       
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

.link-container {
  margin: 5%;
}

.links {
  justify-content: center;
  align-items: center;
  text-align: center;
}

.nuxt-link-exact-active {
 
  background-color: #3b8070 !important;
  border: 0px !important;
  color: #fff !important;
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