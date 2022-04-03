<template>
    <header>
        <div class="header_top border-bottom">
            <div class="wrapper_l d-flex align-items-center">
                <select name="" id="" class="me-auto">
                    <option value="english">English</option>
                </select>
                <ul class="d-flex">
                    <li class="p-2"><a href="#">Courses</a></li>
                    <li class="p-2"><a href="#">Zoom</a></li>
                    <li class="p-2"><a href="#">Pages</a></li>
                    <li class="p-2"><a href="#">Bundles</a></li>
                    <li class="p-2"><a href="#">CourseFormats</a></li>
                    <li class="p-2"><a href="#">Add Course</a></li>
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
            </div>
        </div>
        <div class="header-btm">
            <div class="wrapper_l d-flex align-items-center py-3">

                <img src="../assets/images/MasterStudy_logo.svg" alt="master-study_logo" class="me-4">

                <div class="search_section mx-4 d-flex">
                    <select name="" id="">
                        <option value="">CATEGORY</option>
                    </select>
                    <input type="search" name="" id="" placeholder="Search courses">
                    <div><i class="fa-solid fa-magnifying-glass bg-primary text-light p-2"></i></div>
                </div>

                <div class="work_with_us mx-4 d-flex justify-content-between">
                    <span class="p-2"><i class="fa-solid fa-bullhorn mx-1"></i>Become an Instructor</span>
                    <span class="p-2"><i class="fa-solid fa-briefcase mx-1"></i>For Enterprise</span>
                </div>

                <div class="log-in_section ms-4 d-flex justify-content-between">
                    <span class="p-2"><i class="fa-regular fa-user mx-1"></i>Log-in</span>
                    <span class="common_btn p-2">sign-up</span>
                    <a href="#" class="p-2"><i class="fa-regular fa-bookmark"></i></a>
                </div>

            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: 'HeaderFile',
}
</script>

<style lang="scss" scoped>

header{
    margin-bottom: 5rem
}

.search_section{
    width: 50%;
    input{
        width: 400px;
    }
}

.work_with_us{
    width: 25%;
}

.log-in_section{
    width: 25%;
}
</style>
        
