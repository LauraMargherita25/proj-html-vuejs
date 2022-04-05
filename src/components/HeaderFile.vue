<template>
    <header>
        <header-top-file />
        <header-btm-file />
        
    </header>
</template>

<script>
import HeaderTopFile from './HeaderTopFile.vue';
import HeaderBtmFile from './HeaderBtmFile.vue';

export default {
    name: 'HeaderFile',

    components: {
        HeaderTopFile,
        HeaderBtmFile,
    }
}
</script>

<style lang="scss" scoped>
    header{
    margin-bottom: 5rem
}
</style>
        
