<template>
    <section>
        <form>
            <h1>Login pudge</h1>
            <div class="form-group">
                  <input type="text" class="form-contol">
            </div>
         
           <p>
               <nuxt-link to="/">Home</nuxt-link>
           </p>



        <button class="btn btn-primary" type="submit">
          Login
        </button>
    
        </form>
    </section>
</template>
<script>
export default {
    layout: "empty"
}
</script>
<style scoped>
  input{
      width: 400px;
  }
  form{
      top: 500px;
      width: 500px;
      margin: auto 0; 
  }
</style>