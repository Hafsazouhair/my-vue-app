<template>

  <div class=" sidebar w-1/4 pl-20 py-4 ">
    <!--left menu-->
    <div class="ml-6">
    <svg  xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" id="Layer_1" width="24px" height="24px" class="text-white" viewBox="0 0 24 24" style="enable-background:new 0 0 24 24;color: white;" xml:space="preserve">
  <path d="M14.095479,10.316482L22.286354,1h-1.940718l-7.115352,8.087682L7.551414,1H1l8.589488,12.231093L1,23h1.940717  l7.509372-8.542861L16.448587,23H23L14.095479,10.316482z M11.436522,13.338465l-0.871624-1.218704l-6.924311-9.68815h2.981339  l5.58978,7.82155l0.867949,1.218704l7.26506,10.166271h-2.981339L11.436522,13.338465z" fill="white"/>
</svg>
  </div>

    <nav class="mt-5 px-2">
      <a href="#"
        class="group flex items-center px-2 py-2 leading-6 font-semibold rounded-full text-blue-400 hover:text-blue-600">
        <svg class="mr-4 h-6 w-6 text-blue-400" fill="none" stroke-linecap="round" stroke-linejoin="round"
          stroke-width="2" stroke="currentColor" viewBox="0 0 24 24">
          <path
            d="M3 12l9-9 9 9M5 10v10a1 1 0 001 1h3a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1h3a1 1 0 001-1V10M9 21h6" />
        </svg>
        <span class="text-blue-400">Home</span>
      </a>
      <a href="#"
        class="group flex items-center px-2 py-2 leading-6 font-semibold rounded-full text-base text-white hover:text-blue-400">
        <svg class="mr-4 h-6 w-6" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
          stroke-width="2" viewBox="0 0 24 24">
          <path d="M7 20l4-16m2 16l4-16M6 9h14M4 15h14"></path>
        </svg>
        Explore
      </a>
      <a href="#"
        class="mt-1 group flex items-center px-2 py-2 text-base text-white leading-6 font-medium rounded-full   hover:text-blue-300">
        <svg class="mr-4 h-6 w-6" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
          stroke="currentColor" viewBox="0 0 24 24">
          <path
            d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9">
          </path>
        </svg>
        Notifications
      </a>
      <a href="#"
        class="mt-1 group flex items-center px-2 py-2 text-base text-white leading-6 font-medium rounded-full hover:text-blue-300">
        <svg class="mr-4 h-6 w-6" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
          stroke="currentColor" viewBox="0 0 24 24">
          <path
            d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z">
          </path>
        </svg>
        Messages
      </a>
      <a href="#"
        class="mt-1 group flex items-center px-2 py-2 text-base text-white leading-6 font-medium rounded-full hover:text-blue-300">
        <svg class="mr-4 h-6 w-6" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
          stroke="currentColor" viewBox="0 0 24 24">
          <path d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z"></path>
        </svg>
        Bookmarks
      </a>
      <a href="#"
        class="mt-1 group flex items-center px-2 py-2 text-base text-white leading-6 font-medium rounded-fulL  hover:text-blue-300">
        <svg class="mr-4 h-6 w-6" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
          stroke="currentColor" viewBox="0 0 24 24">
          <path
            d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01">
          </path>
        </svg>
        Lists
      </a>
      <a href="#"
        class="mt-1 group flex items-center px-2 py-2 text-base text-white leading-6 font-medium rounded-full  hover:text-blue-300">
        <svg class="mr-4 h-6 w-6" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
          stroke="currentColor" viewBox="0 0 24 24">
          <path d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path>
        </svg>
        Profile
      </a>
      <a href="#"
        class="mt-1 group flex items-center px-2 py-2 text-base text-white leading-6 font-medium rounded-full  hover:text-blue-300">
        <svg class="mr-4 h-6 w-6" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
          stroke="currentColor" viewBox="0 0 24 24">
          <path d="M8 12h.01M12 12h.01M16 12h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
        </svg>
        More
      </a>

      <button class="bg-blue-400 w-48 mt-5 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded-full">
        Tweet
      </button>
    </nav>

    <div class="flex-shrink-0 flex hover:bg-blue-00 rounded-full p-4 mt-12 mr-0">
      <a href="#" class="flex-shrink-0 group block w-96">
        <div class="flex items-center">
          <div>
            <img class="inline-block h-10 w-10 rounded-full"
              src="https://i0.wp.com/fleurdelangle.fr/wp-content/uploads/2023/08/IMG_8694-scaled.jpg?fit=1000%2C1000&ssl=1" alt="" />
          </div>
          <div class="ml-3">
            <p class="text-base leading-6 font-medium text-white ">
            Hafsa Zouhair
            </p>
            <p
              class="text-sm leading-5 font-medium text-gray-400 group-hover:text-gray-300 transition ease-in-out duration-150">
              @hafsazouhair
            </p>
          </div>
        </div>
      </a>
    </div>

  </div>

</template>


<script>
export default {
  name: 'SidebarComponent'
};
</script>

<style scoped>
.sidebar {
  width: 280px;
  height: 180%;
 
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  padding: 4px;
}


</style>