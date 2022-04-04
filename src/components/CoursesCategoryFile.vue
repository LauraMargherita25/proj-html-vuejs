<template>

    <!-- Section courses category -->
    <div class="wrapper_s">
        
        <div class="row">
            <div class="col-8">
                <img src="../assets/images/cat_1-1540x750.jpg" alt="" class="img-fluid">
                <div class="txt_wrapper d-flex justify-content-between">
                    <span>Software Deevelopment</span>
                    <span>5 Courses</span>
                </div>
            </div>
        
            <div class="col-4">
                <img src="../assets/images/cat_2-740x310.jpg" alt="" class="img-fluid">
                <div class="txt_wrapper d-flex justify-content-between">
                    <span>Art</span>
                    <span>8 Courses</span>
                </div>
                <img src="../assets/images/cat_3-740x310.jpg" alt="" class="img-fluid">
                <div class="txt_wrapper d-flex justify-content-between">
                    <span>Material Design</span>
                    <span>5 Courses</span>
                </div>
            </div>
        </div>
        
        <div class="row">
        
            <div class="col-4">
                <img src="../assets/images/cat_5-740x310.jpg" alt="" class="img-fluid">
                <div class=" txt_wrapper d-flex justify-content-between">
                    <span>Music</span>
                    <span>5 Courses</span>
                </div>
            </div>
        
            <div class="col-4">
                <img src="../assets/images/cat_4-740x310.jpg" alt="" class="img-fluid">
                <div class="txt_wrapper d-flex justify-content-between">
                    <span>Exercise</span>
                    <span>7 Courses</span>
                </div>
            </div>
        
            <div class="col-4">
                <img src="../assets/images/cat_6-740x310.jpg" alt="" class="img-fluid">
                <div class="txt_wrapper d-flex justify-content-between">
                    <span>Photography</span>
                    <span>4 Courses</span>
                </div>
            </div>
        </div>

    </div>
</template>

<script>
export default {
    name: "CoursesCategoryFile"
}
</script>

<style lang="scss" scoped>
    .wrapper_s{
        margin-bottom: 7rem;
        img{
            margin-bottom: 1rem;
        }
        .txt_wrapper{
            padding-bottom: 22px;
        }
    }
</style>