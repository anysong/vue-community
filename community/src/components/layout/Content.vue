<template>
    <div class="content">
        <Search></Search>
    </div>
</template>
<script>
import Search from '@/components/home/Search.vue'
    export default {
        name: 'content',
        components: {
            Search
        }
    }
</script>

<style lang="less" scoped>
    .content {
        width: 100%;
    }
</style>
