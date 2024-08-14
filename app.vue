<template>
  <div :class="{'dark': darkMode}">
    
     <div class="min-h-full">

      <div class="grid grid-cols-12 mx- auto sm:px6 lg:max-w-7xl lg:px-8 lg:gap-5">

        <!-- F-LEft -->
        <div class="bg-red-500 md:block xs-col-span-1 xl:col-span-2">
          <div class="sticky top-0"><SidebarLeftSide/></div>
        </div>
         

        <!-- 2 -->


        <!-- 3 -->


      </div>

     </div>




  </div>
</template>
<script setup>
const darkMode = ref(false) //?

</script>
