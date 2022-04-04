<template>
    <!-- Setion feed -->
    <div class="bg">
        <div class="wrapper_s">

            <div class="container_mex">
                <h3>Come as you are</h3>
                <p>
                MasterStudy used is an excellent workshop whether you come as a
                counselor, advisor, administrator, or faculty member. I am going
                home empowered. I am looking forward to attending the On Course
                MasterStudy and the MasterStudy National Conference next year and
                facilitating the use of this excellent retention/student success
                course at my college.
                </p>
                <strong>Tim Sab</strong>
                <small class="d-block">General Developer, Stylemix Themes</small>
            </div>

            <div class="d-flex align-items-center">
                <div class="triangle"></div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "FeedFile"
}
</script>

<style lang="scss" scoped>
    .bg{
        height: 680px;
        background-image: url("../assets/images/brooke-cagle-224821-unsplash-1-1920x700.jpg");
        background-position: bottom;
        .wrapper_s{
            padding: 5rem 0;
            height: 100%;
            display: flex;
            .container_mex{
                width: 735px;
                height: 100%;
                background-color: white;
                padding: 5rem;
                p{
                    margin: 2rem 0;
                    font-size: 18px;
                    font-weight: 200;
                }
            }
            .triangle{
                border-left: 25px solid white;
                border-right: 25px solid transparent;
                border-top: 18px solid transparent;
                border-bottom: 18px solid transparent;
            }
        }
    }
</style>