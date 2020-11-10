<template>
  <div class="about">
    <center>
        <h2>Contact Our Community</h2>
        <br>
        <p>Join with our <span class="special">Discord</span> server</p>
        <a class="button is-info"  href="https://discord.gg/jzvkhJeP">https://discord.gg/jzvkhJeP</a>
    </center>
    <Footer/>
  </div>
</template>

<script>
   import Footer from '@/components/Footer.vue'
   
   export default {
     name: 'Home',
     components: {
       Footer
     }
   }
</script>

<style scoped>
a {
  color: black;
}
h2 {
  font-family: 'Lobster', cursive;
  margin-top: 2em;
  font-size : 35px;
  color: black;
}
p {
  color: maroon;
  font-family: 'Kaushan Script', cursive;
}
.special {
  font-size : 18px;
  padding: 2px; 
  background-color: #ffcfe2;
  color: maroon;
  font-family: cursive;
  border-radius: 5px;
}
</style>
