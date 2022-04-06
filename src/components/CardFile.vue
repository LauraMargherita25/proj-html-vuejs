<template>
  <div class="card_container">
    <img :src="courseData.thumb" alt="course image" class="img-fluid">
    <div class="card_main">
        <p class="card_category">{{ courseData.category }}</p>
        <p>{{ courseData.title }}</p>
        <hr>
    </div>
    <div class="card_footer">
        
        <div v-show="courseData.ratingState == true">
            <div class="d-flex align-items-center">
                <img src="../assets/images/starfull.svg" alt="">
                <img src="../assets/images/starfull.svg" alt="">
                <img src="../assets/images/starfull.svg" alt="">
                <img src="../assets/images/starfull.svg" alt="">
                <img src="../assets/images/starfull.svg" alt="">
                <span>{{ courseData.rating }}</span>
            </div>
        </div>

        <div v-show="courseData.durationState == true">
            <p class="duration"><i :class="`fa-regular ${courseData.clockIcon}`"></i>{{ courseData.duration }}</p>
        </div>
        <p class="original_price">{{ courseData.originalPrice }}</p>
        <p class="final_price">{{ courseData.finalPrice }}</p>
    </div>
  </div>
</template>

<script>
export default {
    name: "CadFile",
    props: {
      courseData: Object,
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/styles/partials/variables.scss";

    .card_container{
        width: calc((100% / 6) - 1rem);

        border: 1px solid $light_gray;
        margin-left: .5rem;
        margin-right: .5rem;

        background-color: white;
        .card_main{
            padding: 1rem 1rem 0 1rem; 
            p{
                margin-bottom: 1rem;
                font-size: 15px;
            }
            .card_category{
                color: $gray; 
                font-size: 13px;
            }
        }
        .card_footer{
            padding: 0 1rem;
            display: flex;
            justify-content: space-between;
            align-items: start;
            .duration{
                font-size: 13px;
                color: $gray;
                i{
                    margin-right: .5rem;
                }
            }
            .original_price{
                font-size: 13px;
                color: $gray;
                text-decoration: line-through;
            }
            .final_price{
                font-size: 15px;
                font-weight: 500;
            }
        }
        &:hover{
            border: 1px solid orange;
        }
    }
</style>