<template>
  <div class="container">

<!-- Side Bar for cotraction -->
<div class="sidenav">
         <div class="login-main-text">
                <img class="img-circle img-responsive" src="http://api.adorable.io/avatars/300/abott@adorable.png">
                    <div>
                        <h2> <span itemprop="name">Weilun Liu</span></h2>

                        <p> <ul class="social-network social-circle">
                        <li><a href="https://github.com/waylen94" class="icoGitbub" title="Github"><i class="fa fa-github"></i></a></li>
                        <li><a href="#" class="icoFacebook" title="Facebook"><i class="fa fa-facebook"></i></a></li>

                        <li><a href="#" class="icoGoogle" title="Google +"><i class="fa fa-google-plus"></i></a></li>
                        <li><a href="#" class="icoLinkedin" title="Linkedin"><i class="fa fa-linkedin"></i></a></li>
                        <li><a href="https://waylen94.github.io/Diary/" class="icoDiary" title="Diary"><i class="fa fa-calendar"></i></a></li>

                    </ul>

                  </p>
                        <p><i class="fa fa-map-marker"></i> <span itemprop="addressRegion">Brisbane, QLD</span></p>
                        <p itemprop="email"> <i class="fa fa-envelope"> </i> <a href="mailto:you@somedomain.com">valenliu1994@gmail.com</a> </p>



                    </div>
         </div>
</div>

<!-- Content -->
<div class="main">
    <div class="jumbotron">
      <div class="container">
        <h1>Education</h1>
        <p></p>
        <p><a class="btn btn-primary btn-lg" href="http://www.bootcss.com/" role="button" target="_blank">Learn more <span class="glyphicon glyphicon-hand-right" aria-hidden="true"></span></a></p>
      </div>
    </div>
    <div class="jumbotron">
      <div class="container">
        <h1>Work Experience</h1>
        <p>Get vector icons and social logos on your website with Font Awesome, the web’s most popular icon set and toolkit.</p>
        <p>
          <i class="fa fa-camera"></i>
          <i class="fa fa-camera fa-2x"></i>
          <i class="fa fa-camera fa-3x"></i>
          <i class="fa fa-camera fa-4x"></i>
          <i class="fa fa-camera fa-5x"></i>
          <i class="fa fa-spinner fa-spin"></i>
        </p>
      </div>
    </div>





    <div class="projectexhibition-section">
      <h1>Project Exhibition</h1>

                    <div class="row">
                        <div class="col-md-6 how-img">
                            <img src="https://image.ibb.co/dDW27U/Work_Section2_freelance_img1.png" class="rounded-circle img-fluid" alt=""/>
                        </div>
                        <div class="col-md-6">
                            <h4>Find rewarding projects</h4>
                                        <h4 class="subheading">GetLance is a great place to find more clients, and to run and grow your own freelance business.</h4>
                        <p class="text-muted">Freedom to work on ideal projects. On GetLance, you run your own business and choose your own clients and projects. Just complete your profile and we’ll highlight ideal jobs. Also search projects, and respond to client invitations.
                                            Wide variety and high pay. Clients are now posting jobs in hundreds of skill categories, paying top price for great work.
                                            More and more success. The greater the success you have on projects, the more likely you are to get hired by clients that use GetLance.</p>
                        </div>
                    </div>

                    <div class="row">
                        <div class="col-md-6">
                            <h4>Get hired quickly</h4>
                                        <h4 class="subheading">GetLance makes it easy to connect with clients and begin doing great work.</h4>
                                        <p class="text-muted">Streamlined hiring. GetLance’s sophisticated algorithms highlight projects you’re a great fit for.
                                            Top Rated and Rising Talent programs. Enjoy higher visibility with the added status of prestigious programs.
                                            Do substantial work with top clients. GetLance pricing encourages freelancers to use GetLance for repeat relationships with their clients.</p>
                        </div>
                        <div class="col-md-6 how-img">
                            <img src="https://image.ibb.co/cHgKnU/Work_Section2_freelance_img2.png" class="rounded-circle img-fluid" alt=""/>
                        </div>
                    </div>

                    <div class="row">
                        <div class="col-md-6 how-img">
                             <img src="https://image.ibb.co/ctSLu9/Work_Section2_freelance_img3.png" class="rounded-circle img-fluid" alt=""/>
                        </div>
                        <div class="col-md-6">
                            <h4>Work efficiently, effectively.</h4>
                                        <h4 class="subheading">With GetLance, you have the freedom and flexibility to control when, where, and how you work. Each project includes an online workspace shared by you and your client, allowing you to:</h4>
                                        <p class="text-muted">Send and receive files. Deliver digital assets in a secure environment.
                                            Share feedback in real time. Use GetLance Messages to communicate via text, chat, or video.
                                            Use our mobile app. Many features can be accessed on your mobile phone when on the go.</p>
                        </div>
                    </div>

                    <div class="row">
                        <div class="col-md-6">
                            <h4>Get paid on time</h4>
                                        <h4 class="subheading">All projects include GetLance Payment Protection — helping ensure that you get paid for all work successfully completed through the freelancing website.</h4>
                                        <p class="text-muted">All invoices and payments happen through GetLance. Count on a simple and streamlined process.
                                            Hourly and fixed-price projects. For hourly work, submit timesheets through GetLance. For fixed-price jobs, set milestones and funds are released via GetLance escrow features.
                                            Multiple payment options. Choose a payment method that works best for you, from direct deposit or PayPal to wire transfer and more.</p>
                        </div>
                        <div class="col-md-6 how-img">
                            <img src="https://image.ibb.co/gQ9iE9/Work_Section2_freelance_img4.png" class="rounded-circle img-fluid" alt=""/>
                        </div>
                    </div>

                </div>
      </div>
  </div>


</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
$icon-font-path: "~bootstrap-sass/assets/fonts/bootstrap/";
$fa-font-path: "~font-awesome/fonts/";
@import "~bootstrap-sass/assets/stylesheets/_bootstrap";
@import "~font-awesome/scss/font-awesome";

body > .container { margin-top: 15px;}


.projectexhibition-section{
    margin-top:2%;
    padding: 5%;

    h4{
        color: #ffa500;
        font-weight: bold;
        font-size: 30px;
    }
    .subheading{
        color: #3931af;
        font-size: 20px;
    }
    .row{
        margin-top: 10%;
    }
}

.how-img
{
    text-align: center;
}
.how-img img{
    width: 40%;
}


.main-head{
    height: 150px;
    background: #FFF;

}

.sidenav {
    height: 100%;
    background-color: #000;
    overflow-x: hidden;
    padding-top: 20px;
}


.main {
    padding: 0px 10px;
}

@media screen and (max-height: 450px) {
    .sidenav {padding-top: 15px;}
}

@media screen and (max-width: 450px) {
    .login-form{
        margin-top: 10%;
    }

    .register-form{
        margin-top: 10%;
    }
}

@media screen and (min-width: 768px){
    .main{
        margin-left: 25%;
    }

    .sidenav{
        width: 25%;
        position: fixed;
        z-index: 1;
        top: 0;
        left: 0;
    }

    .login-form{
        margin-top: 80%;
    }

    .register-form{
        margin-top: 20%;
    }
}


.login-main-text{
    margin-top: 20%;
    padding: 60px;
    color: #fff;
}

.login-main-text h2{
    font-weight: 300;
}

.btn-black{
    background-color: #000 !important;
    color: #fff;
}


/*=========================
  Icons
 ================= */

/* footer social icons */
ul.social-network {
  list-style: none;
  display: inline;
  margin-left:0 !important;
  padding: 0;
}
ul.social-network li {
  display: inline;
  margin: 0 5px;
}


/* footer social icons */
.social-network a.icoGitbub:hover {
  background-color: #F56505;
}
.social-network a.icoFacebook:hover {
  background-color:#3B5998;
}
.social-network a.icoTwitter:hover {
  background-color:#33ccff;
}
.social-network a.icoGoogle:hover {
  background-color:#BD3518;
}
.social-network a.icoDiary:hover {
  background-color:#0590B8;
}
.social-network a.icoLinkedin:hover {
  background-color:#007bb7;
}
.social-network a.icoGitbub:hover i, .social-network a.icoFacebook:hover i, .social-network a.icoTwitter:hover i,
.social-network a.icoGoogle:hover i, .social-network a.icoDiary:hover i, .social-network a.icoLinkedin:hover i {
  color:#fff;
}
a.socialIcon:hover, .socialHoverClass {
  color:#44BCDD;
}

.social-circle li a {
  display:inline-block;
  position:relative;
  margin:0 auto 0 auto;
  -moz-border-radius:50%;
  -webkit-border-radius:50%;
  border-radius:50%;
  text-align:center;
  width: 50px;
  height: 50px;
  font-size:20px;
}
.social-circle li i {
  margin:0;
  line-height:50px;
  text-align: center;
}

.social-circle li a:hover i, .triggeredHover {
  -moz-transform: rotate(360deg);
  -webkit-transform: rotate(360deg);
  -ms--transform: rotate(360deg);
  transform: rotate(360deg);
  -webkit-transition: all 0.2s;
  -moz-transition: all 0.2s;
  -o-transition: all 0.2s;
  -ms-transition: all 0.2s;
  transition: all 0.2s;
}
.social-circle i {
  color: #fff;
  -webkit-transition: all 0.8s;
  -moz-transition: all 0.8s;
  -o-transition: all 0.8s;
  -ms-transition: all 0.8s;
  transition: all 0.8s;
}


</style>
