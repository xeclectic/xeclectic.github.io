<template>
<!-- Header Text and stripe -->
  <div>
    <section id="header">
      <div id="top-accent">
        <br />
        <div class="row" id="head-links">
          <p class="col l8 center-align">__________</P>
          <a href="#goldBreak" id="link1" class="col l1 center-align">My Work</a>
          <a id="link2" class="col l1 center-align" href="#aboutMe">Skills</a>
          <a id="link3" class="col l1 center-align" href="#codeImg">Contact</a>
        </div>
      </div>
      <div id="avatar-bg"></div>

    <!-- Header Background -->
      <img class="img-fluid" alt="Responsive image"
        id="avatar"
        src="https://66.media.tumblr.com/b48361b922751a12e4c3acf29fa62ffe/d5ee1569c5b8213c-d3/s540x810/636aadd979179ea52e24ebfab80fb88246ab9567.jpg"
      />
      <img class="img-fluid" alt="Responsive image"
        id="header-bg"
        src="https://64.media.tumblr.com/eb9d486478217382f8dd7e9906c117f8/ffdb3a6ffe4e1243-62/s1280x1920/5b848d4725d802706ba496bcf052ffcbbf3bb7d1.jpg"
      />

    <!-- Name Text -->
      <p id="name" class="col l12 center-align">
        HI! I'M HAILEY FOSS</p>
        <br/>
        <p id="name-text" class="col l12 center-align">| junior full-stack web developer |</p>
      <div>
    <!-- Arrow -->
        <div class="arrow">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>
<!-- Gold Break -->
<div class="row">
    <p id="goldBreak" class="col s12 m12 l12 center-align">___________</p>
    </div>
    <!-- Check out my works -->
    <div>
        <br/>
        <p data-aos="fade-up" id="welcome" class="col l12 center-align">WELCOME</p>
        <br/>
        <p id="welcome-text" class="col l12 center-align">
            I am a passionate web developer with a year of working in a challenging enviornment at Innotech
            college where I obtained a my degree.
            <br/>
            Apart from my growing interest in development I have a background in design, photography
            and over thirteen years of video production and editing experience.
            <br/>
            I am seeking opportunity to use each skillset to create engaging and emotive websites.
            <br/>
            Drop me a line and lets chat about your project!</p>
    </div>
    <br>
    <button class="button button1" href="#contact" >Contact Me</button>
    </section>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
}

.button {
    position: relative;
    left: 45vw;
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  display: inline-block;
  font-size: 16px;
  transition-duration: 0.4s;
  cursor: pointer;
}

.button1 {
  background-color: #1C1A19;
  color: lightgray;
  border: 2px solid lightgray;
  margin-bottom: 200px;
}

.button1:hover {
  background-color: lightgray;
  color: #1C1A19;
}

#welcome{
    color: lightgray;
    font-size: 40px;
    letter-spacing: 4px;
    font-family: 'Playfair Display', serif;
}
#welcome-text, #contact-text{
    color: lightgrey;
    font-size: 15px;
    font-family: 'Montserrat', sans-serif;
}
#goldBreak {
    position: relative;
    color:#D4B156;
    width: 10vw;
    font-size: 3vh;
    left: 44rem;

}
#name {
  color: lightgray;
  position: relative;
  bottom: 40vh;
  font-size: 40px;
  letter-spacing: 4px;
  font-family: 'Playfair Display', serif;
}
#name-text{
    color: lightgray;
  position: relative;
  bottom: 40vh;
  font-size: 15px;
  font-family: 'Montserrat', sans-serif;
}

#link1,
#link2,
#link3,
#link4 {
  color: white;
  margin-right: 10px;
}
#link1:hover,
#link2:hover,
#link3:hover,
#link4:hover {
  background-color:#D4B156;
}
#top-accent {
  position: absolute;
  width: 100%;
  height: 1vh;
  background-color: #D4B156;
}
#head-links {
  left: 20vh;
}
#avatar {
  position: absolute;
  width: 200px;
  height: 200px;
  border-radius: 50%;
  left: 650px;
  top: 30vh;
}
#avatar-bg {
  position: absolute;
  width: 210px;
  height: 210px;
  border-radius: 50%;
  background-color: #D4B156;
  left: 43vw;
  top: 30vh;
}
#header-bg {
  width: 100%;
  height: 100vh;
}
.arrow {
  position: absolute;
  top: 92%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.arrow span {
  display: block;
  width: 30px;
  height: 30px;
  border-bottom: 5px solid white;
  border-right: 5px solid white;
  transform: rotate(45deg);
  margin: -10px;
  animation: animate 2s infinite;
}
.arrow span:nth-child(2) {
  animation-delay: -0.2s;
}
.arrow span:nth-child(3) {
  animation-delay: -0.4s;
}
@keyframes animate {
  0% {
    opacity: 0;
    transform: rotate(45deg) translate(-20px, -20px);
  }
  50% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    transform: rotate(45deg) translate(20px, 20px);
  }
}

@media only screen and (max-width: 768px) {
#avatar{
    left: 30vw;
}
#avatar-bg{
    opacity: 0.0;
}
}
</style>
