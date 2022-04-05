<template>
    <div class="header_top border-bottom">
        <div class="wrapper_l">
            <nav class="d-flex align-items-center">
                <select name="" id="" class="me-auto">
                    <option value="english">English</option>
                </select>
                <ul class="d-flex">
                    <li class="p-2"><a href="#">Courses</a></li>
                    <li class="p-2">
                        <span class="position-absolute top-0 end-0  badge bg-danger">
                            NEW
                        </span>
                        <a href="#">Zoom</a>
                    </li>
                    <li class="p-2"><a href="#">Pages</a></li>
                    <li class="p-2"><a href="#">Bundles</a></li>
                    <li class="p-2"><a href="#">CourseFormats</a></li>
                    <li class="p-2">
                        <a href="#">Add Course</a>
                        <span class="position-absolute top-0 end-0  badge bg-danger">
                            NEW
                        </span>
                    </li>
                    <li class="p-2"><a href="#">Demos</a></li>
                </ul>
                <ul class="d-flex">
                    <li class="p-2"><a href="#"><i class="fa-brands fa-twitter"></i></a></li>
                    <li class="p-2"><a href="#"><i class="fa-brands fa-instagram"></i></a></li>
                    <li class="p-2"><a href="#"><i class="fa-brands fa-behance-square"></i></a></li>
                    <li class="p-2"><a href="#"><i class="fa-brands fa-dribbble"></i></a></li>
                    <li class="p-2"><a href="#"><i class="fa-brands fa-flickr"></i></a></li>
                    <li class="p-2"><a href="#"><i class="fa-brands fa-git"></i></a></li>
                    <li class="p-2"><a href="#"><i class="fa-brands fa-linkedin"></i></a></li>
                    <li class="p-2"><a href="#"><i class="fa-brands fa-pinterest"></i></a></li>
                </ul>
            </nav>
        </div>
        </div>
</template>

<script>
export default {
    name: 'HeaderTopFile',
}
</script>

<style lang="scss" scoped>
@import "../assets/styles/partials/variables.scss";

    .header_top{
        padding: .5rem 0;
        color: $gray;
        font-size: 13px;
        select{
            font-size: 13px;
            color: $gray;
            border: none;
            background-color: white;
        }
        li{
            position: relative;
            a{
                line-height: 30px;
            }
            .badge{
                padding: 3px;
                font-size: 9px;
                font-weight: 400;
                border-radius: 0;
            }
        }
        i{
            font-size: 15px;
        }
    }
</style>
