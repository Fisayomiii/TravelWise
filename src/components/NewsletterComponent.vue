<template>
    <div
        class="relative items-center w-full px-9 py-2 mx-auto md:px-12 lg:px-16 max-w-7xl bg-[#FEE1E7] bg-opacity-75 rounded-xl">
        <img src="../assets/illustrations/Intersect.png" class="absolute inset-0 object-cover w-full h-full" alt="" />
        <div class="relative flex-col items-start m-auto align-middle ">
            <div class="grid grid-cols-1 gap-6 lg:grid-cols-2 lg:gap-24">
                <div class="relative items-center gap-12 m-auto lg:inline-flex text-center lg:text-left">
                    <div class="max-w-xl lg:max-w-lg ">
                        <p class="text-2xl font-bold tracking-tight text-black sm:text-4xl" v-motion-slide-visible-once-bottom>
                            Subscribe to our Newsletter.
                        </p>
                        <p class="max-w-xl mt-4 text-base tracking-tight text-gray-600" v-motion-slide-visible-once-bottom>
                            Receive latest news, update, and many other
                            things every week.
                        </p>
                        <!-- <center> -->
                            <form @submit.prevent="onSubmitHandler"
                                class="mt-6 flex flex-wrap max-w-md " v-motion-slide-visible-once-bottom>
                                <input id="email" type="email" v-model="email" autocomplete="email"
                                    class="min-w-0 flex-auto rounded-md border-0 bg-white px-3.5 py-2 text-white shadow-sm bg-[#EF1B48]  focus:outline-none focus:ring focus:ring-rose-300 text-sm text-white font-bold rounded-full transition duration-200 transition ease-in-out delay-150 duration-300 sm:text-sm sm:leading-6"
                                    placeholder="Enter your email" />
                                <button type="submit"
                                    class="flex-none rounded-md px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm bg-[#EF1B48] hover:bg-rose-500 active:bg-rose-300 focus:outline-none focus:ring focus:ring-rose-300 text-sm text-white font-bold rounded-full transition duration-200 transition ease-in-out delay-150 duration-300">Subscribe</button>
                            </form>
                        <!-- </center> -->
                        <br>
                    </div>
                </div>
                <div class="order-first block w-full aspect-square lg:mt-0 lg:order-first" v-motion-pop-visible-once>
                    <img class="object-fit object-center" alt="hero" src="../assets/illustrations/illustration.png">
                </div>
            </div>
        </div>
    </div><br><br><br>
</template>


<script>
export default {
    data() {
        return {
            email: '',
        };
    },
    methods: {
        onSubmitHandler() {
            if (
                this.email.trim().length > 0 &&
                this.email.includes('@') &&
                this.email.includes('.') &&
                this.email.includes('com')
            ) {
                this.$swal.fire({
                    title: 'Successful!',
                    text: 'Your email has been added to our list.',
                    icon: 'success',
                });
                this.email = '';
            } else {
                this.$swal.fire({
                    title: 'OOPS!',
                    text: 'Please input a valid email address.',
                    icon: 'error',
                });
            }
        },
    },
};
</script>