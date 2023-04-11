<template>
    <div class="bg-[#F9F9F9]">
        <div class="mx-auto max-w-2xl px-4 py-16 sm:px-6 sm:py-24 lg:max-w-7xl lg:px-8">
            <div class="max-w-screen-sm sm:text-center sm:mx-auto text-center lg:text-left">
                <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none gradient-underline">
                    Popular locations
                </h2><br><br>
                <p class="text-base text-gray-700 md:text-lg sm:px-4">
                    There are many packages more than you needed just to make sure <br> that you get enough options to avail
                    the best one
                </p>
            </div>
            <!-- <div class="flex mt-4">
                <button @click="prevCard"
                    class="flex-shrink-0 w-12 h-12 bg-gray-300 text-gray-700 text-xl font-bold rounded-full shadow-md mr-4">
                    &lt;
                </button>
                <button @click="nextCard"
                    class="flex-shrink-0 w-12 h-12 bg-gray-300 text-gray-700 text-xl font-bold rounded-full shadow-md">
                    &gt;
                </button>
            </div> -->
            <!-- <div class="flex overflow-x-auto">
                <div class="flex transition-transform duration-300 ease-in-out"
                    :style="`transform: translateX(${translateX}px)`">
                    <div class="flex-shrink-0 w-96 bg-gray-100 p-1 m-2">
                        <a href="#" class="group">
                            <div
                                class="aspect-h-1 aspect-w-1 w-full overflow-hidden rounded-lg bg-gray-200 xl:aspect-h-8 xl:aspect-w-7">
                                <img src="https://tailwindui.com/img/ecommerce-images/category-page-04-image-card-04.jpg"
                                    alt="Hand holding black machined steel mechanical pencil with brass tip and top."
                                    class="h-full w-full object-cover object-center group-hover:opacity-75">
                            </div>
                            <h3 class="mt-4 text-sm text-gray-700">Machined Mechanical Pencil</h3>
                            <p class="mt-1 text-lg font-medium text-gray-900">$35</p>
                        </a>
                    </div>
                    <div class="flex-shrink-0 w-96 bg-gray-100 p-1 m-2">
                        <a href="#" class="group">
                            <div
                                class="aspect-h-1 aspect-w-1 w-full overflow-hidden rounded-lg bg-gray-200 xl:aspect-h-8 xl:aspect-w-7">
                                <img src="https://tailwindui.com/img/ecommerce-images/category-page-04-image-card-04.jpg"
                                    alt="Hand holding black machined steel mechanical pencil with brass tip and top."
                                    class="h-full w-full object-cover object-center group-hover:opacity-75">
                            </div>
                            <h3 class="mt-4 text-sm text-gray-700">Machined Mechanical Pencil</h3>
                            <p class="mt-1 text-lg font-medium text-gray-900">$35</p>
                        </a>
                    </div>
                    <div class="flex-shrink-0 w-96 bg-gray-100 p-1 m-2">
                        <a href="#" class="group">
                            <div
                                class="aspect-h-1 aspect-w-1 w-full overflow-hidden rounded-lg bg-gray-200 xl:aspect-h-8 xl:aspect-w-7">
                                <img src="https://tailwindui.com/img/ecommerce-images/category-page-04-image-card-04.jpg"
                                    alt="Hand holding black machined steel mechanical pencil with brass tip and top."
                                    class="h-full w-full object-cover object-center group-hover:opacity-75">
                            </div>
                            <h3 class="mt-4 text-sm text-gray-700">Machined Mechanical Pencil</h3>
                            <p class="mt-1 text-lg font-medium text-gray-900">$35</p>
                        </a>
                    </div>
                    <div class="flex-shrink-0 w-96 bg-gray-100 p-1 m-2">
                        <a href="#" class="group">
                            <div
                                class="aspect-h-1 aspect-w-1 w-full overflow-hidden rounded-lg bg-gray-200 xl:aspect-h-8 xl:aspect-w-7">
                                <img src="https://tailwindui.com/img/ecommerce-images/category-page-04-image-card-04.jpg"
                                    alt="Hand holding black machined steel mechanical pencil with brass tip and top."
                                    class="h-full w-full object-cover object-center group-hover:opacity-75">
                            </div>
                            <h3 class="mt-4 text-sm text-gray-700">Machined Mechanical Pencil</h3>
                            <p class="mt-1 text-lg font-medium text-gray-900">$35</p>
                        </a>
                    </div>
                </div>
            </div> -->

        </div>
        <Newsletter />

    </div>
</template>
<!-- <div class="mt-4 flex justify-between">
    <div>
        <h3 class="text-sm text-gray-700">
            <a :href="product.href">
                <span aria-hidden="true" class="absolute inset-0" />
                {{ product.name }}
            </a>
        </h3>
        <p class="mt-1 text-sm text-gray-500">{{ product.color }}</p>
    </div>
    <p class="text-sm font-medium text-gray-900">{{ product.price }}</p>
</div> -->
  
<script>
export default {
    components: { Newsletter },

    data() {
        return {
            translateX: 90, // Initial translateX value
            cardWidth: 64, // Width of each card
            numCards: 50, // Number of cards in the carousel
            numVisibleCards: 30, // Number of visible cards at a time
        };
    },
    methods: {
        nextCard() {
            // Move carousel to the right
            if (this.translateX > -(this.cardWidth * (this.numCards - this.numVisibleCards))) {
                this.translateX -= this.cardWidth;
            }
        },
        prevCard() {
            // Move carousel to the left
            if (this.translateX < 0) {
                this.translateX += this.cardWidth;
            }
        },
    },
};

import Newsletter from "./NewsletterComponent.vue";

</script>