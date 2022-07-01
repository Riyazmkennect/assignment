<template>
  <div>
    <div class="flex flex-col items-center justify-center h-screen">
      <div class="p-4">
        <div class="text-center"> Hey User You have sucessfully Logged in</div>
        
      </div>
      <div class="bg-green-600 text-white rounded-full py-3 px-6 shadow-lg">
        <NuxtLink to="/podcast" class="text-center"
          >Continue to join PodCast</NuxtLink
        >
      </div>
      <div class="bg-blue-400 text-white rounded-full py-3 px-6 shadow-lg">
        <NuxtLink to="/podcaster" class="text-bottom"
          >Continue to join PodCaster</NuxtLink
        >
      </div>
      <div class="bg-red-400 text-white rounded-full py-3 px-6 shadow-lg">
        <NuxtLink to="/" class="text-bottom"
          >Exit</NuxtLink
        >
      </div>
       <div class="bg-blue-400 text-white rounded-full py-3 px-6 shadow-lg">
        <NuxtLink to="/choice" class="text-bottom"
          >pratice</NuxtLink
        >
      </div>
    </div>
  </div>
</template>



