<template>
    <div class="flex w-full dark:bg-[#161925] dark:text-white">
        <div class="w-[20%] h-full">
            <div class="h-[30%] px-8 py-3">
                <a class="w-[70%] font-bold text-[35px] font-['cursive']">Yocity</a>
            </div>
            <div class="h-[70%] bg-blue-500">
                <SideBar></SideBar>
            </div>
        </div>
        <div class="w-[80%] h-full">
            <div class="h-[30%]">
                <Header></Header>
            </div>
            <div class="h-[70%]">
                <RouterView />
            </div>
        </div>
    </div>
</template>

<script>
import Header from '../components/Header.vue'
import SideBar from '../components/SideBar.vue'
import { RouterLink, RouterView } from 'vue-router'
export default {
  name: 'Home',
  components: {
    Header,
    SideBar
  },
}
</script>