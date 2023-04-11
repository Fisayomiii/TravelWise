<template>
    <!-- <body class="px-5 sm:px-44"> -->
    <div class="px-5 sm:px-44">
        <Header />

        <div
            class="mt-5 sm:mt-20 px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
            <div class="flex flex-col items-center justify-between lg:flex-row">
                <div class="mb-10 lg:max-w-lg lg:pr-5 lg:mb-0">
                    <div class="max-w-xl mb-6 ">
                        <h2
                            class="max-w-lg mb-6 text-3xl font-extrabold tracking-tight text-gray-900 sm:text-4xl sm:leading-none">
                            The world is waiting for you to explore it

                        </h2>
                        <p class="text-base text-gray-700 md:text-lg">
                            There are many packages more than you needed just to make sure that you get enough options
                            to
                            avail the best one
                        </p>
                    </div>
                    <div
                        class="p-2.5 flex gap-2 items-center justify-center lg:justify-center border-0 ring-1 ring-inset ring-gray-300 rounded-full">
                        <div class="flex text-left">
                            <div
                                class="mr-3 flex items-center justify-center w-7 h-7 text-black transition duration-300 transform rounded-full">
                                <img src="../assets/illustrations/Location.png" alt="Location">
                            </div>
                            <div class="flex flex-col">
                                <div class="text-sm font-semibold">
                                    Where to?
                                </div>
                                <div class="text-xs text-gray-700">Search any location</div>
                            </div>
                        </div>
                        <div class="text-gray-300">l</div>

                        <div class="flex text-left">
                            <div
                                class="mr-3 flex items-center justify-center w-5 h-5 text-black transition duration-300 transform rounded-full">
                                <img src="../assets/illustrations/Calendar.png" alt="calender" />
                            </div>
                            <div class="flex flex-col">

                                <div class="text-sm font-semibold">
                                    Date
                                </div>
                                <div class="text-xs text-gray-700">Select a date</div>
                            </div>
                        </div>
                        <div
                            class="ml-10 flex items-center justify-center w-10 h-10 text-black transition duration-300 transform rounded-full bg-[#F43F5E]">
                            <img src="../assets/illustrations/Search.png" class="w-5 h-5" alt="Search" />
                        </div>
                    </div>

                    <div class="px-2 mt-9">
                        <div class="flex items-center gap-4">
                            <div class="text-center">
                                <h6 class="text-2xl sm:text-3xl font-extrabold text-[#EF1B48]">12K+</h6>
                                <p class="font-bold">Successful Journeys</p>
                            </div>
                            <div class="text-center">
                                <h6 class="text-2xl sm:text-3xl font-extrabold text-[#EF1B48]">16+</h6>
                                <p class="font-bold">Awards Winning</p>
                            </div>
                            <div class="text-center">
                                <h6 class="text-2xl sm:text-3xl font-extrabold text-[#EF1B48]">20+</h6>
                                <p class="font-bold">Years Of Experience</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="relative lg:w-1/2">
                    <div class="hidden lg:flex gap-2 ">
                        <img class="object-fit h-56 mt-52" src="../assets/illustrations/hero1.png" alt="hero1 img" />
                        <img class="object-fit h-96" src="../assets/illustrations/hero2.png" alt="hero2 img" />
                        <img class="object-fit h-56" style="margin-top: -5em;" src="../assets/illustrations/hero3.png"
                            alt="hero3 img" />
                    </div>
                </div>
            </div>
        </div>
    </div>

    <LogoClouds />
    <CtaOne />
    <CtaTwo />
    <Carosel />
    <Footer />
</template>

<script>
import Header from "./HeaderComponent.vue";
import LogoClouds from "./LogoCloudsComponent.vue";
import CtaOne from "./CtaOneComponent.vue";
import CtaTwo from "./CtaTwoComponent.vue";
import Carosel from "./CaroselComponent.vue";
import Footer from "./FooterComponent.vue";

export default {
    components: { Header, LogoClouds, CtaOne, CtaTwo, Carosel, Footer },
    data() {
        return {
        }
    },
    methods: {
    }
}
</script>