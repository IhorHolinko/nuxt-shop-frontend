<template>
<header class="bg-gray-700 border-b dark:bg-gray-900 dark:border-gray-700 lg:fixed lg:w-full lg:top-0 lg:left-0 lg:z-30">
  <div class="container px-4 py-5 mx-auto space-y-4 lg:space-y-0 lg:flex lg:items-center lg:justify-between lg:space-x-10">
    <div class="flex justify-between">
      <a href="/" class="text-white dark:text-gray-200">
        <div class="flex items-center">
          <p class="text-xl ml-2">Shop <strong>Template</strong></p>
        </div>
      </a>
      <div class="flex items-center space-x-2 lg:hidden">
        <button class="p-1 rounded-md hover:bg-gray-100 dark:hover:bg-gray-800 focus:bg-gray-100 dark:focus:bg-gray-800 focus:outline-none">
          <svg viewBox="0 0 20 20" fill="currentColor" class="w-6 h-6 text-gray-700 dark:text-gray-300">
            <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
          </svg>
        </button>
      </div>
    </div>
    <div class="flex flex-col space-y-4 lg:hidden">
      <div class="flex flex-col space-y-3 lg:space-y-0 lg:flex-row lg:space-x-6 xl:space-x-8 lg:items-center">
        <div class="relative inline-block hidden lg:block">
          <div>
            <button class="text-gray-500 dark:text-gray-200 hover:text-gray-800 dark:hover:text-gray-400 transition-colors duration-300 flex items-center space-x-1 focus:outline-none"><span>Products</span>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5">
                <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd"></path>
              </svg>
            </button>
          </div>
          <div class="absolute left-0 z-20 py-1 mt-2 bg-white border border-gray-100 rounded-md shadow-xl dark:border-gray-700 lg:left-auto lg:right-0 dark:bg-gray-800" style="display: none;">
            <div class="overflow-y-auto w-36 max-h-96">
              <a href="/partners" class="block px-4 py-2 text-sm text-gray-700 capitalize transition-colors duration-300 transform dark:text-gray-300 hover:text-primary dark:hover:text-primary">
                Partners
              </a>
              <a href="/reviews" class="block px-4 py-2 text-sm text-gray-700 capitalize transition-colors duration-300 transform dark:text-gray-300 hover:text-primary dark:hover:text-primary">
                Reviews
              </a>
              <a href="/customers" class="block px-4 py-2 text-sm text-gray-700 capitalize transition-colors duration-300 transform dark:text-gray-300 hover:text-primary dark:hover:text-primary">
                Customers
              </a>
              <a href="/stories" class="block px-4 py-2 text-sm text-gray-700 capitalize transition-colors duration-300 transform dark:text-gray-300 hover:text-primary dark:hover:text-primary">
                Stories
              </a>
            </div>
          </div>
        </div>
        <a href="/components" class="text-gray-500 dark:text-gray-200 hover:text-gray-800 dark:hover:text-gray-400 transition-colors duration-300 lg:hidden">Products</a>
        <a href="/premium" class="text-gray-500 dark:text-gray-200 hover:text-gray-800 dark:hover:text-gray-400 transition-colors duration-300">Premium</a>
        <a href="/cheatsheet" target="_blank" class="text-gray-500 dark:text-gray-200 hover:text-gray-800 dark:hover:text-gray-400 transition-colors duration-300">Cheatsheet</a>
        <a target="_blank" href="https://services.creative-tim.com/?ref=tailwindcomponents" class="flex items-center space-x-2 text-gray-500 transition-colors duration-300 dark:text-gray-200 hover:text-gray-800 dark:hover:text-gray-400">Custom Development</a>
      </div>
      <div class="flex flex-col space-y-4 lg:space-y-0 lg:flex-row lg:items-center lg:space-x-4">
        <button type="button" aria-label="Color Mode"
          class="flex justify-center p-2 text-gray-500 transition duration-150 ease-in-out bg-gray-100 border border-transparent rounded-md lg:bg-white lg:dark:bg-gray-900 dark:text-gray-200 dark:bg-gray-800 hover:bg-gray-50 dark:hover:bg-gray-700 hover:text-gray-700 focus:outline-none focus:bg-gray-50 dark:focus:bg-gray-700 active:bg-gray-50">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5 transform -rotate-90">
            <path d="M17.293 13.293A8 8 0 016.707 2.707a8.001 8.001 0 1010.586 10.586z" />
          </svg>
        </button>
        <form action="/search" class="flex flex-wrap justify-between md:flex-row">
          <input type="search" name="query" placeholder="Search" required="required"
            class="w-full h-12 px-4 text-sm text-gray-700 bg-white border border-gray-200 rounded-lg lg:w-20 xl:transition-all xl:duration-300 xl:w-36 xl:focus:w-44 lg:h-10 dark:bg-gray-900 dark:text-gray-300 dark:border-gray-600 focus:border-primary dark:focus:border-primary focus:outline-none focus:ring focus:ring-primary dark:placeholder-gray-400 focus:ring-opacity-20">
        </form>
        <a href="/signup" class="flex items-center justify-center h-12 px-4 text-sm font-medium text-center text-white transition-colors duration-300 transform rounded-md lg:h-10 bg-primary hover:bg-primary/70">
          Create account
        </a>
        <a href="/login"
          class="flex items-center justify-center h-12 px-4 mt-2 text-sm text-center text-gray-600 transition-colors duration-300 transform border rounded-lg lg:h-10 dark:text-gray-300 dark:border-gray-300 hover:bg-gray-100 dark:hover:bg-gray-700 focus:outline-none">
          Login
        </a>
      </div>
    </div>
    <div class="hidden lg:flex lg:flex-row lg:items-center lg:justify-between lg:flex-1 lg:space-x-2">
      <div class="flex flex-col space-y-3 lg:space-y-0 lg:flex-row lg:space-x-6 xl:space-x-8 lg:items-center">
        <div class="relative inline-block hidden lg:block">
          <div>
            <button class="text-gray-100 dark:text-gray-200 hover:text-gray-800 dark:hover:text-gray-400 transition-colors duration-300 flex items-center space-x-1 focus:outline-none">
              <span>Products</span>
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5">
                <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
              </svg>
            </button>
          </div>
          <div class="absolute left-0 z-20 py-1 mt-2 bg-white border border-gray-100 rounded-md shadow-xl dark:border-gray-700 lg:left-auto lg:right-0 dark:bg-gray-800" style="display: none;">
            <div class="overflow-y-auto w-36 max-h-96">
              <a href="/partners" class="block px-4 py-2 text-sm text-gray-700 capitalize transition-colors duration-300 transform dark:text-gray-300 hover:text-primary dark:hover:text-primary">
                Partners
              </a>
              <a href="/reviews" class="block px-4 py-2 text-sm text-gray-700 capitalize transition-colors duration-300 transform dark:text-gray-300 hover:text-primary dark:hover:text-primary">
                Reviews
              </a>
              <a href="/customers" class="block px-4 py-2 text-sm text-gray-700 capitalize transition-colors duration-300 transform dark:text-gray-300 hover:text-primary dark:hover:text-primary">
                Customers
              </a>
              <a href="/stories" class="block px-4 py-2 text-sm text-gray-700 capitalize transition-colors duration-300 transform dark:text-gray-300 hover:text-primary dark:hover:text-primary">
                Stories
              </a>
            </div>
          </div>
        </div>
        <a href="/components" class="text-gray-500 dark:text-gray-200 hover:text-gray-800 dark:hover:text-gray-400 transition-colors duration-300 lg:hidden">Products</a>
        <a href="/premium" class="text-gray-500 dark:text-gray-200 hover:text-gray-800 dark:hover:text-gray-400 transition-colors duration-300">Premium</a>
        <a href="/cheatsheet" target="_blank" class="text-gray-500 dark:text-gray-200 hover:text-gray-800 dark:hover:text-gray-400 transition-colors duration-300">Cheatsheet</a>
        <a target="_blank" href="https://services.creative-tim.com/?ref=tailwindcomponents" class="flex items-center space-x-2 text-gray-500 transition-colors duration-300 dark:text-gray-200 hover:text-gray-800 dark:hover:text-gray-400">
          <span>Custom Development</span>
          <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-5 h-5">
            <path d="M16.979 8.45L16.986 12H19V5H12V7.014L15.55 7.021L5 17.571L6.429 19L16.979 8.45Z" fill="currentColor" />
          </svg>
        </a>
      </div>
      <div class="flex flex-col space-y-2 lg:space-y-0 lg:flex-row lg:items-center lg:space-x-3">
        <button type="button" aria-label="Color Mode"
          class="flex justify-center p-2 text-gray-500 transition duration-150 ease-in-out bg-gray-100 border border-transparent rounded-md lg:bg-white lg:dark:bg-gray-900 dark:text-gray-200 dark:bg-gray-800 hover:bg-gray-50 dark:hover:bg-gray-700 hover:text-gray-700 focus:outline-none focus:bg-gray-50 dark:focus:bg-gray-700 active:bg-gray-50">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5 transform -rotate-90">
            <path d="M17.293 13.293A8 8 0 016.707 2.707a8.001 8.001 0 1010.586 10.586z" />
          </svg>
        </button>
        <form action="/search" class="flex flex-wrap justify-between md:flex-row">
          <input type="search" name="query" placeholder="Search" required="required"
            class="w-full h-12 px-4 text-sm text-gray-700 bg-white border border-gray-200 rounded-lg lg:w-20 xl:transition-all xl:duration-300 xl:w-36 xl:focus:w-44 lg:h-10 dark:bg-gray-900 dark:text-gray-300 dark:border-gray-600 focus:border-primary dark:focus:border-primary focus:outline-none focus:ring focus:ring-primary dark:placeholder-gray-400 focus:ring-opacity-20">
        </form>
        <a href="/signup" class="flex items-center justify-center h-12 px-4 text-sm font-medium text-center text-white transition-colors duration-300 transform rounded-md lg:h-10 bg-primary hover:bg-primary/70">
          Create account
        </a>
        <a href="/login"
          class="flex items-center justify-center h-12 px-4 mt-2 text-sm text-center text-gray-100 bg-gray-700 border border-gray-500 rounded-lg lg:h-10 dark:text-gray-300 dark:border-gray-300 hover:bg-gray-600 dark:hover:bg-gray-700 focus:outline-none">
          Login
        </a>
      </div>
    </div>
  </div>
</header>
</template>

<script>
export default {}
</script>
