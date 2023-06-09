<template>
 <nav class="bg-white border-gray-200 px-2 sm:px-4 py-2.5 rounded dark:bg-gray-800">
  <div class="flex flex-wrap items-center justify-between max-w-screen-xl p-4 mx-auto">
   <Logo />
   <UserInfo />
   <NavigationLinks />
  </div>
 </nav>
</template>

<script>
import Logo from './logo.vue'
import NavigationLinks from './NavigationLinks.vue'
import UserInfo from './UserInfo.vue'

export default {
 name: 'NavbarComponent',
 components: {
  Logo,
  NavigationLinks,
  UserInfo
 }
}
</script>
