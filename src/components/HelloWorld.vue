<template>
 <div class="hello">
   <h1>{{ msg }}</h1>
   <br>
   <a href="http://ohno.com.ar" class="btn btn-danger">
     Oh no!
   </a>
   <br>
   <div class="alert alert-success mt-3" role="alert">
     Primer proyecto del curso con el Cli!
   </div>
 </div>
</template>

<script>
export default {
  name: 'Fespi',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 40px 0;
}

</style>
