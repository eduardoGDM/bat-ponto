<template>
   <div>
     <div class="d-flex flex-column">
    <NavBar/>
    <SideBar/>
    <LoginCard/>
    </div>
  </div>
</template>

<script>
import SideBar from '@/components/SideBar.vue'
import NavBar from  '@/components/NavBar.vue'
import LoginCard from  '@/components/LoginCard.vue'

export default {
  name: 'Home',
  components: {
    SideBar,
    NavBar,
    LoginCard
  }
}
</script>

