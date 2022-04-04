<template>

    <!-- Section we are proud -->
    <div class="bg">
        <div class="wrapper_s">
            <div class="row">

                <div class="col-8 offset-2">
                    <div class="txt_wrapper">
                        <h2>We are Proud</h2>
                        <p>Certificate courses are instructed by highly educated and qualified instructors who hold doctoral and master's level degrees.</p>
                    </div>
                </div>

            </div>

            <div class="row">
                <div class="col-12">
                    <div class="d-flex">
                        <div class="txt_wrapper border-end">
                            <h1>2000</h1>
                            <p>STUDENTS</p>
                        </div>

                        <div class="txt_wrapper border-end">
                            <h1>950</h1>
                            <p>COURSE</p>
                        </div>

                        <div class="txt_wrapper border-end">
                            <h1>1600</h1>
                            <p>HOURS VIDEO</p>
                        </div>

                        <div class="txt_wrapper">
                            <h1>150</h1>
                            <p>COUNTRIES RACHED</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "WeProudFile"
}
</script>

<style lang="scss" scoped>
@import "../assets/styles/partials/variables.scss";

    .bg{
        height: 80vh;
        background-color: $light_blue;
        background-image: url("../assets/images/we_proud.png");
        background-position: bottom;
        background-repeat: no-repeat;
        .col-8{
            .txt_wrapper{
                margin: 6rem 0;
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
        .col-12{
            .txt_wrapper{
                width: 25%;
                text-align: center;
                padding-top: 2rem;
                padding-bottom: 1rem;
                h1{
                    font-size: 70px;
                }
                p{
                    font-size: 22px;
                    font-weight: 200;
                    text-transform: uppercase;
                    margin: 0;
                }
            }
        }
    }
</style>