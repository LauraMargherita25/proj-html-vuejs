<template>
    <!-- Section more info -->
    <div class="bg">
        <div class="wrapper_s">
            <div class="row h-100">
                <div class="col-6 d-flex align-items-center">
                    <div class="txt_wrapper">
                        <h2>Limitless learning, more possibilities</h2>
                        <p>Online courses open the opportunity for learning to almost anyone, regardless of their scheduling commitments.</p>
                        <div class="common_btn">
                        read more
                        </div>
                    </div> 
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "ReadMoreFile"
}
</script>

<style lang="scss" scoped>
    .bg{
        height: 60vh;
        background-image: url("../assets/images/Untitled-1-1-1-1-1.png");
        margin-bottom: 6rem;
        .wrapper_s{
            height: 60vh;
            h2{
                margin-bottom: 2rem;
            }
            p{
                font-size: 23px;
                font-weight: 300;
                margin-bottom: 2rem;
            }
        }
    }
</style>