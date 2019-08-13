<template>
    <div class="main-content">
        <Main></Main>
        <Aside></Aside>
        <router-view></router-view>
        hivuiviub
    </div>
</template>

<script>
import Main from '@/components/common/Main'
import Aside from '@/components/common/Aside'
export default {
    data() {
        return {
            Main,
            Aside
        }
    },
}
</script>

<style>

</style>
