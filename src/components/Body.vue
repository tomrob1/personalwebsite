<template>
  <div class="container-fluid">
      <div class="row">
        <div class="col"></div>
        <div class="col" id="main-body">
            <p class="h3"> About Me </p>
            Studying Advanced Computer Science MSc, currently working on my Dissertation project that aims to create a  
            <a href="https://www.researchgate.net/publication/344547065_A_Case_for_a_Currencyless_Economy_Based_on_Bartering_with_Smart_Contracts">bartering web application</a>
            for goods and services, using the IBM blockchain Hyperledger Fabric.
            <hr>
            I have experience in front-end and back-end development, having used languages such as Java, Python, JavaScript, PHP, MySQL, R and C in my studies and work experience.
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
</style>
