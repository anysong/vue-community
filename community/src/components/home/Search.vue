<template>
    <div class="search">
        <div class="search-wrap">
            <SearchBox></SearchBox>
        </div>
    </div>
</template>

<script>
    import SearchBox from '@/components/home/SearchBox.vue'
    export default {
        name: 'search',
        components: {
            SearchBox
        }
    }
</script>

<style lang="less" scoped>
    .search {
        width: 100%;
        height: 200px;
        background-color: #f3f3f3;
        .search-wrap {
            width: 850px;
            height: 100%;
            margin: 0 auto;
            position: relative;
            box-sizing: border-box;
            padding-top: 80px;
        }
    }
</style>

