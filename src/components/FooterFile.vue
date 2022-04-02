<template>
  <footer>
    <div class="container">
      <div class="row row-cols-4">
        <div class="col-3">
          <h5>About</h5>
          <p>
            Masterstudy is Education WordPress theme featured by Learning
            Management System (LMS) for online education. Developed by
            StylemixThemes.
          </p>
        </div>

        <div class="col-3">
          <h5>Contact</h5>
          <p>USA, Callifornia 20, First Avenue, Callifornia</p>
          <p>Tel.: +1 212 458 300 32</p>
          <p>Fax: +1 212 375 24 14</p>
          <p>info@masterstudy.com</p>
        </div>

        <div class="col-3">
          <h5>Pages</h5>
          <ul>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Home</a></li>
            <li><a href="#">Shortcodes</a></li>
            <li><a href="#">Courses</a></li>
            <li><a href="#">Membership</a></li>
            <li><a href="#">Typography</a></li>
          </ul>
        </div>

        <div class="col-3">
          <h5>Blog</h5>
          <div class="post d-flex mb-3">
            <img
              src="../assets/images/photo-1517520287167-4bbf64a00d66-69x69.jpeg"
              alt="post-image"
              class="me-3"
            />
            <div class="post_content">
              <p class="m-0">Our main target is to "Developing Yourself as a Leader"</p>
              <p class="m-0">-August 9, 2018</p>
            </div>
          </div>
          <div class="post d-flex mb-3">
            <img
              src="../assets/images/photo-1517520287167-4bbf64a00d66-69x69.jpeg"
              alt="post-image"
              class="me-3"
            />
            <div class="post_content">
              <p class="m-0">Our main target is to "Developing Yourself as a Leader"</p>
              <p class="m-0">-August 9, 2018</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "MainFile",
};
</script>

<style lang="scss" scoped>
ul{
  columns: 2;
  list-style: disc;
}
</style>
