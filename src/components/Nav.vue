<template>
  <div class="relative flex items-center justify-between pb-3 border-b border-gray-300">
    <div class="flex flex-1 p-1">
      <label for="search" class="mr-2">
        <img
          src="https://web.elifemall.com.tw/zh/images/icon-search.svg"
          class="w-6"
          alt="search-icon"
        />
      </label>
      <input type="text" class="focus:outline-none" placeholder="熱門文字：..." />
    </div>
    <a href="#" class="flex flex-1 justify-center">
      <img src="https://img.dcity.com.tw/zh/images/logo.svg" class="flex-none" alt="logo" />
    </a>
    <ul class="flex flex-1 items-center justify-end space-x-7">
      <li>
        <a href="#">
          登入
        </a>
      </li>
      <li>
        <a href="#" class="flex items-center py-1.5 px-2 border border-gray-300 rounded-3xl">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5 mr-2"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              d="M3 1a1 1 0 000 2h1.22l.305 1.222a.997.997 0
            00.01.042l1.358 5.43-.893.892C3.74 11.846
            4.632 14 6.414 14H15a1 1 0 000-2H6.414l1-1H14a1 1 0 00.894-.553l3-6A1 1 0 0017
            3H6.28l-.31-1.243A1 1 0 005 1H3zM16 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013
            0zM6.5 18a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"
            />
          </svg>
          購物車
        </a>
      </li>
    </ul>
  </div>
  <!-- <router-link to="/">Home</router-link> |
  <router-link to="/about">About</router-link> -->
</template>

<script>
export default {};
</script>
