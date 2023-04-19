<script type="module">
import { Power3, gsap } from 'gsap/all';
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

        };
    },
    mounted() {
        this.startAnimation();
    },
    methods: {
        startAnimation() {
            gsap.fromTo(
                this.$refs.img, // Target element
                { opacity: 0, y: 1280 }, // From properties
                { opacity: 1, y: 0, duration: 1, ease: Power3.easeOut, delay: 2 }
            );
            gsap.fromTo(
                this.$refs.myText, // Target element
                { opacity: 0, y: 60 }, // From properties
                { opacity: 1, y: 0, duration: 1, ease: Power3.easeOut, delay: 3 }
            );
            gsap.fromTo(
                this.$refs.contentP, // Target element
                { opacity: 0, y: 60 }, // From properties
                { opacity: 1, y: 0, duration: 1, ease: Power3.easeOut, delay: 3.3 }
            );
            gsap.fromTo(
                this.$refs.rounded, // Target element
                { opacity: 0, }, // From properties
                { opacity: 1, duration: 1, ease: Power3.easeOut, delay: 3.6 }
            );
            gsap.fromTo(
                this.$refs.testimonial, // Target element
                { opacity: 0, y: 60 }, // From properties
                { opacity: 1, y: 0, duration: 1, ease: Power3.easeOut, delay: 3.9 }
            );
            gsap.fromTo(
                this.$refs.testimonial1, // Target element
                { opacity: 0, y: 60 }, // From properties
                { opacity: 1, y: 0, duration: 1, ease: Power3.easeOut, delay: 4.2 }
            );
            gsap.fromTo(
                this.$refs.testimonial2, // Target element
                { opacity: 0, y: 60 }, // From properties
                { opacity: 1, y: 0, duration: 1, ease: Power3.easeOut, delay: 4.4 }
            );
        },
    },
}
</script>

<template>
    <div class="px-5 sm:px-16 lg:px-44">
        <Header />

        <div class="relative flex flex-col-reverse py-16 lg:pt-0 lg:flex-col lg:pb-0">
            <div ref="img"
                class="hidden lg:block inset-y-0 right-0 w-full max-w-xl px-4 mx-auto lg:pl-8 lg:pr-0 lg:mb-0 lg:mx-0 lg:w-1/2 lg:max-w-full lg:absolute xl:px-0">
                <img class="object-cover w-full h-56 rounded shadow-lg lg:rounded-none lg:shadow-none sm:h-96 lg:h-full"
                    src="https://images.unsplash.com/photo-1529018576489-4d1b669bdb15?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=774&q=80"
                    alt="img" />
            </div>
            <div class="relative flex flex-col items-start w-full max-w-xl px-4 mx-auto md:px-0 lg:px-8 lg:max-w-screen-xl">
                <div class="mb-16 lg:my-40 lg:max-w-lg lg:pr-5">
                    <h2 ref="myText"
                        class="max-w-lg mb-5 text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none">
                        The world is waiting for you
                        to explore it
                    </h2>

                    <p ref="contentP" class="pr-5 mb-5 text-base text-gray-700 md:text-lg">
                        There are many packages more than you needed just to make sure that you get enough options to avail
                        the best one
                    </p>

                    <div ref="rounded"
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
                            <div class="text-center" ref="testimonial">
                                <h6 class="text-2xl sm:text-3xl font-extrabold text-[#EF1B48]">12K+</h6>
                                <p class="font-bold">Successful Journeys</p>
                            </div>
                            <div class="text-center" ref="testimonial1">
                                <h6 class="text-2xl sm:text-3xl font-extrabold text-[#EF1B48]">16+</h6>
                                <p class="font-bold">Awards Winning</p>
                            </div>
                            <div class="text-center" ref="testimonial2">
                                <h6 class="text-2xl sm:text-3xl font-extrabold text-[#EF1B48]">20+</h6>
                                <p class="font-bold">Years Of Experience</p>
                            </div>
                        </div>
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