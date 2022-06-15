<template>
	<div class="bg-gray-900">
		<div class="min-h-screen h-screen relative">
			<header class="text-gray-400 bg-gray-900 body-font border-b border-gray-400 z-20 w-full top-0 fixed">
				<div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
					<a class="flex title-font font-medium items-center text-white mb-4 md:mb-0">
						<svg xmlns="http://www.w3.org/2000/svg"
						     class="w-10 h-10 text-white p-2 bg-pink-500 rounded-full"
						     viewBox="0 0 20 20" fill="currentColor">
							<path fill-rule="evenodd"
							      d="M12.395 2.553a1 1 0 00-1.45-.385c-.345.23-.614.558-.822.88-.214.33-.403.713-.57 1.116-.334.804-.614 1.768-.84 2.734a31.365 31.365 0 00-.613 3.58 2.64 2.64 0 01-.945-1.067c-.328-.68-.398-1.534-.398-2.654A1 1 0 005.05 6.05 6.981 6.981 0 003 11a7 7 0 1011.95-4.95c-.592-.591-.98-.985-1.348-1.467-.363-.476-.724-1.063-1.207-2.03zM12.12 15.12A3 3 0 017 13s.879.5 2.5.5c0-1 .5-4 1.25-4.5.5 1 .786 1.293 1.371 1.879A2.99 2.99 0 0113 13a2.99 2.99 0 01-.879 2.121z"
							      clip-rule="evenodd" />
						</svg>
						<span class="ml-3 text-xl">Nowodev</span>
					</a>
					<nav class="md:ml-auto flex flex-wrap items-center text-base justify-center">
						<a class="mr-5 hover:text-white">First Link</a>
						<a class="mr-5 hover:text-white">Second Link</a>
						<a class="mr-5 hover:text-white">Third Link</a>
						<a class="mr-5 hover:text-white">Fourth Link</a>
						<a href="https://github.com/nowodev" class="mr-5" target="_blank">
							<svg class="w-7 h-7 md:fill-white" viewBox="0 0 496 512" xmlns="http://www.w3.org/2000/svg">
								<!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
								<path d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z" />
							</svg>
						</a>
						<a href="https://twitter.com/nowodev" target="_blank">
							<svg class="w-7 h-7 fill-blue-500" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
								<!--! Font Awesome Pro 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
								<path d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z" />
							</svg>
						</a>
					</nav>
				</div>
			</header>

			<section class="h-full">
				<div class="w-full lg:w-1/3 lg:fixed outline outline-sky-500 grid place-items-center bg-gray-700 lg:z-10 h-1/2 lg:h-full">
					<img alt="Favour" class="w-72 md:w-4/5" src="./assets/images/casual.png" />
				</div>
			</section>
		</div>

		<!-- hero section -->
		<!--		<section id="home" class="flex relative pt-16 min-h-screen">-->
		<!--			<div class="container flex flex-col items-center mx-auto md:flex-row-reverse">-->
		<!--				<div class="px-9 md:w-2/5 md:px-0">-->
		<!--					<img alt="Favour" class="w-72 md:w-full" src="./assets/images/casual.png" />-->
		<!--				</div>-->

		<!--				<div class="px-9 mt-9 text-white md:w-3/5 md:pr-16">-->
		<!--					<div class="text-5xl font-extrabold text-left md:text-6xl">-->
		<!--						<h2>Hi, I'm Favour!</h2>-->
		<!--					</div>-->

		<!--					<p class="my-4 text-xl md:text-2xl">-->
		<!--						A <strong>Fullstack Developer</strong> with a passion for building responsive <br-->
		<!--							class="hidden xl:block"> and beautifully-->
		<!--						crafted websites using the latest technologies.-->
		<!--					</p>-->

		<!--					<div class="inline-flex w-full">-->
		<!--						<input class="text-[#1F1627] py-3 px-6 font-medium w-full lg:w-96 rounded-l-full"-->
		<!--						       placeholder="Email address" type="email" />-->
		<!--						<button class="px-6 py-3 float-right lg:float-none font-semibold rounded-r-full bg-[#326059] focus:ring-2 focus:ring-black"-->
		<!--						        type="submit">-->
		<!--							Connect-->
		<!--						</button>-->
		<!--					</div>-->
		<!--				</div>-->
		<!--			</div>-->
		<!--		</section>-->
		<!-- hero section -->

		<!-- footer -->
		<Footer />
	</div>
</template>

<script>
	import About from "./components/About.vue";
	import Contact from "./components/Contact.vue";
	import Footer from "./components/Footer.vue";
	import Header from "./components/Header.vue";
	import Navbar from "./components/NavbarOld.vue";

	export default {
		name: "Home",
		components: { Header, About, Contact, Navbar, Footer },
	};
</script>
