<template>
  <div class="header-btm">
            <div class="wrapper_l d-flex align-items-center">

                <img src="../assets/images/MasterStudy_logo.svg" alt="master-study_logo" >

                <div class="search_section d-flex">
                    <div class="select">
                        <i class="fa-solid fa-bars"></i>
                        <span>CATEGORY</span>
                    </div>
                    <div class="search">
                        <input type="search" name="" id="" placeholder="Search courses">
                        <div class="search_btn"><i class="fa-solid fa-magnifying-glass"></i></div>
                    </div>
                </div>

                <div class="work_with_us">
                    <span><i class="fa-solid fa-bullhorn"></i>Become an Instructor</span>
                    <span><i class="fa-solid fa-briefcase"></i>For Enterprise</span>
                </div>

                <div class="account_section">
                    <span class="log-in"><i class="fa-regular fa-user"></i>Log-in</span>
                    <span class="common_btn">sign-up</span>
                    <span class="fav"><i class="fa-regular fa-bookmark"></i></span>
                </div>

            </div>
        </div>
</template>

<script>
export default {
    name: "HeaderBtmFile"
}
</script>

<style lang="scss" scoped>
@import "../assets/styles/partials/variables.scss";

    .header-btm{
        margin-top: 1rem;
    }
   img{
       margin-right: 5rem;
   }
   
   .search_section{
       margin-right: 5rem;
        .select{
            display: flex;
            align-items: center;

            margin-right: 1rem;

            color: $gray;
            font-size: 12px;
            font-weight: 600;
            i{
                color: $gray;
                margin-right: .5rem;
            }
        }
        .search{
            width: 500px;
            display: flex;
            input{
                width: 100%;
                border: none;
                text-indent: 10px;
                &::placeholder{
                    background-color: #f0f2f5;
                }
            }
            .search_btn{
                padding: .8rem 1.5rem;
                background-color: $blue;
                color: white;
            }
        }
    }
   
    .work_with_us{
        margin-right: 5rem;
        font-size: 14px;
        span{
            margin-right: 1.2rem;
            i{
                color: $blue;
                margin-right: .5rem;
            }
        }
    }
   
    .account_section{
        color: $blue;
        .log-in{
            font-size: 14px;
            i{
                margin-right: .5rem;
            }
        }
        .common_btn{
            width: 150px;
            margin: 0 1.5rem;
        }
        .fav{
            font-size: 25px;
        }
    }

</style>