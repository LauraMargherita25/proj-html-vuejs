<template>
    
    <!-- section cta -->
    <div class="wrapper_s">
        <div class="row">
            <div class="col-7 d-flex align-items-center">
                <div class="txt_wrapper">
                    <h1>Start Investing in You</h1>
                    <p>
                    With over 1200 courses in 18 subjects, you're guaranteed to find
                    something that's right for you.
                    </p>
                    <div class="common_btn">join for free</div>
                </div>
            </div>

            <div class="col-5">
                <div class="img_wrapper">
                    <img src="../assets/images/base.png" alt="" />
                    <img src="../assets/images/book1.png" alt="" class="position-absolute book1"/>
                    <img src="../assets/images/book2.png" alt="" class="position-absolute book2"/>
                    <img src="../assets/images/bubblespeech.png" alt="" class="position-absolute bubblespeech"/>
                    <img src="../assets/images/moon4.png" alt="" class="position-absolute moon"/>
                    <img src="../assets/images/magnifier.png" alt="" class="position-absolute magnifier"/>
                </div>
            </div>
        </div>
    </div>
    
</template>

<script>
export default {
  name: "CtaFile",
};
</script>

<style lang="scss" scoped>
    .wrapper_s{
        margin-bottom: 2rem;
        .txt_wrapper{
            h1{
                margin-bottom: 2rem;
            }
            p{
                font-size: 22px;
                margin-bottom: 2rem;
            }
        }
        .img_wrapper {
            position: relative;
            .book1{
                top: 108px;
                left: 373px;
            }
            .book2{
                top: 275px;
                left: 220px;
            }
            .bubblespeech{
                top: 57px;
                left: 488px;
            }
            .moon{
                top: 122px;
                left: 101px;
            }
            .magnifier{
                top: 320px;
                left: 460px;
            }
        }
    }
</style>
