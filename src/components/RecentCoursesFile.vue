<template>
    
    <!-- Section recent courses -->
    <div class="wrapper_l">
        <div class="row">
            <div class="col-12">
                
                <h2>Recnt courses</h2>
                <nav>
                    <ul>
                        <li>All Categories</li>
                        <li>Art</li>
                        <li>Exercise</li>
                        <li>Material Design</li>
                        <li>Music</li>
                        <li>Photograohy</li>
                        <li>Software Development</li>
                    </ul>
                </nav>
                
            </div>

            <div class="col-12">
                <div class="card_container">

                </div>
            </div>

            <div class="col-12 text-center">
                <div class="common_btn">
                    show all
                </div>
            </div>
        </div>
    </div>
    
</template>

<script>
export default {
    name: "RecentCoursesFile"
}
</script>

<style lang="scss" scoped>
@import "../assets/styles/partials/variables.scss";

    .wrapper_l{
        margin-bottom: 7rem;
        h2{
            margin-bottom: 3rem;
            text-align: center;
        }
        ul{
            margin-bottom: 3rem;
            text-align: center;
            li{
                padding: 1rem;
                display: inline;
                color: $blue;
                font-size: 15px;
                &:hover{
                    background-color: $light_blue;
                    color: $gray;
                    border-radius: 50px;
                }
            }
        }
        .card_container{
            margin-bottom: 3rem;
        }
    }
</style>