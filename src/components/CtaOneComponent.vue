<template>
    <section class="relative flex items-center w-full bg-[#F9F9F9] sm:mb-52">
        <div class="relative items-center w-full px-5 py-24 mx-auto md:px-12 lg:px-16 max-w-7xl">
            <div class="relative flex-col items-start m-auto align-middle">
                <div class="grid grid-cols-1 gap-6 lg:grid-cols-2 lg:gap-24">
                    <div class="relative items-center gap-12 m-auto lg:inline-flex">
                        <div class="max-w-xl text-center lg:text-left">
                            <div>
                                <p class="text-2xl font-bold tracking-tight text-black sm:text-4xl" v-motion-slide-visible-once-bottom>
                                    Travel and experience seamless experience with us
                                </p>
                                <p class="max-w-xl mt-4 text-base tracking-tight text-gray-600" v-motion-slide-visible-once-bottom>
                                    Travel with your friends and family with one single tap and plan your trips together
                                    whilst in your
                                    comfort zone
                                </p>
                            </div>
                            <div class="flex justify-center gap-3 mt-10 lg:justify-start" v-motion-slide-visible-once-bottom>
                                <button>
                                    <a class="hidden lg:inline-block py-4 px-9 bg-[#EF1B48] hover:bg-rose-500 active:bg-rose-300 focus:outline-none focus:ring focus:ring-rose-300 text-sm text-white font-bold rounded-full transition duration-200 transition ease-in-out delay-150 hover:scale-110 duration-300"
                                        href="/">Start booking
                                    </a>
                                </button>
                            </div>
                        </div>
                    </div>
                    <div class="order-first block w-full mt-12 aspect-square lg:mt-0 lg:order-first" v-motion-pop-visible-once>
                        <img class="object-cover object-center w-full mx-auto lg:ml-auto" alt="hero"
                            src="../assets/illustrations/man.png">
                    </div>
                </div>
            </div>
        </div>
    </section><br>
</template>