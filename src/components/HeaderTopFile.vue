<template>
    <div class="header_top border-bottom">
        <div class="wrapper_l">
            <nav class="d-flex align-items-center">
                <select name="" id="" class="me-auto">
                    <option value="english">English</option>
                </select>
                
                <ul  class="d-flex">
                    <li class="p-2" v-for="link in arrLinks" :key="link.linkTo">
                        <span class="badge position-absolute top-0 end-0" v-show="link.badge == true">
                            NEW
                        </span>
                        <a href="#">{{ link.linkTo }}</a>
                    </li>
                </ul>

                <ul  class="d-flex">
                    <li class="p-2" v-for="social in arrSocials" :key="social.id"><a href="#"><i :class="social.icon"></i></a></li>
                </ul>
            </nav>
        </div>
        </div>
</template>

<script>
export default {
    name: 'HeaderTopFile',
    data() {
        return {
            arrLinks:[
                {
                    linkTo: 'Courses',
                    badge: false,
                },
                {
                    linkTo: 'Zoom',
                    badge: true,
                },
                {
                    linkTo: 'Pages',
                    badge: false,
                },
                {
                    linkTo: 'Bundles',
                    badge: false,
                },
                {
                    linkTo: 'CourseFormats',
                    badge: false,
                },
                {
                    linkTo: 'Add Course',
                    badge: true,
                },
                {
                    linkTo: 'Demos',
                    badge: false,
                },
            ],
            arrSocials: [
                {
                    id: 'twitter',
                    icon: 'fa-brands fa-twitter',
                },
                {
                    id: 'instagram',
                    icon: 'fa-brands fa-instagram',
                },
                {
                    id: 'behance-square',
                    icon: 'fa-brands fa-behance-square',
                },
                {
                    id: 'dribbble',
                    icon: 'fa-brands fa-dribbble',
                },
                {
                    id: 'flickr',
                    icon: 'fa-brands fa-flickr',
                },
                {
                    id: 'git',
                    icon: 'fa-brands fa-git',
                },
                {
                    id: 'linkedin',
                    icon: 'fa-brands fa-linkedin',
                },
                {
                    id: 'pinterest',
                    icon: 'fa-brands fa-pinterest',
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/styles/partials/variables.scss";

    .header_top{
        padding: .5rem 0;
        color: $gray;
        font-size: 13px;
        select{
            font-size: 13px;
            color: $gray;
            border: none;
            background-color: white;
        }
        li{
            position: relative;
            a{
                line-height: 30px;
            }
            .badge{
                padding: 3px;

                background-color: red;

                font-size: 9px;
                font-weight: 400;
                border-radius: 0;

                position: absolute;
            }
        }
        i{
            font-size: 15px;
        }
    }
</style>
