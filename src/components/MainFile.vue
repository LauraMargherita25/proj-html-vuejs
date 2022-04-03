<template>
  <main>
    <cta-file />
    <pros-file />
    <courses-category-file />
    <read-more-file />
    <recent-courses-file />
    <we-proud-file />
    <newsletter-file />
    <popular-courses-file />
    <work-with-us-file />
    <feed-file />
  </main>
</template>

<script>
import CtaFile from './CtaFile.vue'
import ProsFile from './ProsFile.vue'
import CoursesCategoryFile from './CoursesCategoryFile.vue';
import ReadMoreFile from './ReadMoreFile.vue';
import RecentCoursesFile from './RecentCoursesFile.vue'
import WeProudFile from './WeProudFile.vue';
import NewsletterFile from './NewsletterFile.vue';
import PopularCoursesFile from './PopularCoursesFile.vue';
import WorkWithUsFile from './WorkWithUsFile.vue';
import FeedFile from './FeedFile.vue';

export default {
  components: { 
    CtaFile, 
    ProsFile, 
    CoursesCategoryFile, 
    ReadMoreFile, 
    RecentCoursesFile, 
    WeProudFile, 
    NewsletterFile, 
    PopularCoursesFile, 
    WorkWithUsFile, 
    FeedFile },
  name: "MainFile",
};
</script>

<style lang="scss" scoped>

</style>
