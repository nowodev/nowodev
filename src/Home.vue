<template>
    <div class="bg-gradient-to-r from-gray-700 via-gray-900 to-black">
        <!-- <body class="bg-[#4F637D]"> -->
        <!-- <body class="bg-gradient-to-r from-yellow-400 via-gray-50 to-teal-300"> -->
        <!-- <body style="background: radial-gradient(rgb(253, 230, 138), rgb(124, 58, 237), rgb(12, 74, 110))"> -->
        <!-- <body style="background: radial-gradient(at 50% 0%, rgb(209, 213, 219), rgb(192, 38, 211), rgb(234, 88, 12))"> -->
        <!-- <body style="background: radial-gradient(at 50% 0%, rgb(180, 83, 9), rgb(253, 186, 116), rgb(159, 18, 57))"> -->
        <!-- <body style="background: radial-gradient(rgb(56, 189, 248), rgb(49, 46, 129))"> -->
        <!-- <body style="background: conic-gradient(rgb(199, 210, 254), rgb(71, 85, 105), rgb(199, 210, 254))"> -->

        <nav
                id="bgcolor"
                class="absolute top-0 z-50 flex flex-wrap items-center justify-between w-full bg-transparent"
        >
            <div
                    class="container flex flex-wrap items-center justify-between px-4 py-2 mx-auto text-center"
            >
                <div
                        class="relative flex justify-between w-full md:w-auto md:static md:block md:justify-start"
                >
                    <div class="w-auto h-auto p-1 bg-[#C2E812] rounded-full">
                        <a href="index.html">
                            <img alt="Logo" src="./assets/images/wolf.png" />
                        </a>
                    </div>

                    <button
                            class="p-2 text-3xl cursor-pointer md:hidden"
                            onclick="toggle_navbar('nav')"
                            type="button"
                    >
                        <i class="text-white fas fa-bars"></i>
                    </button>
                </div>

                <div
                        id="nav"
                        class="items-center flex-auto hidden mt-2 mb-2 bg-white rounded-lg md:flex grow md:mt-0 md:bg-transparent md:rounded-none"
                >
                    <ul
                            class="flex flex-col mr-auto text-lg font-bold text-black md:flex-row md:text-white"
                    >
                        <li class="flex">
                            <a class="p-4" href="#">About</a>
                        </li>
                        <li class="flex">
                            <a class="p-4" href="#">Works</a>
                        </li>
                        <li class="flex">
                            <a class="p-4" href="#">Services</a>
                        </li>
                        <li class="flex">
                            <a class="p-4" href="#">Contact</a>
                        </li>
                    </ul>

                    <ul
                            class="flex flex-row gap-2 cursor-pointer md:ml-auto md:text-white"
                    >
                        <li class="flex">
                            <a href="https://github.com/NowoDev" target="_blank">
                                <i class="p-4 text-2xl fab fa-github"></i>
                            </a>
                        </li>
                        <li class="flex">
                            <a href="https://twitter.com/nowodev" target="_blank">
                                <i class="p-4 text-2xl fab fa-twitter"></i>
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

        <!-- hero section -->
        <section class="relative flex min-h-screen pt-16">
            <div
                    class="container flex flex-col items-center mx-auto md:flex-row-reverse"
            >
                <div class="px-9 md:w-2/5 md:px-0">
                    <img alt="Favour" src="./assets/images/casual.png" />
                </div>

                <div class="text-white mt-9 px-9 md:w-3/5 md:pr-16">
                    <div
                            class="text-4xl font-extrabold text-center md:text-left lg:text-5xl xl:text-7xl"
                    >
                        <h1>Building digital products, brands experience</h1>
                    </div>

                    <p class="my-4 text-xl text-center md:block md:text-left">
                        a <strong>Laravel Developer</strong> and upcoming
                        <strong>Tailwind Developer</strong> based temporarily in NG.
                    </p>

                    <div class="lg:w-full lg:inline-flex">
                        <input
                                class="text-[#1F1627] py-1.5 px-4 lg:py-3 lg:rounded-none lg:rounded-l-full font-medium h-10 w-full lg:w-fit rounded-full"
                                placeholder="Email address"
                                type="email"
                        />
                        <button
                                class="px-6 py-1.5 mt-2 mb-5 lg:mt-0 float-right lg:float-none font-semibold lg:rounded-none lg:rounded-r-full bg-[#C2E812] focus:ring-2 focus:ring-black text-[#1F1627] h-10 text-sm md:text-base rounded-full"
                                type="submit"
                        >
                            Connect With Me
                        </button>
                    </div>
                </div>
            </div>
        </section>
        <!-- hero section -->

        <section class="relative flex w-full min-h-screen mt-16">
            <div class="container flex flex-col items-center mx-auto text-white">
                <div
                        class="flex flex-col justify-between w-full px-16 lg:px-24 md:flex-row lg:mb-12"
                >
                    <div class="w-full lg:p-4 md:w-2/5">
                        <h1 class="mb-3 text-4xl font-semibold lg:text-5xl">
                            My awesome <span class="text-gray-300">services</span>
                        </h1>
                        <p class="mb-3 font-medium text-justify lg:text-lg">
                            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
                            nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam
                            erat, sed diam voluptua.
                        </p>
                        <button
                                class="px-5 font-semibold py-1.5 bg-[#C2E812] focus:ring-2 focus:ring-black rounded-full text-[#1F1627]"
                        >
                            Download CV
                        </button>
                    </div>

                    <div
                            class="flex flex-col items-center p-6 mt-8 space-y-2 text-center shadow-lg rounded-3xl w-fit lg:ml-24 lg:mt-24 h-fit shadow-black md:w-64"
                    >
                        <img
                                alt="Wolf"
                                class="p-1 rounded-full bg-[#C2E812]"
                                src="./assets/images/wolf.png"
                        />
                        <h1 class="font-semibold">Design</h1>
                        <p class="font-normal">
                            lorem ipsum dummy text are uually used for prints and websites
                            industry. So I used theirs also.
                        </p>

                        <button
                                class="px-5 font-semibold py-1.5 bg-[#C2E812] focus:ring-2 focus:ring-black rounded-full text-[#1F1627]"
                        >
                            Learn More
                        </button>
                    </div>
                </div>

                <div
                        class="flex flex-col justify-around w-full px-16 lg:px-24 md:flex-row"
                >
                    <div
                            class="flex flex-col items-center p-6 mt-8 space-y-2 text-center shadow-lg rounded-3xl w-fit lg:ml-24 md:-mt-6 h-fit shadow-black md:w-64 lg:-mt-20"
                    >
                        <img
                                alt="Wolf"
                                class="p-1 rounded-full bg-[#C2E812]"
                                src="./assets/images/wolf.png"
                        />
                        <h1 class="font-semibold">Development</h1>
                        <p class="font-normal">
                            lorem ipsum dummy text are uually used for prints and websites
                            industry. So I used theirs also.
                        </p>

                        <button
                                class="px-5 font-semibold py-1.5 bg-[#C2E812] focus:ring-2 focus:ring-black rounded-full text-[#1F1627]"
                        >
                            Learn More
                        </button>
                    </div>

                    <div
                            class="flex flex-col items-center p-6 my-8 space-y-2 text-center shadow-lg rounded-3xl w-fit h-fit shadow-black md:w-64"
                    >
                        <img
                                alt="Wolf"
                                class="p-1 rounded-full bg-[#C2E812]"
                                src="./assets/images/wolf.png"
                        />
                        <h1 class="font-semibold">UX</h1>
                        <p class="font-normal">
                            lorem ipsum dummy text are uually used for prints and websites
                            industry. So I used theirs also.
                        </p>

                        <button
                                class="px-5 font-semibold py-1.5 bg-[#C2E812] focus:ring-2 focus:ring-black rounded-full text-[#1F1627]"
                        >
                            Learn More
                        </button>
                    </div>
                </div>
            </div>
        </section>

        <!-- works -->
        <section class="relative w-full min-h-screen mt-16">
            <div class="container items-center mx-auto text-white px-16">
                <h3 class="text-white font-bold text-2xl">
                    Clients always get
                    <span class="text-[#C2E812]">exceptional works</span> from me .......
                </h3>

                <div class="flex overflow-x-scroll mt-7 hide-scroll-bar">
                    <div class="flex flex-nowrap px-2 space-x-4 py-4">
                        <div
                                class="bg-white h-64 w-64 rounded-lg overflow-hidden hover:scale-110 delay-150 transition duration-300 ease-in-out"
                        ></div>
                        <div
                                class="bg-white h-64 w-64 rounded-lg overflow-hidden hover:scale-110 delay-150 transition duration-300 ease-in-out"
                        ></div>
                        <div
                                class="bg-white h-64 w-64 rounded-lg overflow-hidden hover:scale-110 delay-150 transition duration-300 ease-in-out"
                        ></div>
                        <div
                                class="bg-white h-64 w-64 rounded-lg overflow-hidden hover:scale-110 delay-150 transition duration-300 ease-in-out"
                        ></div>
                        <div
                                class="bg-white h-64 w-64 rounded-lg overflow-hidden hover:scale-110 delay-150 transition duration-300 ease-in-out"
                        ></div>
                        <div
                                class="bg-white h-64 w-64 rounded-lg overflow-hidden hover:scale-110 delay-150 transition duration-300 ease-in-out"
                        ></div>
                    </div>
                </div>

                <div class="flex flex-col md:flex-row md:justify-between">
                    <div class="mt-16 md:w-2/5">
                        <h3 class="text-white font-bold text-2xl capitalize underline decoration-sky-400">
                            For my workflow, I use the following
                            <span class="text-[#C2E812]">tools</span>
                        </h3>
                        <p class="text-lg text-justify font-medium">
                            Adipisicing et voluptate do cillum. Sit id esse Lorem magna dolor
                            sit amet aliqua cillum minim et consectetur magna ad. Mollit enim
                            sit exercitation exercitation. Sit labore non qui voluptate enim in
                            culpa nisi.
                        </p>

                        <button
                                class="px-8 mt-5 font-semibold py-1.5 bg-[#C2E812] focus:ring-2 focus:ring-black rounded-full text-[#1F1627]"
                        >
                            Hire me
                        </button>
                    </div>

                    <div
                            class="w-full md:w-1/2 h-auto border bg-gray-600 rounded-full items-center mt-10"
                    >
                        <div class="flex justify-between p-6">
                            <i class="fa-brands fa-laravel text-[#FF2D20] text-7xl"></i>
                            <i class="fa-brands fa-html5 text-[#E34F26] text-7xl"></i>
                        </div>
                        <div class="text-center">
                            <i class="fa-brands fa-php text-[#3178C6] text-7xl"></i>
                        </div>
                        <div class="flex justify-between p-6">
                            <i class="fa-brands fa-js text-[#F7DF1E] text-7xl"></i>
                            <i class="fa-brands fa-github text-black text-7xl"></i>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- footer -->
        <footer class="container mx-auto py-9">
            <p class="font-bold text-center text-white underline decoration-sky-500/30 decoration-wavy">&COPY; NowoDev
                2021 - {{ year }}
            </p>
        </footer>
    </div>
</template>

<script>
    export default {
        name: "Home",

        data() {
            return {
                show: false,
                year: new Date().getFullYear()
            }
        },

        methods: {
            toggleNavbar: function () {
                this.show = !this.show
            }
        }
        //     function toggle_navbar(navId) {
        // document.getElementById(navId).classList.toggle("hidden");
        // document.getElementById(navId).classList.toggle("block");
        //
        // document.getElementById("bgcolor").classList.toggle("bg-transparent");
        // document.getElementById("bgcolor").classList.toggle("bg-black");
    }
</script>