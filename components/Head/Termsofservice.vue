<template>
    <div class="mt-24 bg-gray-50">
        <div class="flex flex-col md:flex-row justify-between py-6 px-6 md:px-32 items-center">
            <div class="basis-full md:basis-1/2 flex items-center text-black py-3 text-2xl space-x-1">
                <NuxtLink to="/">
                    <p class="font-bold">Niflare</p>
                </NuxtLink>
                <NuxtLink to="/">
                    <div>
                        <svg class="mt-1 w-6 h-6 md:w-[30px] md:h-[30px] text-black" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
                            <path fill-rule="evenodd" d="M9.586 2.586A2 2 0 0 1 11 2h2a2 2 0 0 1 2 2v.089l.473.196.063-.063a2.002 2.002 0 0 1 2.828 0l1.414 1.414a2 2 0 0 1 0 2.827l-.063.064.196.473H20a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-.089l-.196.473.063.063a2.002 2.002 0 0 1 0 2.828l-1.414 1.414a2 2 0 0 1-2.828 0l-.063-.063-.473.196V20a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2v-.089l-.473-.196-.063.063a2.002 2.002 0 0 1-2.828 0l-1.414-1.414a2 2 0 0 1 0-2.827l.063-.064L4.089 15H4a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2h.09l.195-.473-.063-.063a2 2 0 0 1 0-2.828l1.414-1.414a2 2 0 0 1 2.827 0l.064.063L9 4.089V4a2 2 0 0 1 .586-1.414ZM8 12a4 4 0 1 1 8 0 4 4 0 0 1-8 0Z" clip-rule="evenodd" />
                        </svg>
                    </div>
                </NuxtLink>
            </div>

            <div class="flex flex-col md:flex-row items-center justify-between w-full md:w-[90%] space-y-4 md:space-y-0 md:space-x-8">
                <NuxtLink to="#ourservice" class="text-black py-3">
                    <p>Our Service</p>
                </NuxtLink>
                <NuxtLink to="#learnwithus" class="text-black py-3">
                    <div>Learn With Us</div>
                </NuxtLink>
                <NuxtLink to="/Termsofservice" class="text-black py-3">
                    <div>Terms of Service</div>
                </NuxtLink>
                <NuxtLink to="/Privacypolicy" class="text-black py-3">
                    <div>Privacy Policy</div>
                </NuxtLink>
            </div>

            <div class="basis-full md:basis-1/2 flex justify-end">
                <button class="bg-black text-white hover:bg-gray-50 font-bold py-4 px-5 rounded-2xl">
                    Download Course
                </button>
            </div>
        </div>
    </div>
</template>
