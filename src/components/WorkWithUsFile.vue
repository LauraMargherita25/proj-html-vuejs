<template>
    
    <!-- Section work with us -->
    <div class="wrapper_l">
        <div class="row">

            <div class="col-6">
                <div class="card_wwf">
                    <img src="../assets/images/image_box_1-221x231.png" alt="">
                    <div class="txt_wrapper">
                        <h3>Become an Instructor</h3>
                        <p>Teach what you love. Masterstudy gives you the tools to create a course.</p>
                        <div class="common_btn">
                        start taching
                        </div>
                    </div>
                </div>
            </div>

            <div class="col-6">
                <div class="card_wwf">
                    <img src="../assets/images/image_box_2-234x231.png" alt="">
                    <div class="txt_wrapper">
                        <h3>Setup For Business</h3>
                        <p>Get unlimited access to 2,500 of Udemy's top courses for your team.</p>
                        <div class="common_btn">
                        doing business
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>
    
</template>

<script>
export default {
    name: "WorkWithUsFile"
}
</script>

<style lang="scss" scoped>
@import "../assets/styles/partials/variables.scss";

    .wrapper_l{
        padding: 6rem 0;
        .card_wwf{
            padding: 5rem 12rem 4rem 2rem;
            border: 1px solid $light_gray;
            display: flex;
            img{
                margin-right: 2.5rem;
            }
            .txt_wrapper{
                h3{
                    margin-top: 1.5rem
                }
                p{
                    font-size: 18px;
                    font-weight: 200;
                    margin: 1.5rem 0;
                }
            }
        }
    }
</style>