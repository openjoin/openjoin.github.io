<template>
   <div>
      <section class="home-top">
         <div class="container">
            <div class="columns">
               <div class="column">
                  <b-image
                     src="assets/home.png"
                     class="home-img"
                     ></b-image>
               </div>
               <div class="column">
                  <center>
                     <h1>Open Source is for everyone, yes you!</h1>
                     <p><span class="special">OPEN SOURCE</span> is not about code, it is about people and collaboration.</p>
                     <h5><span class="qute">“</span>Use this plateform to publish your opensource projects..<span class="qute">”</span></h5>
                  </center>
               </div>
            </div>
         </div>
      </section>
      <section>
        <div class="container">
            <div class="columns">
               <div class="column">
                  <div class="box">
                     <article class="media">
                        <div class="media-left">
                           <figure class="image is-64x64">
                              <b-icon
                                 icon="target"
                                 size="is-large"
                                 type="is-danger">
                              </b-icon>
                           </figure>
                        </div>
                        <div class="media-content">
                           <div class="content">
                              <h4> Our Target</h4>
                              <p>
                                 We are invested in getting you those green squares 💹 on GitHub! Contributing to Open Source Software (OSS) is a great way for you to learn, work with different people and also network.
                              </p>
                           </div>
                        </div>
                     </article>
                  </div>
               </div>
            </div>
         </div>
      </section>
      <Team/>
      <Footer/>
   </div>
</template>
<script>
   import Team from '@/components/Team.vue'
   import Footer from '@/components/Footer.vue'
   
   export default {
     name: 'Home',
     data() {
       return {
           rounded: false,
       }
     },
     components: {
       Team,
       Footer
     }
   }
</script>
<style scoped>
  h1 {
    font-family: 'Lobster', cursive;
    margin-top: 3em;
    font-size : 50px;
    color: black;
  }
  h4{
    font-family: 'Lobster', cursive;
    color: black;
    margin-top: 1em;
  }
  h5 {
    color :red;
    font-size : 20px;
    font-weight: bold;
  }
  p {
    color: maroon;
    font-family: 'Kaushan Script', cursive;
  }
  .home-img {
    margin-top: 4em;
  }
  .home-top {
     margin-bottom: 3em;
  }
  .special {
     padding: 2px; 
     background-color: #ffcfe2;
     color: maroon;
     font-family: cursive;
     border-radius: 5px;
  }
  .qute {
    font-size: 50px;
  }

  @media (max-width: 991.98px) {
    h1 {
      font-family: 'Lobster', cursive;
      margin-top: 1em;
      font-size : 30px;
    }
    h4{
      font-family: 'Lobster', cursive;
      margin-top: 1em;
    }
    .home-img {
      margin-top: 1em;
    }

  }
</style>
