<template>
    <div id="main">
        <Header title="个人中心"/>
        <div id="content">
            <login/>
            <!-- <router-view></router-view> -->
        </div>
        <tabBar/>
    </div>
</template>
<script>
import Header from '@/components/Header';
import tabBar from '@/components/TabBar';
import login from '@/components/Login';

export default {
    name : 'mine',
    components : {
        Header,
        tabBar,
        login
    }
}
</script>

<style scoped>

</style>