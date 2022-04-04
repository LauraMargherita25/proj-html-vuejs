<template>

    <!-- Section newsletter -->
    <div class="bg">
        <div class="wrapper_s">
            <div class="row">

                <div class="col-7">
                    <div class="txt_wrapper">
                    <h5>Subscribe our newsletter</h5>
                    <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words</p>
                    </div>
                </div>

                <div class="col-5">
                    <div class="txt_wrapper">
                        <p class="text-uppercase">your e-mail address</p>
                        <form>
                            <input type="email" placeholder="Enter your E-mail">
                            <div class="btn_subscribe">
                            subscribe
                            </div>
                        </form>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "NewsletterFile"
}
</script>

<style lang="scss" scoped>
@import "../assets/styles/partials/variables.scss";

    .bg{
        background-color: #4ed7a8;
        color: white;
        .txt_wrapper{
            margin: 4rem 0;
            p{
                font-size: 15px;
            }
            input{
                width: 330px;
                border: none;
                padding:  1rem;
                line-height: 0;
                &::placeholder { 
                    color: $gray;
                    opacity: 1;
                    font-size: 15px;
                    padding: 0 1rem;
                }
            }
            .btn_subscribe{
                font-weight: 500;
                text-transform: uppercase;
                background-color: $blue;
                display: inline;
                padding:  1rem;
            }
        }
    }
</style>