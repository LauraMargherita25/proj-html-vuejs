<template>
    
    <!-- Section recent courses -->
    <div class="wrapper_l">
        <div class="row">
            <div class="col-12">
                
                <h2>Recnt courses</h2>
                <nav>
                    <ul>
                        <li>All Categories</li>
                        <li>Art</li>
                        <li>Exercise</li>
                        <li>Material Design</li>
                        <li>Music</li>
                        <li>Photograohy</li>
                        <li>Software Development</li>
                    </ul>
                </nav>
                
            </div>

            <div class="col-12">
                <div class="cards_container d-flex flex-wrap">
                    <card-file v-for="course in arrCourses" :key="course.title" :course-data="course" />
                </div>
            </div>

            <div class="col-12 text-center">
                <div class="common_btn">
                    show all
                </div>
            </div>
        </div>
    </div>
    
</template>

<script>
import CardFile from './CardFile.vue'
export default {
    name: "RecentCoursesFile",
    components: {
        CardFile
    },
    data() {
        return {
            arrCourses: [
                {
                    thumb: require('../assets/images/photo-1461749280684-dccba630e2f6-272x161.jpeg'),
                    category: 'Apache >',
                    title: 'Web Coding and Apache Basics',
                    duration: '6 hours',
                    price: 'Free',
                },
                {
                    thumb: require('../assets/images/cat_2-272x161.jpg'),
                    category: 'Apache >',
                    title: 'Web Coding and Apache Basics',
                    duration: '6 hours',
                    price: 'Free',
                },
                {
                    thumb: require('../assets/images/course-preview-272x161.jpg'),
                    category: 'Apache >',
                    title: 'Web Coding and Apache Basics',
                    duration: '6 hours',
                    price: 'Free',
                },
                {
                    thumb: require('../assets/images/photo-1496307042754-b4aa456c4a2d-272x161.jpeg'),
                    category: 'Apache >',
                    title: 'Web Coding and Apache Basics',
                    duration: '6 hours',
                    price: 'Free',
                },
                {
                    thumb: require('../assets/images/photo-1416339134316-0e91dc9ded92-scaled-272x161.jpeg'),
                    category: 'Apache >',
                    title: 'Web Coding and Apache Basics',
                    duration: '6 hours',
                    price: 'Free',
                },
                {
                    thumb: require('../assets/images/cathryn-lavery-67852-unsplash-272x161.jpg'),
                    category: 'Apache >',
                    title: 'Web Coding and Apache Basics',
                    duration: '6 hours',
                    price: 'Free',
                },
                {
                    thumb: require('../assets/images/photo-1475452779376-caebfb988090-272x161.jpeg'),
                    category: 'Apache >',
                    title: 'Web Coding and Apache Basics',
                    duration: '6 hours',
                    price: 'Free',
                },
                {
                    thumb: require('../assets/images/cristian-grecu-762012-unsplash-min-scaled-272x161.jpg'),
                    category: 'Apache >',
                    title: 'Web Coding and Apache Basics',
                    duration: '6 hours',
                    price: 'Free',
                },
                {
                    thumb: require('../assets/images/landscape-272x161.jpg'),
                    category: 'Apache >',
                    title: 'Web Coding and Apache Basics',
                    duration: '6 hours',
                    price: 'Free',
                },
                {
                    thumb: require('../assets/images/12345-1-272x161.png'),
                    category: 'Apache >',
                    title: 'Web Coding and Apache Basics',
                    duration: '6 hours',
                    price: 'Free',
                },
                {
                    thumb: require('../assets/images/jakob-owens-198234-unsplash-min-1-272x161.png'),
                    category: 'Apache >',
                    title: 'Web Coding and Apache Basics',
                    duration: '6 hours',
                    price: 'Free',
                },
                {
                    thumb: require('../assets/images/promo_tf-272x161.jpg'),
                    category: 'Apache >',
                    title: 'Web Coding and Apache Basics',
                    duration: '6 hours',
                    price: 'Free',
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/styles/partials/variables.scss";

    .wrapper_l{
        margin-bottom: 7rem;
        h2{
            margin-bottom: 3rem;
            text-align: center;
        }
        ul{
            margin-bottom: 3rem;
            text-align: center;
            li{
                padding: 1rem;
                display: inline;
                color: $blue;
                font-size: 15px;
                &:hover{
                    background-color: $light_blue;
                    color: $gray;
                    border-radius: 50px;
                }
            }
        }
        .card_container{
            margin-bottom: 3rem;
        }
    }
</style>