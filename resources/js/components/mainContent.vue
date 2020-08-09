<template>
  <div>
    <div data-aos="fade-up" class="wrapper">
      <div class="card a img-fluid" alt="Responsive image"></div>
      <div class="card b img-fluid" alt="Responsive image"></div>
      <div class="card c img-fluid" alt="Responsive image"></div>
      <div class="card d img-fluid" alt="Responsive image"></div>
    </div>

    <div id="gold" class="col l1 center-align">_______________</div>
    <p id="skills" data-aos="fade-up" class="col l1 center-align">Skills</p>

    <div class="wrapper-skill">
      <img
        data-aos="fade-up"
        data-aos-duration="500"
        class="img-fluid"
        src="https://img.icons8.com/color/32/000000/adobe-premiere-pro.png"
      />
      <p data-aos="fade-up" data-aos-duration="500" class="skills-text">Premiere Pro</p>
      <img
        data-aos="fade-up"
        data-aos-duration="800"
        class="img-fluid"
        src="https://img.icons8.com/color/32/000000/adobe-photoshop.png"
      />
      <p data-aos="fade-up" data-aos-duration="800" class="skills-text">Photoshop</p>
      <img
        data-aos="fade-up"
        data-aos-duration="1100"
        class="img-fluid"
        src="https://img.icons8.com/color/32/000000/compact-camera.png"
      />
      <p data-aos="fade-up" data-aos-duration="1100" class="skills-text">Video/Photography</p>
      <img
        data-aos="fade-up"
        data-aos-duration="1400"
        class="img-fluid"
        src="https://img.icons8.com/color/32/000000/system-task.png"
      />
      <p
        data-aos="fade-up"
        data-aos-duration="1400"
        class="skills-text"
      >HTML, CSS, PHP, MySQL, JavaScript</p>
      <img
        data-aos="fade-up"
        data-aos-duration="1700"
        class="img-fluid"
        src="https://img.icons8.com/color/32/000000/api-settings.png"
      />
      <p data-aos="fade-up" data-aos-duration="1700" class="skills-text">Rest API</p>
      <img
        data-aos="fade-up"
        data-aos-duration="1000"
        class="img-fluid"
        src="https://img.icons8.com/color/32/000000/source-code.png"
      />
      <p
        data-aos="fade-up"
        data-aos-duration="1000"
        class="skills-text"
      >Vue, vuejs, Laravel, Bootstrap, Materialize, Jquery, JS Frameworks/Libraries</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "mainContent",
};
</script>

<style scoped>
.wrapper {
  display: grid;
  grid-gap: 270px;
  grid-template-columns: repeat(auto-fill, 100px);
}

.card {
  font-size: 150%;
}

.a {
  grid-column: 1 / 3;
  width: 740px;
  height: 445px;
  background: url("https://64.media.tumblr.com/8f331196c04be85b70582742b183f0dd/7a178890964a5f2f-43/s1280x1920/d4ed3bf57f43b1311ee5b5ae75932b41453b3cf8.jpg")
    no-repeat;
  background-size: 740px 445px;
}
.a:hover {
  background: url("https://i.imgur.com/m9wqM0v.jpg") no-repeat;
  background-size: 740px 445px;
}

.b {
  grid-column: 3 / 5;
  width: 742px;
  height: 445px;
  background: url("https://64.media.tumblr.com/828526730a20ea1d67b7faab59b0f669/7a178890964a5f2f-ab/s1280x1920/bbff0e5edee7ffd8827f3f2a5c85874670b31829.jpg")
    no-repeat;
  background-size: 742px 445px;
}
.b:hover {
  background: url("https://64.media.tumblr.com/aa881c2b46c8ec9038ec9d26c599783f/e6e8a06417aa408d-c9/s540x810/325be22c373633a06cebbf0822fa422bd49eb48f.gifv")
    no-repeat;
  background-size: 742px 445px;
}

.c {
  bottom: 300px;
  grid-column: 1 / 3;
  width: 740px;
  height: 445px;
  background: url("https://64.media.tumblr.com/c211c04233f5d1d0d2ef701b36853aca/7a178890964a5f2f-f5/s1280x1920/b8a78319027158d987635f73d74fe04f103837fd.jpg")
    no-repeat;
  background-size: 740px 445px;
}
.c:hover {
  background: url("https://64.media.tumblr.com/903b3d9e43abd9abc9dd1320ed447173/9bca164bfb878a80-0d/s640x960/744ba3c3e02f0e3bee782d9ace003cfe6a7fe1ca.gifv")
    no-repeat;
  background-size: 740px 445px;
}

.d {
  bottom: 300px;
  grid-column: 3 / 5;
  width: 742px;
  height: 445px;
  background: url("https://64.media.tumblr.com/af3512844156c28c28d3b3634b078ff3/7a178890964a5f2f-b1/s1280x1920/691cdc5a7b220f8402bfc394553d205eebc472e7.jpg")
    no-repeat;
  background-size: 742px 445px;
}
.d:hover {
  background: url("https://64.media.tumblr.com/a60c4b735777ce398d6ade29829c6642/9bca164bfb878a80-50/s640x960/aaefe4a9682f4d98500d8610191cf64e91a43cab.gifv")
    no-repeat;
  background-size: 742px 445px;
}

#gold {
  color: #d4b156;
  margin-bottom: 50px;
}
#skills {
  color: lightgray;
  font-size: 40px;
  letter-spacing: 6px;
  font-family: "Playfair Display", serif;
  margin-bottom: 100px;
}

.wrapper-skill {
  display: grid;
  margin: 100px;
  grid-gap: 100px;
  grid-template-columns: repeat(auto-fill, 100px);
}

.skills-text {
  color: lightgray;
  font-size: 15px;
  font-family: "Montserrat", sans-serif;
}
</style>
