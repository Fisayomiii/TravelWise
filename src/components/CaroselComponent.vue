<template>
    <div class="bg-[#F9F9F9]">
        <div class="mx-auto max-w-2xl px-4 py-16 sm:px-6 sm:py-24 lg:max-w-7xl lg:px-1">

            <div class="max-w-screen-sm sm:text-center sm:mx-auto text-center">
                <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none gradient-underline">
                    Popular locations
                </h2><br><br>
                <p class="text-base text-gray-700 md:text-lg sm:px-4 mt-2">
                    There are many packages more than you needed just to make sure that you get enough options to avail
                    the best one
                </p>
            </div>
            <div class="flex overflow-x-auto">
                <div class="flex transition-transform duration-300 ease-in-out gap-6" ref="carousel">

                    <div class="max-w-sm max-h-fit bg-white shawdow-lg w-96 px-6 pt-6 pb-2 rounded-xl dark:bg-zinc-800">
                        <div class="relative overflow-hidden group rounded-xl">
                            <img class="object-cover rounded-xl h-64 w-full transition duration-500 ease-in-out transform group-hover:scale-105"
                                src="../assets/illustrations/illustrationcard1.png" alt="illustrationimg1" />
                            <div class="absolute inset-0 bg-black opacity-0 group-hover:opacity-10 transition-opacity">
                            </div>
                        </div>
                        <div class="mt-4 mb-5 flex justify-between">
                            <div>
                                <h3 class="text-sm text-gray-700">
                                    <h5 class="text-gray-900 font-bold text-2xl tracking-tight dark:text-white">
                                        Mountain Hiking Tour
                                    </h5>
                                </h3>
                            </div>
                            <p class="mr-4 text-md font-medium text-amber-400 flex gap-1">4.5 <img
                                    src="../assets/illustrations/Star.png" class="h-5" alt="star"></p>
                        </div>
                        <p class="font-normal text-gray-700 mb-3 dark:text-gray-400">Himalayas , Hawaii
                        </p>
                        <div class="mt-4 mb-5 flex justify-between">
                            <div>
                                <h3 class="text-sm text-gray-700">
                                    <h5 class="text-gray-400 font-bold text-1xl tracking-tight dark:text-white">
                                        <span class="text-[#EF1B48] text-2xl">$1,000</span>/person
                                    </h5>
                                </h3>
                            </div>
                            <button
                                class="inline-block py-3 px-6 bg-[#EF1B48] hover:bg-rose-500 active:bg-rose-300 focus:outline-none focus:ring focus:ring-rose-300 text-sm text-white font-bold rounded-full transition duration-200 transition ease-in-out delay-150 hover:scale-110 duration-300">Book
                                now
                            </button>
                        </div>
                    </div>

                    <div class="max-w-sm max-h-fit bg-white shawdow-lg w-96 px-6 pt-6 pb-2 rounded-xl dark:bg-zinc-800">
                        <div class="relative overflow-hidden group rounded-xl">
                            <img class="object-cover rounded-xl h-64 w-full transition duration-500 ease-in-out transform group-hover:scale-105"
                                src="../assets/illustrations/illustrationcard2.png" alt="illustrationimg2" />
                            <div class="absolute inset-0 bg-black opacity-0 group-hover:opacity-10 transition-opacity">
                            </div>
                        </div>
                        <div class="mt-4 mb-5 flex justify-between">
                            <div>
                                <h3 class="text-sm text-gray-700">
                                    <h5 class="text-gray-900 font-bold text-2xl tracking-tight dark:text-white">
                                        Mountain Hiking Tour
                                    </h5>
                                </h3>
                            </div>
                            <p class="mr-4 text-md font-medium text-amber-400 flex gap-1">4.5 <img
                                    src="../assets/illustrations/Star.png" class="h-5" alt="star"></p>
                        </div>
                        <p class="font-normal text-gray-700 mb-3 dark:text-gray-400">Himalayas , Hawaii
                        </p>
                        <div class="mt-4 mb-5 flex justify-between">
                            <div>
                                <h3 class="text-sm text-gray-700">
                                    <h5 class="text-gray-400 font-bold text-1xl tracking-tight dark:text-white">
                                        <span class="text-[#EF1B48] text-2xl">$1,000</span>/person
                                    </h5>
                                </h3>
                            </div>
                            <button
                                class="py-3 px-6 bg-[#EF1B48] hover:bg-rose-500 active:bg-rose-300 focus:outline-none focus:ring focus:ring-rose-300 text-sm text-white font-bold rounded-full transition duration-200 transition ease-in-out delay-150 hover:scale-110 duration-300">Book
                                now
                            </button>
                        </div>
                    </div>

                    <div class="max-w-sm max-h-fit bg-white shawdow-lg w-96 px-6 pt-6 pb-2 rounded-xl dark:bg-zinc-800">
                        <div class="relative overflow-hidden group rounded-xl">
                            <img class="object-cover rounded-xl h-64 w-full transition duration-500 ease-in-out transform group-hover:scale-105"
                                src="../assets/illustrations/illustrationcard3.png" alt="illustrationimg3" />
                            <div class="absolute inset-0 bg-black opacity-0 group-hover:opacity-10 transition-opacity">
                            </div>
                        </div>
                        <div class="mt-4 mb-5 flex justify-between">
                            <div>
                                <h3 class="text-sm text-gray-700">
                                    <h5 class="text-gray-900 font-bold text-2xl tracking-tight dark:text-white">
                                        Mountain Hiking Tour
                                    </h5>
                                </h3>
                            </div>
                            <p class="mr-4 text-md font-medium text-amber-400 flex gap-1">4.5 <img
                                    src="../assets/illustrations/Star.png" class="h-5" alt="star"></p>
                        </div>
                        <p class="font-normal text-gray-700 mb-3 dark:text-gray-400">Himalayas , Hawaii
                        </p>
                        <div class="mt-4 mb-5 flex justify-between">
                            <div>
                                <h3 class="text-sm text-gray-700">
                                    <h5 class="text-gray-400 font-bold text-1xl tracking-tight dark:text-white">
                                        <span class="text-[#EF1B48] text-2xl">$1,000</span>/person
                                    </h5>
                                </h3>
                            </div>
                            <button
                                class=" py-3 px-6 bg-[#EF1B48] hover:bg-rose-500 active:bg-rose-300 focus:outline-none focus:ring focus:ring-rose-300 text-sm text-white font-bold rounded-full transition duration-200 transition ease-in-out delay-150 hover:scale-110 duration-300">Book
                                now
                            </button>
                        </div>
                    </div>

                    <div class="max-w-sm max-h-fit bg-white shawdow-lg w-96 px-6 pt-6 pb-2 rounded-xl dark:bg-zinc-800">
                        <div class="relative overflow-hidden group rounded-xl">
                            <img class="object-cover rounded-xl h-64 w-full transition duration-500 ease-in-out transform group-hover:scale-105"
                                src="../assets/illustrations/illustrationcard4.png" alt="illustrationimg4" />
                            <div class="absolute inset-0 bg-black opacity-0 group-hover:opacity-10 transition-opacity">
                            </div>
                        </div>
                        <div class="mt-4 mb-5 flex justify-between">
                            <div>
                                <h3 class="text-sm text-gray-700">
                                    <h5 class="text-gray-900 font-bold text-2xl tracking-tight dark:text-white">
                                        Mountain Hiking Tour
                                    </h5>
                                </h3>
                            </div>
                            <p class="mr-4 text-md font-medium text-amber-400 flex gap-1">4.5 <img
                                    src="../assets/illustrations/Star.png" class="h-5" alt="star"></p>
                        </div>
                        <p class="font-normal text-gray-700 mb-3 dark:text-gray-400">Himalayas , Hawaii
                        </p>
                        <div class="mt-4 mb-5 flex justify-between">
                            <div>
                                <h3 class="text-sm text-gray-700">
                                    <h5 class="text-gray-400 font-bold text-1xl tracking-tight dark:text-white">
                                        <span class="text-[#EF1B48] text-2xl">$1,000</span>/person
                                    </h5>
                                </h3>
                            </div>
                            <button
                                class=" py-3 px-6 bg-[#EF1B48] hover:bg-rose-500 active:bg-rose-300 focus:outline-none focus:ring focus:ring-rose-300 text-sm text-white font-bold rounded-full transition duration-200 transition ease-in-out delay-150 hover:scale-110 duration-300">Book
                                now
                            </button>
                        </div>

                    </div>

                </div>

            </div>
                <div class="flex justify-center mt-6">
                    <!-- button  -->
                    <button @click="previous"
                        class="flex-shrink-0 w-11 h-11 active:bg-[#F43F5E] hover:bg-rose-500 active:bg-rose-300 outline-none ring ring-rose-300 font-bold rounded-full transition duration-200 transition ease-in-out delay-150 hover:scale-110 text-gray-900 text-xl font-bold rounded-full shadow-md mr-4">
                        &lt;
                    </button>
                    <button @click="next"
                        class="flex-shrink-0 w-11 h-11 hover:bg-rose-500 active:bg-rose-300 focus:outline-none ring ring-rose-300 font-bold rounded-full transition duration-200 transition ease-in-out delay-150 hover:scale-110 text-gray-900 text-xl font-bold rounded-full shadow-md">
                        &gt;
                    </button>
                </div>
        </div>
        <Newsletter />

    </div>
</template>


<script>
import Newsletter from "./NewsletterComponent.vue";

export default {
    components: { Newsletter },

    data() {
        return {
            currentIndex: 0,
            cardWidth: 0,
            carouselWidth: 0,
        };
    },
    mounted() {
        this.cardWidth = this.$refs.carousel.children[0].offsetWidth;
        this.carouselWidth = this.$refs.carousel.offsetWidth;
    },
    methods: {
        next() {
            if (this.currentIndex < 3) {
                this.currentIndex++;
                this.$refs.carousel.style.transform = `translateX(-${this.cardWidth * this.currentIndex
                    }px)`;
            }
        },
        previous() {
            if (this.currentIndex > 0) {
                this.currentIndex--;
                this.$refs.carousel.style.transform = `translateX(-${this.cardWidth * this.currentIndex
                    }px)`;
            }
        }
    }
};
</script>