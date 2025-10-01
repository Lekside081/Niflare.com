<template>
    <div id="niflare" class="Simplify rounded-b-3xl sm:px-5">
        <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-6  mx-auto w-[90%] py-10">
            <div class="basis-1/2 mt-28">
                <div class="text-5xl font-bold hidden md:block"><span class="text-yellow-200">Innovative </span>Solutions</div>
                <div class="text-4xl text-center font-bold block md:hidden"><span class="text-yellow-200">Innovative </span>Solutions</div>
                <div class="text-6xl mt-6 font-bold hidden md:block">{{ title }}</div>
                <div class="text-5xl mt-6 font-bold block md:hidden text-center">{{ title }}</div>
                <div class="text-6xl mt-6 font-bold hidden md:block">{{ name }}</div>
                <div class="text-5xl mt-6 font-bold block md:hidden text-center">{{ name }}</div>

                <div class="hidden md:block">
                <div class="text-2xl mt-14 text-gray-300">We transform your ideas into Reality by leveraging</div>
                <div class="text-2xl mt-1 text-gray-300">Cutting-edge technologies whether you're a business</div>
                <div class="text-2xl mt-1 text-gray-300">Owner seeking robust digital solutions or an Individual</div>
                <div class="text-2xl mt-1 text-gray-300">Eager to learn and grow, we're Here to deliver except-</div>
                <div class="text-2xl mt-1 text-gray-300">ional services and training</div>
                </div>

                <div class="block md:hidden text-center">
                <div class="text-2xl mt-14 text-gray-300">We transform your ideas into Reality</div>
                <div class="text-2xl mt-1 text-gray-300">by leveraging Cutting-edge</div>
                <div class="text-2xl mt-1 text-gray-300">technologies whether you're a</div>
                <div class="text-2xl mt-1 text-gray-300">business Owner seeking robust</div>
                <div class="text-2xl mt-1 text-gray-300">digital solutions or an Individual Eager to learn and grow, we're Here</div>
                <div class="text-2xl mt-1 text-gray-300">to deliver exceptional services and</div>
                <div class="text-2xl mt-1 text-gray-300">training</div>
                </div>

                <div class="flex justify-center md:justify-start py-10">
                    <button class="bg-green-500 hover:bg-gray-50 font-bold py-3 px-12 text-black text-2xl rounded-full">
                        Get Course
                    </button>
                </div>
            </div>

            <div class="basis-1/2 py-16">
                <img :src="img">
            </div>

        </div>

    </div>
</template>

<script setup>
defineProps(
   ['name', 'title', 'img']
)

</script>

<style>
.Simplify {
    font-family: Arial, sans-serif;
    color: #fff;
    background-color: rgb(0, 0, 0);
    margin: 0;
}
</style>