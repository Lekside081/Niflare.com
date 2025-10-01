<template>
    <div class="Navbar z-10 px-6">
        <div class="flex items-center justify-between lg:px-10 rounded-full bg-black mt-1.5 py-4">
            <div class="basis-1/2 flex text-white py-3 text-2xl space-x-1">
                <NuxtLink to="/">
                <!-- <p class="font-bold">Niflare</p> -->
                </NuxtLink>
                <NuxtLink to="/">
                <div><svg class="mt-1 w-[30px] h-[30px]  text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                        width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
                        <path fill-rule="evenodd"
                            d="M9.586 2.586A2 2 0 0 1 11 2h2a2 2 0 0 1 2 2v.089l.473.196.063-.063a2.002 2.002 0 0 1 2.828 0l1.414 1.414a2 2 0 0 1 0 2.827l-.063.064.196.473H20a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-.089l-.196.473.063.063a2.002 2.002 0 0 1 0 2.828l-1.414 1.414a2 2 0 0 1-2.828 0l-.063-.063-.473.196V20a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2v-.089l-.473-.196-.063.063a2.002 2.002 0 0 1-2.828 0l-1.414-1.414a2 2 0 0 1 0-2.827l.063-.064L4.089 15H4a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2h.09l.195-.473-.063-.063a2 2 0 0 1 0-2.828l1.414-1.414a2 2 0 0 1 2.827 0l.064.063L9 4.089V4a2 2 0 0 1 .586-1.414ZM8 12a4 4 0 1 1 8 0 4 4 0 0 1-8 0Z"
                            clip-rule="evenodd" />
                    </svg>
                </div>
                </NuxtLink>
            </div>

            <div class="basis-1/4 text-white py-3">
                <NuxtLink to="#ourservice">
                <p>Service</p>
                </NuxtLink>
            </div>

            <div class="basis-1/4 text-white py-3">
                <NuxtLink to="#learnwithus">
                    <div>Learn</div>
                </NuxtLink>
            </div>

            <div class="hidden sm:flex basis-1/4 text-white py-3">
                <NuxtLink to="/Termsofservice">
                    <div>Terms of Service</div>
                </NuxtLink>
            </div>

            <div class="hidden sm:flex basis-1/4 text-white py-3">
                <NuxtLink to="/Privacypolicy">
                    <div>Privacy Policy</div>
                </NuxtLink>
            </div>

            <div class="hidden md:flex basis-1/2 justify-end">
                <button class="bg-green-500 hover:bg-gray-50 font-bold py-3 px-5 rounded-full">
                    Download Course
                </button>
            </div>
             <!-- Mobile Menu Icon -->
      <div class="lg:hidden">
        <button @click="toggleMenu">
          <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
          </svg>
        </button>
      </div>

            <!-- Mobile Menu Dropdown -->
      <div v-if="isMenuOpen"
        class="absolute top-full right-0 w-[27%] bg-white border-4 shadow-md md:hidden flex flex-col gap-2 px-2 py-1">
        <a href="/Termsofservice" class="text-gray-700 hover:text-blue-600">Terms of Service</a>
        <a href="/Privacypolicy" class="hover:text-blue-600">Privacy Policy</a>
      </div>

        </div>


    </div>
</template>
<script setup>
import { ref } from 'vue'
const isMenuOpen = ref(false)
const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value
}
</script>

<style>
.Navbar {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
}
</style>