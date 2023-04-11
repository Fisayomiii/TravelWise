<template>
	<nav class="relative py-6 flex justify-between items-center bg-white">
		<a class="text-3xl font-bold leading-none" href="/">
			<img src="../assets/illustrations/Logo.png" class="h-8" alt="">
		</a>
		<div class="lg:hidden">
			<button class="navbar-burger flex items-center text-[#EF1B48] p-3" @click="showMenu = !showMenu">
				<svg class="block h-4 w-4 fill-current" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
					<title>Mobile menu</title>
					<path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
				</svg>
			</button>
		</div>
		<ul
			class="hidden absolute top-1/2 left-1/2 transform -translate-y-1/2 -translate-x-1/2 lg:flex lg:mx-auto lg:flex lg:items-center lg:w-auto lg:space-x-12">
			<li>
				<a class="text-sm text-gray-900 font-bold hover:text-gray-500 transition-all" href="/">Home</a>
			</li>
			<li>
				<a class="text-sm text-gray-900 flex font-bold hover:text-gray-500 transition-all" href="/">Listing</a>
			</li>
			<li>
				<a class="text-sm flex text-gray-900 font-bold hover:text-gray-500 transition-all" href="/">Pages</a>
			</li>
			<li>
				<a class="text-sm text-gray-900 font-bold hover:text-gray-500 transition-all" href="/">Contact Us</a>
			</li>
		</ul>
		<a class="hidden lg:inline-block lg:ml-auto lg:mr-3 py-4 px-9 text-sm text-gray-900 font-bold rounded-full border-0 ring-2 ring-inset ring-[#EF1B41] active:bg-rose-300 focus:outline-none focus:ring focus:ring-rose-300 transition duration-200 transition ease-in-out delay-150 hover:scale-110 duration-300"
			href="/">Log In
		</a>
		<a class="hidden lg:inline-block py-4 px-9 bg-[#EF1B48] hover:bg-rose-500 active:bg-rose-300 focus:outline-none focus:ring focus:ring-rose-300 text-sm text-white font-bold rounded-full transition duration-200 transition ease-in-out delay-150 hover:scale-110 duration-300"
			href="/">Sign up
		</a>
	</nav>

	<div class="relative z-50" :class="showMenu ? 'flex' : 'hidden'">
		<div class="inset-0 fixed bg-gray-800 opacity-25"></div>
		<nav class="fixed top-0 right-0 bottom-0 flex flex-col w-5/6 max-w-sm py-6 px-5 bg-white border-r overflow-y-auto">
			<div class="flex items-center mb-8">
				<button @click="showMenu = !showMenu">
					<svg class="h-6 w-6 text-[#EF1B48] cursor-pointer hover:text-[#EF1B45]"
						xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
						<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12">
						</path>
					</svg>
				</button>

				<a class="text-3xl ml-3 font-bold leading-none" href="/">
					<img src="../assets/illustrations/Logo.png" class="h-8" alt="">
				</a>
			</div>

			<div>
				<ul>
					<li class="mb-1">
						<a class="block p-4 text-sm font-semibold text-gray-900 hover:bg-rose-50 hover:text-rose-600 rounded"
							href="/">Home</a>
					</li>
					<li class="mb-1">
						<a class="block p-4 text-sm font-semibold text-gray-900 hover:bg-rose-50 hover:text-rose-600 rounded"
							href="/">Listing</a>
					</li>
					<li class="mb-1">
						<a class="block p-4 text-sm font-semibold text-gray-900 hover:bg-rose-50 hover:text-rose-600 rounded"
							href="/">Pages</a>
					</li>
					<li class="mb-1">
						<a class="block p-4 text-sm font-semibold text-gray-900 hover:bg-rose-50 hover:text-rose-600 rounded"
							href="/">Contact Us</a>
					</li>
				</ul>
			</div>
			<div class="mt-auto">
				<div class="pt-6">
					<a class="block px-4 py-4 mb-3 leading-loose text-xs text-center font-semibold leading-none border-0 ring-2 ring-inset ring-[#EF1B41] active:bg-rose-300 focus:outline-none focus:ring focus:ring-rose-300 transition duration-200 transition ease-in-out delay-150 hover:scale-105 duration-300 rounded-full"
						href="/">Log in</a>
					<a class="block px-4 py-3 mb-2 leading-loose text-xs text-center font-semibold bg-[#EF1B48] hover:bg-rose-500 active:bg-rose-300 focus:outline-none focus:ring focus:ring-rose-300 text-sm font-bold rounded-full transition duration-200 transition ease-in-out delay-150 hover:scale-105 duration-300"
						href="/">Sign Up</a>
				</div>
				<p class="my-4 text-xs text-center text-gray-400">
					<span>Copyright © <a href="https://github.com/Fisayomiii" target="_blank"
							rel="noopener noreferrer">Fisayomiii</a></span>
				</p>
			</div>
		</nav>
	</div>
</template>


<script>
export default {
	data() {
		return {
			showMenu: false,
		};
	},
};
</script>