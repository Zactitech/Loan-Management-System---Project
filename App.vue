<template>
  <div class="background-image">
  
    <div>

      <h1 style="padding-top:250px">Get a loan today!</h1>    
  
      <h2 style="padding-top:400px">FinCraft loan management system is a digital platform that automates every 
          stage of the loan lifecycle.</h2>
          <br>
          <br>
          <br>
  
    </div>
  </div>
  <div class="questions" style="text-align:left; font-weight:bolder; background-color:rgb(2, 2, 60);"><span style="color:white;">Frequently asked</span> questions</div> <hr>
    <div style="font-size:200%;"><p><select class="dropdown">
      <option value="option1">How does LMS work?</option>
      <option value="option2">Depending on requirements, LMS assists in part or whole. </option>
      <option value="option3">LMS provides lenders with accurate statements and reports.</option>
    </select></p> <br> <hr>
      
      <p><select class="dropdown">
        <option value="option1">How do i qualify for a loan?</option>
        <option value="option2">LMS evaluates credit score and how you handled debt previously. </option>
        <option value="option3">How much you earn will determine how much credit you can take on.</option>
      </select></p> <br> <hr>
      <p> <select class="dropdown">
        <option value="option1">How do I apply for a loan?</option>
        <option value="option2">ID(SA Resident) or Passport with valid work/retirement permit (non-SA resident)</option>
        <option value="option3">Proof of residence (in your name, and not older than 3 months)        </option>
        <option value="option3">Proof of income and financial information</option>
      </select></p> <br> <hr>
      <div style="font-size:90%">Have more questions?</div>
      <v-btn class="btn" variant="tonal">
        Contact a Consultant
      </v-btn>
      <v-btn style="margin-left:44.5%" class="btn" variant="tonal">
        Read more FAQs
      </v-btn>
      <br>
      <br>
      <br>
      <br>
    </div>
    <div class="base-box">
      
        Home &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
        FaQs <br>
        Interests &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
        Privacy Policy <br>
        Contact &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
        Terms and Conditions &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
        Social Links
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <a href="#" class="fa fa-facebook"></a>
        <a href="#" class="fa fa-twitter"></a>
        <a href="#" class="fa fa-linkedin"></a>
        <a href="#" class="fa fa-youtube"></a>
      </div>
      <hr width="95%" style="margin-left:2%; margin-bottom:1%" >
      <p style="color:white; text-align:center; margin-bottom:3%">Copyright © 2012 - 2023, FindaVirtualFriend.com. All Rights Reserved.</p>
     


</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',

  components: {
    HelloWorld
  }
}
 
</script>
<style>
body{
  background-color:rgb(2, 2, 60);
  font-family: Arial, Helvetica, sans-serif;
  color: white;
}
.background-image {
  background-image: url('@/assets/background.png');
  background-size: cover;
  background-position: center;
  background-color: rgb(2, 2, 60);
}
h1{
  font-size: 500%;
  text-align: center;
  left: 20%;
  top: 250px;
}
h2{
  font-size: 300%;
  left: 20%;
  top: 600px;
}
.questions{
  color:deepskyblue;
  font-size: 300%;
}
.btn{
  background-color: deepskyblue;
  margin-left: 42%;
}
.base-box{
  /*background-image: url('@/assets/darker.png');*/
  width: 400%;
  margin-bottom: 5%;
  margin-left: 25%;
}
.base-box1{
  width: 8%;
  height: 100px;
  background-color: deepskyblue;
}
.base-box2{
  width: 8%;
  height: 100px;
  margin-left: 10%;
  background-color: deepskyblue;
}
.base-box3{
  width: 8%;
  height: 100px;
  margin-left: 20%;
  background-color: deepskyblue;
}
.fa {
  padding: 20px;
  font-size: 30px;
  width: 50px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
}
.fa:hover {
  opacity: 0.7;
}
.fa-facebook {
  background: #3B5998;
  color: white;
}

.fa-twitter {
  background: #55ACEE;
  color: white;
}
.fa-linkedin {
  background: #007bb5;
  color: white;
}

.fa-youtube {
  background: #bb0000;
  color: white;
}
.dropdown {
  width: 400%;
  color: deepskyblue;
  
}

  </style>
