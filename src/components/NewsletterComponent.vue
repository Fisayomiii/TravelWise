<template>
    <div
        class="relative items-center w-full px-5 py-24 mx-auto md:px-12 lg:px-16 max-w-7xl bg-[#FEE1E7] bg-opacity-75 rounded-xl">
        <img src="../assets/illustrations/Intersect.png" class="absolute inset-0 object-cover w-full h-full" alt="" />
        <div class="relative flex-col items-start m-auto align-middle ">
            <div class="grid grid-cols-1 gap-6 lg:grid-cols-2 lg:gap-24">
                <div class="relative items-center gap-12 m-auto lg:inline-flex text-center lg:text-left">
                    <div class="max-w-xl lg:max-w-lg ">
                        <p class="text-2xl font-bold tracking-tight text-black sm:text-4xl">
                            Subscribe to our newsletter
                            to get exclusive updates from Us.
                        </p>
                        <p class="max-w-xl mt-4 text-base tracking-tight text-gray-600">
                            Receive latest news, update, and many other
                            things every week.
                        </p>
                        <center>
                            <div class="mt-6 flex flex-wrap max-w-md ">
                                <label for="email-address" class="sr-only">Email address</label>
                                <input id="email-address" name="email" type="email" autocomplete="email"
                                    class="min-w-0 flex-auto rounded-md border-0 bg-white px-3.5 py-2 text-white shadow-sm bg-[#EF1B48]  focus:outline-none focus:ring focus:ring-rose-300 text-sm text-white font-bold rounded-full transition duration-200 transition ease-in-out delay-150 duration-300 sm:text-sm sm:leading-6"
                                    placeholder="Enter your email" />
                                <button type="submit"
                                    class="flex-none rounded-md px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm bg-[#EF1B48] hover:bg-rose-500 active:bg-rose-300 focus:outline-none focus:ring focus:ring-rose-300 text-sm text-white font-bold rounded-full transition duration-200 transition ease-in-out delay-150 hover:scale-110 duration-300">Subscribe</button>
                            </div>
                        </center>
                    </div>
                </div>
                <div class="order-first block w-full  aspect-square lg:mt-0 lg:order-first">
                    <img class="object-cover object-center w-full" alt="hero"
                        src="../assets/illustrations/illustration.png">
                </div>

            </div>
        </div>
    </div><br><br><br>
</template>
  