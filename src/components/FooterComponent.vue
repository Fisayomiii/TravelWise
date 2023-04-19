<template>
    <footer class="bg-white" aria-labelledby="footer-heading">
        <h2 id="footer-heading" class="sr-only">Footer</h2>
        <div class="px-4 py-12 mx-auto max-w-7xl sm:px-6 lg:px-16">
            <div class="xl:grid xl:grid-cols-3 xl:gap-8">
                <div class="text-white xl:col-span-1 lg:ml-auto">
                    <button v-motion-pop-visible-once>
                        <a class="inline-block py-4 px-9 bg-[#EF1B48] hover:bg-rose-500 active:bg-rose-300 focus:outline-none focus:ring focus:ring-rose-300 text-sm text-white font-bold rounded-full transition duration-200 transition ease-in-out delay-150 hover:scale-110 duration-300"
                            href="/">Get Started
                        </a>
                    </button>
                </div>
                <div class="grid grid-cols-2 gap-8 mt-12 xl:mt-0 xl:col-span-2 lg:order-first">
                    <div class="md:grid md:grid-cols-2 md:gap-8">
                        <div>
                            <h3 class="font-semibold leading-6 text-black uppercase" v-motion-slide-visible-once-bottom>
                                Company
                            </h3>
                            <ul role="list" class="mt-4 space-y-2">
                                <li v-for="item in items" :key="item.id">
                                    <a href="#" class="text-sm text-gray-500 hover:text-blue-600" v-motion-slide-visible-once-bottom>
                                        {{ item.name }}
                                    </a>
                                </li>
                            </ul>
                        </div>
                        <div class="mt-12 md:mt-0">
                            <h3 class="font-semibold leading-6 text-black uppercase" v-motion-slide-visible-once-bottom>
                                Help
                            </h3>
                            <ul role="list" class="mt-4 space-y-2">
                                <li v-for="item in items" :key="item.id">
                                    <a href="#" class="text-sm text-gray-500 hover:text-blue-600" v-motion-slide-visible-once-bottom>
                                        {{ item.name }}
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="md:grid md:grid-cols-2 md:gap-8">
                        <div>
                            <h3 class="font-semibold leading-6 text-black uppercase" v-motion-slide-visible-once-bottom>
                                Security
                            </h3>
                            <ul role="list" class="mt-4 space-y-2">
                                <li v-for="item in items" :key="item.id">
                                    <a href="#" class="text-sm text-gray-500 hover:text-blue-600" v-motion-slide-visible-once-bottom>
                                        {{ item.name }}
                                    </a>
                                </li>
                            </ul>
                        </div>
                        <div class="mt-12 md:mt-0">
                            <h3 class="font-semibold leading-6 text-black uppercase" v-motion-slide-visible-once-bottom>
                                Socials
                            </h3>
                            <ul role="list" class="mt-4 space-y-2">
                                <li v-for="item in items" :key="item.id">
                                    <a href="#" class="text-sm text-gray-500 hover:text-blue-600" v-motion-slide-visible-once-bottom>
                                        {{ item.name }}
                                    </a>
                                </li>
                            </ul>
                        </div>

                    </div>
                </div>
            </div>
        </div>


        <div class="px-4 py-12 mx-auto max-w-7xl sm:px-6 lg:px-16">
            <div
                class="flex flex-col items-center pt-8 pb-12 border-t border-gray-200 md:flex-row-reverse md:justify-between md:pt-6">
                <p class="mt-6 text-sm text-gray-500 md:mt-0" v-motion-slide-visible-once-bottom>
                    © Fisayomiii
                    <!-- -->. All rights reserved.
                </p><br/>
                <div class="max-w-xl">
                    <a class="text-3xl font-bold leading-none" href="/" v-motion-slide-visible-once-bottom>
                        <img src="../assets/illustrations/Logo.png" class="h-8" alt="">
                    </a>
                </div>
            </div>
        </div>
    </footer>
</template>


<script>
export default {
  data() {
    return {
      items: [
        { id: 1, name: 'Footer Menu' },
        { id: 2, name: 'Footer Menu' },
        { id: 3, name: 'Footer Menu' },
        { id: 4, name: 'Footer Menu' },
        { id: 5, name: 'Footer Menu' },
        { id: 6, name: 'Footer Menu' },
      ],
    };
  },
};
</script>