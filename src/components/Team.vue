<template>
	<section>
        <div class="container">
            <center>
                <h2>Our Awesome Team</h2>
                <br>
            </center>
            <!-- Must add three column in one row -->
            <div class="columns">
               <div class="column">
                  <div class="box">
                     <article class="media">
                        <div class="media-left">
                           <figure class="image is-64x64">
                                <b-image
                                    src="https://avatars1.githubusercontent.com/u/33308414?s=460&u=d7ca504b514a16fac3bdfec55f58cab40e02f2da&v=4"
                                    class="home-img"
                                ></b-image>
                           </figure>
                        </div>
                        <div class="media-content">
                           <div class="content">
                              <h4>
                                 <a target="_blank" href="https://github.com/Katheesh">S. Katheeskumar</a>
                              </h4>
                              <p>
                                 Softwate Engineer at <a target="_blank" href="https://gitleaf.com">GitLeaf</a>
                              </p>
                           </div>
                        </div>
                     </article>
                  </div>
               </div>
               <div class="column">
                  <div class="box">
                     <article class="media">
                        <div class="media-left">
                           <figure class="image is-64x64">
                                <b-image
                                    src="https://avatars3.githubusercontent.com/u/22113485?s=400&u=73dc0bd949e873a0cd09b86bcf45d10953da049e&v=4"
                                    class="home-img"
                                ></b-image>
                           </figure>
                        </div>
                        <div class="media-content">
                           <div class="content">
                              <h4>
                                 <a target="_blank" href="#">E.Vijay</a>
                              </h4>
                              <p>
                                 <a target="_blank" href="#">FreeLancer</a>
                              </p>
                           </div>
                        </div>
                     </article>
                  </div>
               </div>
               <div class="column">
                  <div class="box">
                     <article class="media">
                        <div class="media-left">
                           <figure class="image is-64x64">
                                <b-image
                                    src="https://readyrefrigeration.ca/sites/default/files/styles/headshot/adaptive-image/public/nobody.jpg"
                                    class="home-img"
                                ></b-image>
                           </figure>
                        </div>
                        <div class="media-content">
                           <div class="content">
                              <h4>
                                 <a target="_blank" href="#">Sample</a>
                              </h4>
                              <p>
                                 Sample job at <a target="_blank" href="#">You Company</a>
                              </p>
                           </div>
                        </div>
                     </article>
                  </div>
               </div>
            </div>
            <center><router-link to="/join" class="button is-danger">Join Now</router-link></center>
        </div>
    </section>
</template>

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
h1 {
  font-family: 'Lobster', cursive;
  color: black;
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
