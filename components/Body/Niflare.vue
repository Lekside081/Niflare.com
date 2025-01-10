<template>
    <div id="niflare" class="Simplify rounded-b-3xl sm:px-5">
        <div class="flex flex-row mx-auto w-[90%]">
            <div class="basis-1/2 mt-52">
                <div class="text-5xl font-bold"><span class="text-yellow-200">Innovative </span>Solutions</div>
                <div class="text-6xl mt-6 font-bold">{{ title }}</div>
                <div class="text-6xl mt-6 font-bold">{{ name }}</div>

                <div class="text-2xl mt-14 text-gray-300">We transform your ideas into Reality by leveraging</div>
                <div class="text-2xl mt-1 text-gray-300">Cutting-edge technologies whether you're a business</div>
                <div class="text-2xl mt-1 text-gray-300">Owner seeking robust digital solutions or an Individual</div>
                <div class="text-2xl mt-1 text-gray-300">Eager to learn and grow, we're Here to deliver except-</div>
                <div class="text-2xl mt-1 text-gray-300">ional services and training</div>

                <div class="py-10">
                    <button class="bg-green-500 hover:bg-gray-50 font-bold py-3 px-12 text-black text-2xl rounded-full">
                        Get Course
                    </button>
                </div>
            </div>

            <div class="basis-1/2 mt-52">
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