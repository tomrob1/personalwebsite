<template>
  <div class="container-fluid">
      <div class="row">
        <div class="col"></div>
        <div class="col-la" id="main-body">
            <h2> About Me </h2>
            Studying Advanced Computer Science MSc, currently working on my Dissertation project that aims to create a  
            <a href="https://www.researchgate.net/publication/344547065_A_Case_for_a_Currencyless_Economy_Based_on_Bartering_with_Smart_Contracts">bartering web application</a>
            for goods and services, using the IBM blockchain Hyperledger Fabric.
            <hr>
            I have experience in front-end and back-end development, having used languages such as Java, Python, JavaScript, PHP, MySQL, R and C in my studies and work experience.
              <!-- portfolio section -->
              <br>
              <br>
              <br>
              <section class="protfolio">
                  <h2>Portfolio</h2>
                  <div class="container">
                      <div class="row">
                          <div class="col">
                                  <div class="card">
                                      <div class="card-head">
                                          <h2>Placement Project</h2>
                                      </div>
                                      <hr>
                                      <div class="card-body">
                                          <p>
                                            Developed a web app in Vue.js for users to browse the Computer Science staff directory and browse offices via a map at the University of Liverpool
                                          </p>
                                          <a href="https://github.com/tomrob1/StaffDir-Updated" class="btn btn-primary">Go to project</a>
                                      </div>
                                  </div>
                                  <br>
                          </div>

                          <div class="col">
                                  <div class="card">
                                      <div class="card-head">
                                          <h2>Undergraduate Project</h2>
                                      </div>
                                      <hr>
                                      <div class="card-body">
                                          <p>
                                            Financial Computing dissertation project - Developed a trading strategy in R from anonymised stocks
                                          </p>
                                          <a href="https://github.com/tomrob1/COMP396Project" class="btn btn-primary">Go to project</a>
                                      </div>
                                  </div>
                              <br>
                          </div>  

                          <div class="col">
                              <div class="card">
                                  <div class="card-head">
                                      <h2>Postgraduate Group Project</h2>
                                  </div>
                                  <hr>
                                  <div class="card-body">
                                      <p>
                                        Front-end developer of group project, developed web application in Vue.js that pulled API data from Newcastle University smart building and displayed graphically.
                                      </p>
                                      <a href="https://github.com/chencqy/ncl_group1" class="btn btn-primary">Go to project</a>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
              </section>
        </div>
        <div class="col" id="links">
        <p class="h4">Links</p>
        <b-icon icon="github"></b-icon><a href="https://github.com/tomrob1">Github</a> <br>
        <b-icon icon="file-earmark-person"></b-icon><a :href=pdfLink target="_blank">CV</a> <br>
        <b-icon icon="envelope"></b-icon><a href="mailto:tomrobertson599@hotmail.co.uk" target="_blank">Email</a>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Body',
  data(){
    return {
      pdfLink : require('../assets/NEW_CV.pdf')
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#main-body{
  margin-top: 30px;
}
#links{
    margin-top: 30px;
}
.card-head{
  padding-top: 10px;
}
</style>
