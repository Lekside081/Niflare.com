<template>
    <div class="Navbar z-10">
        <div class="flex flex-row justify-between rounded-full bg-black mt-1.5 py-4 px-4">
            <div class="basis-1/2 flex text-white py-3 text-2xl space-x-1">
                <NuxtLink to="/">
                <p class="font-bold">Niflare</p>
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
                <p>Our Service</p>
                </NuxtLink>
            </div>

            <div class="basis-1/4 text-white py-3">
                <NuxtLink to="#learnwithus">
                    <div>Learn With Us</div>
                </NuxtLink>
            </div>

            <div class="basis-1/4 text-white py-3">
                <NuxtLink to="/Termsofservice">
                    <div>Terms of Service</div>
                </NuxtLink>
            </div>

            <div class="basis-1/4 text-white py-3">
                <NuxtLink to="/Privacypolicy">
                    <div>Privacy Policy</div>
                </NuxtLink>
            </div>

            <div class="basis-1/2 flex justify-end">
                <button class="bg-green-500 hover:bg-gray-50 font-bold py-3 px-5 rounded-full">
                    Download Course
                </button>
            </div>

        </div>


    </div>
</template>
<style>
.Navbar {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 0px 140px 0px 140px;
}
</style>

