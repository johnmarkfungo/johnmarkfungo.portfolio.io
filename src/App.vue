<template>
  <nav class="navbar navbar-expand-lg bg-dark navbar-dark py-3 fixed-top">
    <div class="container">
      <a href="#" class="navbar-brand"><i class="bi bi-person-circle"></i> Portfolio Website</a>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navmenu"><span class="navbar-toggler-icon"></span></button>

      <div class="collapse navbar-collapse" id="navmenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a href="#cv" class="nav-link">CV</a>
          </li>
          <li class="nav-item">
            <a href="#projects" class="nav-link">Projects</a>
          </li>
          <li class="nav-item">
            <a href="#about" class="nav-link">About/Skills</a>
          </li>
          <li class="nav-item">
            <a href="#contact" class="nav-link">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- Showcase -->
  <section class="bg-dark text-light p-5 pt-lg-5 text-center text-sm-start">
    <div class="container">
      <div class="d-sm-flex align-items-center">
        <div>
          <h1>Hi, I am<br><span class="text-warning">John Mark</span></h1>
          <h4 class="text-secondary">UI/UX Designer</h4>
          <p class="lead my-4">WE MAKE A WEB <span class="text-warning">A BETTER PLACE</span>
          </p>
          <button class="btn btn-primary btn-lg" data-bs-toggle="modal" data-bs-target="#start">Talk to me!</button>
          <i class="bi bi-github-square"></i>
        </div>
        <img class="img-fluid w-50 d-none d-md-block" src="./assets/my_image.png" alt="my-picture">
      </div>
    </div>
  </section>
  <!--COntact-->
  <div class="modal fade" id="start" tabindex="-1" aria-labelledby="startLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="startLabel">Contact Me!</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <p class="lead">Please fill out all the inputs below!</p>
        <form>
          <div class="mb-3">
            <label for="email" class="col-form-label">Email</label>
            <input type="text" class="form-control" id="email" required>
          </div>
          <div class="mb-3">
            <label for="message" class="col-form-label">Message</label>
            <textarea class="form-control" id="message" col="5" required></textarea>
          </div>
        </form>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="submit" class="btn btn-primary" data-bs-dismiss="modal">Submit</button>
      </div>
    </div>
  </div>
</div>

<!--CV-->

<section class="p-5" id="cv">
  <div class="container bg-primary p-5">
    <h2 class="text-center">Resume</h2>
    <div class="row text-left g-4">
      <div class="col-md">
        <div class="card bg-secondary p-3">
          <h2>John Mark Bo Fungo</h2>
          <a href="#" class="text-light">fungojohnmark@gmail.com</a>
          <hr>
          <h2><i class="bi bi-archive-fill"></i>Objective</h2>
          <p class="text-lead text-light">To gain more experiences.</p>
          <hr>
          <h2><i class="bi bi-archive-fill"></i>Personal Information</h2>
          <ul>
            <li class="text-dark">Birthdate:</li>
            <p class="text-lead text-light">November 09, 2001</p>
            <li class="text-dark">Civil Status:</li>
            <p class="text-lead text-light">Single</p>
            <li class="text-dark">Nationality</li>
            <p class="text-lead text-light">Filipino</p>
            <li class="text-dark">Sex</li>
            <p class="text-lead text-light">Male</p>
          </ul>
          <hr>
          <h2><i class="bi bi-archive-fill"></i>Contact Information</h2>
          <ul>
            <li class="text-dark">Mobile:</li>
            <p class="text-lead text-light">09636751794</p>
            <li class="text-dark">Email:</li>
            <p class="text-lead text-light">fungojohnmark@gmail.com</p>
          </ul>
          <hr>
          <h2><i class="bi bi-archive-fill"></i>Skills</h2>
          <ul>
            <li class="text-lead text-light">HTML</li>
            <li class="text-lead text-light">CSS</li>
          </ul>
          <h2><i class="bi bi-archive-fill"></i>Languages</h2>
          <ul>
            <li class="text-lead text-light">Filipino</li>
            <li class="text-lead text-light">English</li>
          </ul>
        </div>
      </div>
      <div class="col-md">
        <div class="card bg-secondary p-3">
          <h2><i class="bi bi-archive-fill"></i>Education</h2>
          <ul>
            <li>2019 Apr</li>
            <p class="text-lead text-light" style="font-weight: bold;">Senior High School Diploma</p>
            <p class="text-lead text-light">San Roque National High School</p>
            <p class="text-lead text-light">Major BSIT</p>
            <p class="text-lead text-light">Field of Study: Academic Track: General Academic Strand (GAS)</p>
          </ul>
          <hr>
          <h2><i class="bi bi-archive-fill"></i>Certification</h2>
          <p class="text-lead text-light">2020</p>
          <p  class="text-lead text-light"><strong>HTML Course In SoloLearn.com</strong></p>
          <hr>
          <h2><i class="bi bi-archive-fill"></i>References</h2>
          <p class="text-lead text-light"><strong>Grace Lani Fulleros</strong></p>
          <ul>
            <li class="text-lead text-light">High School Teacher</li>
            <li class="text-lead text-light">Teacher III</li>
            <li class="text-lead text-light">San Roque National High School</li>
            <li class="text-lead text-light">09479557964</li>
          </ul>
          <p class="text-lead text-light"><strong>Mark Anthony Gacis</strong></p>
          <ul>
            <li class="text-lead text-light">College Teacher</li>
            <li class="text-lead text-light">MIT</li>
            <li class="text-lead text-light">Sorsogon State University Bulan Campus</li>
            <li class="text-lead text-light">09998009597</li>
          </ul>
        </div>
        <a href="./assets/John Mark-Fungo-Resume.pdf" download="Fungo-JohnMark-Resume" class="btn btn-dark m-3"><i class="bi bi-arrow-down-circle"></i>Download CV</a>
      </div>
    </div>
  </div>
</section>

<!--Projects-->

<section class="p-5" id="projects">
    <div class="container">
      <h1 class="text-primary mb-3">PROJECTS</h1>
      <div class="row text-center g-4">
        <div class="col-md">
          <div class="card bg-dark text-light p-3">
            <div class="h1 mb-3">
              <i class="bi bi-controller"></i>
            </div>
            <h3 class="class-title mb-3">
              Monster Slayer Game
            </h3>
            <p class="card-text">
              A web-based simple fight game between you and the monster.
            </p>
            <a :href="linkMonster" target="_blank" class="btn btn-primary mb-2"><i class="bi bi-github"></i> View Source Code</a>
            <a :href="playMonster" target="_blank" class="text-dark" style="text-decoration: none; background: #eee; width: 50%; margin: auto"><i class="bi bi-play"></i> Play</a>
          </div>
        </div>
        <div class="col-md">
          <div class="card bg-secondary text-light p-3">
            <div class="h1 mb-3">
              <i class="bi bi-book"></i>
            </div>
            <h3 class="class-title mb-3">
              Learning Resources App
            </h3>
            <p class="card-text">
              A website which you can store some learning resources online.
            </p>
            <a :href="linkLearn" target="_blank" class="btn btn-dark mb-2"><i class="bi bi-github"></i> View Source Code</a>
            <a :href="learnResource" target="_blank" class="text-light" style="text-decoration: none; background: #000; width: 50%; margin: auto"><i class="bi bi-play"></i> Learn</a>
          </div>
        </div>
        <div class="col-md">
          <div class="card bg-dark text-light p-3">
            <div class="h1 mb-3">
              <i class="bi bi-search"></i>
            </div>
            <h3 class="class-title mb-3">
              Find A Coach App
            </h3>
            <p class="card-text">
              A website which you can find a coach or register as a coach
            </p>
            <a :href="linkFindCoach" target="_blank" class="btn btn-primary mb-2"><i class="bi bi-github"></i> View Source Code</a>
            <a :href="findCoach" target="_blank" class="text-dark" style="text-decoration: none; background: #eee; width: 50%; margin: auto"><i class="bi bi-play"></i>Search</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ABout -->

  <secttion class="p-5" id="about">
     <div class="container p-5">
       <h2>Skills</h2>
       <h4><i class="bi bi-html"></i>HTML 5</h4>
       <div class="progress mb-5">
  <div class="progress-bar progress-bar-success" role="progressbar" aria-valuenow="40"
  aria-valuemin="0" aria-valuemax="100" style="width:70%">
    70%
  </div>
</div>
<h4><i class="bi bi-html"></i>CSS 3</h4>
<div class="progress mb-5">
  <div class="progress-bar progress-bar-info" role="progressbar" aria-valuenow="50"
  aria-valuemin="0" aria-valuemax="100" style="width:80%">
    80%
  </div>
</div>
<h4><i class="bi bi-html"></i>PHOTOSHOP</h4>
<div class="progress mb-5">
  <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60"
  aria-valuemin="0" aria-valuemax="100" style="width:60%">
    60%
  </div>
</div>
<h4><i class="bi bi-html"></i>VUE JS</h4>
<div class="progress mb-5">
  <div class="progress-bar progress-bar-danger" role="progressbar" aria-valuenow="70"
  aria-valuemin="0" aria-valuemax="100" style="width:40%">
    40%
  </div>
</div> 
     </div>
  </secttion>

<!-- COntact Info -->

  <section class="p-5" id="contact">
    <div class="container">
      <div class="row g-4">
        <div class="col-md">
          <h2 class="text-center mb-4">
            Contact Info
          </h2>
          <ul class="list-group list-group-flush lead">
            <li class="list-group-item">
              <span class="fw-bold"><i class="bi bi-geo-alt"></i> Main Location: </span>San, Roque, Bulusan, Sorsogon
            </li>
            <li class="list-group-item">
            <iframe :src="myLocation" width="300" height="200" style="border:0;" loading="lazy"></iframe>
            </li>
            <li class="list-group-item">
              <span class="fw-bold"><i class="bi bi-phone"></i> Mobile Phone: </span>+639636751794
            </li>
            <li class="list-group-item">
              <span class="fw-bold"><i class="bi bi-envelope"></i> Personal Email: </span>fungojohnmark@gmail.com
            </li>
          </ul>
        </div>
      </div>
      <button class="btn btn-primary btn-lg mt-2" data-bs-toggle="modal" data-bs-target="#start">Talk to me!</button>
      <div class="d-flex mt-4">
        <a href="https://www.facebook.com/johnmark.fungo" target="_blank" class="mx-3"><h2 class="bi bi-facebook"></h2></a>
      <a href="https://www.instagram.com/invites/contact/?i=6rpqil9ple4p&utm_content=2kh1sp9" target="_blank" class="mx-3"><h2 class="bi bi-instagram"></h2></a>
      <a href="https://github.com/johnmarkfungo" target="_blank" class="mx-3"><h2 class="bi bi-github"></h2></a>
      <a href="#" class="mx-3"><h2 class="bi bi-linkedin"></h2></a>
      </div>
    </div>
  </section>

  <footer class="p-5 bg-dark text-white text-center position-relative">
    <div class="container">
      <p class="lead">Copyright &copy; 2021 John Mark Fungo - BSIT 3-D</p>
      <a href="#" class="position-absolute bottom-0 end-0 p-5"><i class="bi bi-arrow-up-circle h1"></i></a>
    </div>
  </footer>
</template>

<script>
export default {
  data(){
    return{
      linkMonster: 'https://github.com/johnmarkfungo/Lesson-4-Monster-Slayer-Game',
      playMonster: 'https://johnmarkfungo.github.io/Lesson-4-Monster-Slayer-Game/',
      linkLearn: 'https://github.com/johnmarkfungo/learning-resources-app',
      learnResource: 'https://learning-resource-app-65b83.firebaseapp.com/',
      linkFindCoach: 'https://github.com/johnmarkfungo/find-a-coach-web-app',
      findCoach: 'https://find-a-coach-john-mark-fungo.firebaseapp.com/',
      myLocation: 'https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d37975.7421175196!2d124.06269818637112!3d12.746546572584538!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x33a0c6918fa806d1%3A0x281185299c0be16d!2sSan%20Roque%2C%20Sorsogon!5e0!3m2!1sen!2sph!4v1638975182598!5m2!1sen!2sph'
    }
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;0,500;1,300&display=swap');
*{
	box-sizing: border-box;
	font-family: 'Roboto', sans-serif;
}
html{
	scroll-behavior: smooth;
}
body{
	margin: 0;
	padding: 0;
}
body::before{
    display: block;
    content: '';
    height: 60px;
}
a{
  text-decoration: none;
}
@media(min-width: 768px){
  .news-input{
    width: 50%;
  }
}
</style>