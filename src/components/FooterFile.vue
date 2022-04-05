<template>
  <footer>
    <div class="wrapper_s">
      <div class="row row-cols-4">

        <div class="col-3">
          <h4>About</h4>
          <p>
            Masterstudy is Education WordPress theme featured by Learning
            Management System (LMS) for online education. Developed by
            StylemixThemes.
          </p>
          <a href="#" v-for="social in arrSocial" :key="social"><i :class="`fa-brands ${social}`"></i></a>
        </div>

        <div class="col-3">
          <h4>Contact</h4>
          <p>USA, Callifornia 20, First Avenue, Callifornia</p>
          <p>Tel.: +1 212 458 300 32</p>
          <p>Fax: +1 212 375 24 14</p>
          <p><a href="">info@masterstudy.com</a></p>
        </div>

        <div class="col-3">
          <h4>Pages</h4>
          <ul>
            <li v-for="link in arrLinks" :key="link"><a href="#">{{ link }}</a></li>
          </ul>
        </div>

        <div class="col-3">
          <h4>Blog</h4>
          <div class="post d-flex mb-3" v-for="post in arrPosts" :key="post.postId">
            <div class="post_img img-fluid">
              <img
                :src="post.img"
                alt="post-image"
              />
            </div>
            <div class="post_content">
              <p>{{ post.text }}</p>
              <p class="date">{{ post.date }}</p>
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
        'fa-facebook',
        'fa-twitter-square',
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
          img: require('../assets/images/photo-1517520287167-4bbf64a00d66-75x75.jpeg'),
          text: 'Our main target is to "Developing Yourself as a Leader"',
          date: '-- August 9, 2018',
        },
        {
          postId: 2,
          img: require('../assets/images/photo-1490376840453-5f616fbebe5b-75x75.jpeg'),
          text: 'Those Other College Expenses You Aren`t Thinking About',
          date: '-- June 3, 2015',
        }
      ]
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/styles/partials/variables.scss";

  .wrapper_s{
    margin-top: 5rem;
    margin-bottom: 3rem;

    font-size: 14px;
    
    h4{
      margin-bottom: 2rem;
    }

    p{
      margin-bottom: 1rem;
    }

    a{
      color: $gray;
    }
    
    i{
      font-size: 20px;
      margin-right: 1rem;
    }

    ul {
      columns: 2;
      list-style: disc;
      padding-left: 15px;
      li{
        margin-bottom: 1rem;
        font-size: 16px;
        a{
          color: black;
        }
      }
    }

    .post_img{
      margin-right: 1rem;
    }

    .post_content{
      p{
        margin-bottom: 0;
        color: $gray;
        font-weight: 600;
        font-size: 13px;
      }
      .date{
        color: $light_gray;
        font-weight: 300;
      }
    }
  }
</style>
