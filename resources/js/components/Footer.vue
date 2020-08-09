<template>
  <div>
      <div class="col l12 center-align">
          <div id="gold" class="col l12 center-align">______________________</div>
          <p id="contact" class="col l12 center-align">CONTACT</p>
          <br>
          <div id="gold" class="col l12 center-align" >____________________________________________________________________</div>
          <p class=" contact-text col l12 center-align">Email: hailey.foss@hotmail.com</p>
          <br>
          <div id="gold" class="col l12 center-align">_____________________________________________________________________</div>
          <p class="contact-text col l12 center-align"> Phone: 587-436-1642</p>
          <div id="gold" class="col l12 center-align">_____________________________________________________________________</div>
            <button class="button button1" href="https://www.linkedin.com/in/hailey-foss-75974778/" >LinkedIn</button>
          <div class="col l12 center-align" id="gold">____________________________________________________________________</div>
          <img class="col l12 center-align" src="https://img.icons8.com/fluent/96/000000/github.png"/>
          <a href="https://github.com/xeclectic" class="contact-text col l12 center-align"> GitHub</a>
          </div>
    <img id="footer-bg" src="https://images.wallpaperscraft.ru/image/doski_derevyannyj_tekstura_118306_2560x1080.jpg"/>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
#gold {
  color: #d4b156;
  margin-bottom: 50px;
}

#contact {
  color: lightgray;
  font-size: 40px;
  letter-spacing: 6px;
  font-family: "Playfair Display", serif;
  margin-bottom: 100px;
}
.contact-text {
  color: lightgray;
  font-size: 15px;
  font-family: "Montserrat", sans-serif;
}

.button {
    position: relative;
  border: none;
  color: lightgray;
  padding: 16px 32px;
  display: inline-block;
  font-size: 16px;
  transition-duration: 0.4s;
  cursor: pointer;
}

.button1 {
  background-color: #1C1A19;
  color: lightgrey;
  border: 2px solid #d4b156;
  margin-bottom: 50px;
}

.button1:hover {
  background-color: #d4b156;
  color: #1C1A19;
}

#footer-bg{
    width: 98.5vw;
    height: 15vh;
}
</style>
