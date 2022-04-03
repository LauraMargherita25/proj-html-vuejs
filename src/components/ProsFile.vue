<template>
   
        <!-- Section our courses's pros -->
        <div class="wrapper_s">
            <div class="row">
                <div class="col-4">
                    <div class="card_pros">
                        <i class="fa-solid fa-earth-americas"></i>
                        <p>Worldwide Recognize</p>
                        <small>
                        Our online course certificates can be used around the world and
                        also in most popular universities and companies.
                        </small>
                    </div>
                </div>

                <div class="col-4">
                    <div class="card_pros">
                        <i class="fa-solid fa-desktop"></i>
                        <p>Mostly Online Learning (sd)</p>
                        <small>
                        Masterstudy online certificates can be obtained in a range of
                        specialized areas and typically take about a year to complete.
                        </small>
                    </div>
                </div>

                <div class="col-4">
                    <div class="card_pros">
                        <i class="fa-regular fa-calendar-check"></i>
                        <p>Graduate in as little as 1 Year</p>
                        <small>
                        Online post-graduate certificates are a popular way to develop
                        your professional qualifications of Masterstudy.
                        </small>
                    </div>
                </div>
            </div>
        </div>

</template>

<script>
export default {
  name: "ProsFile",
};
</script>

<style lang="scss" scoped>
@import "../assets/styles/partials/variables.scss";

    .wrapper_s{
        margin-bottom: 7rem;

        .card_pros{
            padding: 2rem;
            background-color: $light_blue;
            p{
                margin-bottom: 1rem;
            }
            small{
                color: #838a97;
                font-size: 13.5px;
            }
            i{
                color: $blue;
                font-size: 60px;
                margin-bottom: 1rem;
            }
        }
    }
</style>
