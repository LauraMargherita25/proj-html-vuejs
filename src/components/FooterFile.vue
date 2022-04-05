<template>
  <footer>
    <div class="wrapper_s">
      <div class="row row-cols-4">

        <div class="col-3">
          <h5>About</h5>
          <p>
            Masterstudy is Education WordPress theme featured by Learning
            Management System (LMS) for online education. Developed by
            StylemixThemes.
          </p>
          <a href="#" v-for="social in arrSocial" :key="social"><i :class="`fa-brands ${social}`"></i></a>
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
            <li v-for="link in arrLinks" :key="link"><a href="#">{{ link }}</a></li>
          </ul>
        </div>

        <div class="col-3">
          <h5>Blog</h5>
          <div class="post d-flex mb-3" v-for="post in arrPosts" :key="post.postId">
            <img
              :src="post.img"
              alt="post-image"
              class="me-3"
            />
            <div class="post_content">
              <p class="m-0">{{ post.text }}</p>
              <p class="m-0">{{ post.date }}</p>
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
  data() {
    return {
      arrSocial: [
        'fa-twitter-square',
        'fa-facebook',
        'fa-instagram',
      ],
      arrLinks: [
        'Blog',
        'Home',
        'Shortcodes',
        'Courses',
        'Membership',
        'Typography',
      ],
      arrPosts: [
        {
          postId: 1,
          img: require('../assets/images/photo-1517520287167-4bbf64a00d66-69x69.jpeg'),
          text: 'Our main target is to "Developing Yourself as a Leader"',
          date: '- August 9, 2018',
        },
        {
          postId: 2,
          img: require('../assets/images/photo-1490376840453-5f616fbebe5b-69x69.jpeg'),
          text: 'Those Other College Expenses You Aren`t Thinking About',
          date: '- June 3, 2015',
        }
      ]
    };
  },
};
</script>

<style lang="scss" scoped>
ul {
  columns: 2;
  list-style: disc;
}
</style>
