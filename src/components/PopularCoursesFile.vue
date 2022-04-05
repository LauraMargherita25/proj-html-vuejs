<template>

    <!-- Section popular courses -->
    <div class="bg">
        <div class="wrapper_l">
            <div class="row">
                <div class="col-8 offset-2">
                    <div class="txt_wrapper">
                        <h2>Popular courses</h2>
                        <p>Discover our most popular courses for self learning</p>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12">
                    <div class="cards_container d-flex flex-wrap">
                        <card-file v-for="course in arrCourses" :key="course.title" :course-data="course" />
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12">
                    <div class="btn_direction">
                        <div class="arrow left">
                            <i class="fa-solid fa-angle-left"></i>
                        </div>
                        <div class="arrow right">
                            <i class="fa-solid fa-angle-right"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import CardFile from './CardFile.vue'
export default {
    name: "PopularCoursesFile",
    components: {
        CardFile
    },
    data() {
        return {
            arrCourses:[
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
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/styles/partials/variables.scss";

    .bg{
        background-color: $light_blue;
        .col-8{
            .txt_wrapper{
                margin: 6rem 0 4rem;
                text-align: center;
                h2{
                    margin-bottom: 2rem;
                }
                p{
                    font-size: 18px;
                    font-weight: 200;
                }
            }
        }
        .cards_container{
            margin-bottom: 5rem;
        }
        .btn_direction{
            display: flex;
            justify-content: center;
            margin-bottom: 5rem;
            .arrow{
                width: 50px;
                height: 50px;
                border: 1px solid $light_gray;
                display: flex;
                align-items: center;
                justify-content: center;
                color: $light_gray;
                background-color: white;
                &:hover{
                    background-color: #457992;
                    color: white;
                    cursor: pointer;
                }
            }
        }
    }
</style>