<template>
  <main>
    <!-- section cta -->
    <div class="cta">
      <div class="container">
        <div class="row">
          <div class="col-7 d-flex align-items-center">
            <div class="txt_wrapper">
              <h1>Start Investing in You</h1>
              <p>With over 1200 courses in 18 subjects, you're guaranteed to find something that's right for you.</p>
              <div class="common_btn">join for free</div>
            </div>
          </div>

          <div class="col-3">
            <div class="img-wrapper">
              <img src="../assets/images/base.png" alt="">
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Section our courses's pros -->
    <div class="courses_pros">
      <div class="container py-5">
        <div class="row">

          <div class="col-4">
            <div class="bg-info p-4 h-100">
              <i class="fa-solid fa-earth-americas fs-1"></i>
              <h2>Worldwide Recognize</h2>
              <p>Our online course certificates can be used around the world and also in most popular universities and companies.</p>
            </div>
          </div>

          <div class="col-4">
            <div class="bg-info p-4 h-100">
              <i class="fa-solid fa-desktop fs-1"></i>
              <h2>Mostly Online Learning (sd)</h2>
              <p>Masterstudy online certificates can be obtained in a range of specialized areas and typically take about a year to complete.</p>
            </div>
          </div>

          <div class="col-4">
            <div class="bg-info p-4 h-100">
              <i class="fa-regular fa-calendar-check fs-1"></i>
              <h2>Graduate in as little as 1 Year</h2>
              <p>Online post-graduate certificates are a popular way to develop your professional qualifications of Masterstudy</p>
            </div>
          </div>

        </div>
      </div>
    </div>

    

    <!-- Section work with us -->
    <div class="work_with_us">
      <div class="my_container py-5">
        <div class="row">

          <div class="col-6">
            <div class="border p-5">
              <img src="../assets/images/image_box_1-221x231.png" alt="">
              <div class="d-inline-block ps-3">
                <h1>Become an Instructor</h1>
                <p>Teach what you love. Masterstudy gives you the tools to create a course.</p>
                <div class="common_btn">
                  start taching
                </div>
              </div>
            </div>
          </div>

          <div class="col-6">
            <div class="border p-5">
              <img src="../assets/images/image_box_2-234x231.png" alt="">
              <div class="d-inline-block ps-3">
                <h1>Setup For Business</h1>
                <p>Get unlimited access to 2,500 of Udemy's top courses for your team.</p>
                <div class="common_btn">
                  doing business
                </div>
              </div>
            </div>
          </div>

        </div>
      </div>
    </div>
    
    <!-- Setion feed -->
    <div class="come_as_u_are">
      <div class="container py-5 h-100 d-flex">
        <div class="col-7 h-100">
          <div class="container_mex bg-light p-5 h-100">
            <h1>Come as you are</h1>
            <p>
              MasterStudy used is an excellent workshop whether you come as a
              counselor, advisor, administrator, or faculty member. I am going
              home empowered. I am looking forward to attending the On Course
              MasterStudy and the MasterStudy National Conference next year and
              facilitating the use of this excellent retention/student success
              course at my college.
            </p>
            <p>Tim Sab</p>
            <p>General Developer, Stylemix Themes</p>
          </div>
        </div>
        <div class="col-3 d-flex align-items-center ">
          <div class="triangle">

          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "MainFile",
};
</script>

<style lang="scss" scoped>
.img_wrapper{
  height: 800px;
  width: 800px;
}
.come_as_u_are {
  height: 70vh;
  background-image: url("../assets/images/brooke-cagle-224821-unsplash-1-1920x700.jpg");
  .triangle{
    border-left: 50px solid whitesmoke;
    border-right: 50px solid transparent;
    border-top: 50px solid transparent;
    border-bottom: 50px solid transparent;
  }
}
</style>
