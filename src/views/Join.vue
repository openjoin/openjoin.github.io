<template>
   <div>
      <div class="container">
         <div class="columns">
            <div class="column">
               <center>
                  <h1>How to join our community?</h1>
                  <img width="300" src="assets/undraw_Invite_re_rrcp.svg">
                  <p class="special">Raise an issue on the support repo asking to join.</p>
                  <br>
                    <a class="button is-danger" href="https://github.com/openjoin/support/issues/new/choose">
                     <strong>Raise an issue</strong>
                    </a>
                    <br>
                    
               </center>
            </div>
         </div>
      </div>
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
h1 {
	margin-top: 1em;
  font-family: 'Lobster', cursive;
  color: black;
  font-size : 50px;
}
h4{
  font-family: 'Lobster', cursive;
  color: black;
}
p {
  color: maroon;
  font-family: 'Kaushan Script', cursive;
}
.special {
  font-size : 22px;
  padding: 2px; 
  background-color: #ffcfe2;
  color: maroon;
  font-family: cursive;
  border-radius: 5px;
}
</style>