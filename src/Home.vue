<template>
    <!--    <div class="bg-gradient-to-r from-gray-700 via-gray-900 to-black">-->
    <!--         <div class="bg-[#4F637D]">-->
    <!--         <div class="bg-gradient-to-r from-yellow-400 via-gray-50 to-teal-300">-->
    <!-- <div style="background: radial-gradient(rgb(253, 230, 138), rgb(124, 58, 237), rgb(12, 74, 110))"> -->
    <!-- <div style="background: radial-gradient(at 50% 0%, rgb(209, 213, 219), rgb(192, 38, 211), rgb(234, 88, 12))"> -->
    <!-- <div style="background: radial-gradient(at 50% 0%, rgb(180, 83, 9), rgb(253, 186, 116), rgb(159, 18, 57))"> -->
    <div style="background: radial-gradient(rgb(56, 189, 248), rgb(49, 46, 129))">
        <!-- <div style="background: conic-gradient(rgb(199, 210, 254), rgb(71, 85, 105), rgb(199, 210, 254))"> -->

        <Navbar />

        <!-- hero section -->
        <section id="home" class="flex relative pt-16 min-h-screen">
            <div class="container flex flex-col items-center mx-auto md:flex-row-reverse">
                <div class="px-9 md:w-2/5 md:px-0">
                    <img alt="Favour" class="w-72 md:w-full" src="./assets/images/casual.png" />
                </div>

                <div class="px-9 mt-9 text-white md:w-3/5 md:pr-16">
                    <div class="text-4xl font-extrabold text-center md:text-left lg:text-5xl xl:text-7xl">
                        <h1>Building digital products, brands experience</h1>
                    </div>

                    <p class="my-4 text-xl text-center md:block md:text-left">
                        A <strong>Fullstack Developer</strong> with a passion for building responsive <br
                            class="hidden xl:block"> and beautifully
                        crafted websites using the latest technologies.
                    </p>

                    <div class="inline-flex w-full">
                        <input class="text-[#1F1627] py-3 px-6 font-medium w-full lg:w-96 rounded-l-full"
                               placeholder="Email address" type="email" />
                        <button class="px-6 py-3 float-right lg:float-none font-semibold rounded-r-full bg-[#326059] focus:ring-2 focus:ring-black"
                                type="submit">
                            Connect
                        </button>
                    </div>
                </div>
            </div>
        </section>
        <!-- hero section -->

        <section id="about" class="min-h-screen"></section>

        <section id="services" class="flex relative mt-16 w-full min-h-screen">
            <div class="container flex flex-col items-center mx-auto text-white">
                <div class="flex flex-col justify-between px-16 w-full lg:px-24 md:flex-row lg:mb-12">
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
                                class="px-5 font-semibold py-1.5 bg-[#C2E812] focus:ring-2 focus:ring-black rounded-full text-[#1F1627]">
                            Download CV
                        </button>
                    </div>

                    <div class="flex flex-col items-center p-6 mt-8 space-y-2 text-center rounded-3xl shadow-lg w-fit lg:ml-24 lg:mt-24 h-fit shadow-black md:w-64">
                        <img alt="Wolf" class="p-1 rounded-full bg-[#C2E812]"
                             src="./assets/images/wolf.png" />
                        <h1 class="font-semibold">Design</h1>
                        <p class="font-normal">
                            lorem ipsum dummy text are uually used for prints and websites
                            industry. So I used theirs also.
                        </p>

                        <button class="px-5 font-semibold py-1.5 bg-[#C2E812] focus:ring-2 focus:ring-black rounded-full text-[#1F1627]">
                            Learn More
                        </button>
                    </div>
                </div>

                <div class="flex flex-col justify-around px-16 w-full lg:px-24 md:flex-row">
                    <div class="flex flex-col items-center p-6 mt-8 space-y-2 text-center rounded-3xl shadow-lg w-fit lg:ml-24 md:-mt-6 h-fit shadow-black md:w-64 lg:-mt-20">
                        <img alt="Wolf" class="p-1 rounded-full bg-[#C2E812]"
                             src="./assets/images/wolf.png" />
                        <h1 class="font-semibold">Development</h1>
                        <p class="font-normal">
                            lorem ipsum dummy text are uually used for prints and websites
                            industry. So I used theirs also.
                        </p>

                        <button class="px-5 font-semibold py-1.5 bg-[#C2E812] focus:ring-2 focus:ring-black rounded-full text-[#1F1627]">
                            Learn More
                        </button>
                    </div>

                    <div class="flex flex-col items-center p-6 my-8 space-y-2 text-center rounded-3xl shadow-lg w-fit h-fit shadow-black md:w-64">
                        <img alt="Wolf" class="p-1 rounded-full bg-[#C2E812]"
                             src="./assets/images/wolf.png" />
                        <h1 class="font-semibold">UX</h1>
                        <p class="font-normal">
                            lorem ipsum dummy text are uually used for prints and websites
                            industry. So I used theirs also.
                        </p>

                        <button class="px-5 font-semibold py-1.5 bg-[#C2E812] focus:ring-2 focus:ring-black rounded-full text-[#1F1627]">
                            Learn More
                        </button>
                    </div>
                </div>
            </div>
        </section>

        <section id="contact" class="min-h-screen"></section>

        <!-- works -->
        <section class="relative mt-16 w-full min-h-screen">
            <div class="container items-center px-16 mx-auto text-white">
                <h3 class="text-2xl font-bold text-white">
                    Clients always get
                    <span class="text-[#C2E812]">exceptional works</span> from me .......
                </h3>

                <div class="flex overflow-x-scroll mt-7 hide-scroll-bar">
                    <div class="flex flex-nowrap px-2 py-4 space-x-4">
                        <div class="overflow-hidden w-64 h-64 bg-white rounded-lg transition duration-300 ease-in-out delay-150 hover:scale-110">
                        </div>
                        <div class="overflow-hidden w-64 h-64 bg-white rounded-lg transition duration-300 ease-in-out delay-150 hover:scale-110">
                        </div>
                        <div class="overflow-hidden w-64 h-64 bg-white rounded-lg transition duration-300 ease-in-out delay-150 hover:scale-110">
                        </div>
                        <div class="overflow-hidden w-64 h-64 bg-white rounded-lg transition duration-300 ease-in-out delay-150 hover:scale-110">
                        </div>
                        <div class="overflow-hidden w-64 h-64 bg-white rounded-lg transition duration-300 ease-in-out delay-150 hover:scale-110">
                        </div>
                        <div class="overflow-hidden w-64 h-64 bg-white rounded-lg transition duration-300 ease-in-out delay-150 hover:scale-110">
                        </div>
                    </div>
                </div>

                <div class="flex flex-col md:flex-row md:justify-between">
                    <div class="mt-16 md:w-2/5">
                        <h3 class="text-2xl font-bold text-white underline capitalize decoration-sky-400">
                            For my workflow, I use the following
                            <span class="text-[#C2E812]">tools</span>
                        </h3>
                        <p class="text-lg font-medium text-justify">
                            Adipisicing et voluptate do cillum. Sit id esse Lorem magna dolor
                            sit amet aliqua cillum minim et consectetur magna ad. Mollit enim
                            sit exercitation exercitation. Sit labore non qui voluptate enim
                            in culpa nisi.
                        </p>

                        <button class="px-8 mt-5 font-semibold py-1.5 bg-[#C2E812] focus:ring-2 focus:ring-black rounded-full text-[#1F1627]">
                            Hire me
                        </button>
                    </div>

                    <div class="items-center mt-10 w-full h-auto bg-gray-600 rounded-full border md:w-1/2">
                        <div class="flex justify-between p-6">
                            <svg class="w-9 h-9 fill-[#FF2D20]" viewBox="0 0 512 512"
                                 xmlns="http://www.w3.org/2000/svg">
                                <!--! Font Awesome Pro 6.1.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
                                <path d="M504.4,115.83a5.72,5.72,0,0,0-.28-.68,8.52,8.52,0,0,0-.53-1.25,6,6,0,0,0-.54-.71,9.36,9.36,0,0,0-.72-.94c-.23-.22-.52-.4-.77-.6a8.84,8.84,0,0,0-.9-.68L404.4,55.55a8,8,0,0,0-8,0L300.12,111h0a8.07,8.07,0,0,0-.88.69,7.68,7.68,0,0,0-.78.6,8.23,8.23,0,0,0-.72.93c-.17.24-.39.45-.54.71a9.7,9.7,0,0,0-.52,1.25c-.08.23-.21.44-.28.68a8.08,8.08,0,0,0-.28,2.08V223.18l-80.22,46.19V63.44a7.8,7.8,0,0,0-.28-2.09c-.06-.24-.2-.45-.28-.68a8.35,8.35,0,0,0-.52-1.24c-.14-.26-.37-.47-.54-.72a9.36,9.36,0,0,0-.72-.94,9.46,9.46,0,0,0-.78-.6,9.8,9.8,0,0,0-.88-.68h0L115.61,1.07a8,8,0,0,0-8,0L11.34,56.49h0a6.52,6.52,0,0,0-.88.69,7.81,7.81,0,0,0-.79.6,8.15,8.15,0,0,0-.71.93c-.18.25-.4.46-.55.72a7.88,7.88,0,0,0-.51,1.24,6.46,6.46,0,0,0-.29.67,8.18,8.18,0,0,0-.28,2.1v329.7a8,8,0,0,0,4,6.95l192.5,110.84a8.83,8.83,0,0,0,1.33.54c.21.08.41.2.63.26a7.92,7.92,0,0,0,4.1,0c.2-.05.37-.16.55-.22a8.6,8.6,0,0,0,1.4-.58L404.4,400.09a8,8,0,0,0,4-6.95V287.88l92.24-53.11a8,8,0,0,0,4-7V117.92A8.63,8.63,0,0,0,504.4,115.83ZM111.6,17.28h0l80.19,46.15-80.2,46.18L31.41,63.44Zm88.25,60V278.6l-46.53,26.79-33.69,19.4V123.5l46.53-26.79Zm0,412.78L23.37,388.5V77.32L57.06,96.7l46.52,26.8V338.68a6.94,6.94,0,0,0,.12.9,8,8,0,0,0,.16,1.18h0a5.92,5.92,0,0,0,.38.9,6.38,6.38,0,0,0,.42,1v0a8.54,8.54,0,0,0,.6.78,7.62,7.62,0,0,0,.66.84l0,0c.23.22.52.38.77.58a8.93,8.93,0,0,0,.86.66l0,0,0,0,92.19,52.18Zm8-106.17-80.06-45.32,84.09-48.41,92.26-53.11,80.13,46.13-58.8,33.56Zm184.52,4.57L215.88,490.11V397.8L346.6,323.2l45.77-26.15Zm0-119.13L358.68,250l-46.53-26.79V131.79l33.69,19.4L392.37,178Zm8-105.28-80.2-46.17,80.2-46.16,80.18,46.15Zm8,105.28V178L455,151.19l33.68-19.4v91.39h0Z" />
                            </svg>
                            <svg class="w-9 h-9 fill-[#E34F26]" viewBox="0 0 384 512"
                                 xmlns="http://www.w3.org/2000/svg">
                                <!--! Font Awesome Pro 6.1.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
                                <path d="M0 32l34.9 395.8L191.5 480l157.6-52.2L384 32H0zm308.2 127.9H124.4l4.1 49.4h175.6l-13.6 148.4-97.9 27v.3h-1.1l-98.7-27.3-6-75.8h47.7L138 320l53.5 14.5 53.7-14.5 6-62.2H84.3L71.5 112.2h241.1l-4.4 47.7z" />
                            </svg>
                        </div>

                        <div class="flex justify-center">
                            <svg class="w-9 h-9 fill-[#3178C6]" viewBox="0 0 640 512"
                                 xmlns="http://www.w3.org/2000/svg">
                                <!--! Font Awesome Pro 6.1.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
                                <path d="M320 104.5c171.4 0 303.2 72.2 303.2 151.5S491.3 407.5 320 407.5c-171.4 0-303.2-72.2-303.2-151.5S148.7 104.5 320 104.5m0-16.8C143.3 87.7 0 163 0 256s143.3 168.3 320 168.3S640 349 640 256 496.7 87.7 320 87.7zM218.2 242.5c-7.9 40.5-35.8 36.3-70.1 36.3l13.7-70.6c38 0 63.8-4.1 56.4 34.3zM97.4 350.3h36.7l8.7-44.8c41.1 0 66.6 3 90.2-19.1 26.1-24 32.9-66.7 14.3-88.1-9.7-11.2-25.3-16.7-46.5-16.7h-70.7L97.4 350.3zm185.7-213.6h36.5l-8.7 44.8c31.5 0 60.7-2.3 74.8 10.7 14.8 13.6 7.7 31-8.3 113.1h-37c15.4-79.4 18.3-86 12.7-92-5.4-5.8-17.7-4.6-47.4-4.6l-18.8 96.6h-36.5l32.7-168.6zM505 242.5c-8 41.1-36.7 36.3-70.1 36.3l13.7-70.6c38.2 0 63.8-4.1 56.4 34.3zM384.2 350.3H421l8.7-44.8c43.2 0 67.1 2.5 90.2-19.1 26.1-24 32.9-66.7 14.3-88.1-9.7-11.2-25.3-16.7-46.5-16.7H417l-32.8 168.7z" />
                            </svg>
                        </div>

                        <div class="flex justify-between p-6">
                            <svg class="w-9 h-9" style="fill: #000000" viewBox="0 0 48 48"
                                 xmlns="http://www.w3.org/2000/svg">
                                <path d="M6,42V6h36v36H6z" fill="#ffd600"></path>
                                <path d="M29.538 32.947c.692 1.124 1.444 2.201 3.037 2.201 1.338 0 2.04-.665 2.04-1.585 0-1.101-.726-1.492-2.198-2.133l-.807-.344c-2.329-.988-3.878-2.226-3.878-4.841 0-2.41 1.845-4.244 4.728-4.244 2.053 0 3.528.711 4.592 2.573l-2.514 1.607c-.553-.988-1.151-1.377-2.078-1.377-.946 0-1.545.597-1.545 1.377 0 .964.6 1.354 1.985 1.951l.807.344C36.452 29.645 38 30.839 38 33.523 38 36.415 35.716 38 32.65 38c-2.999 0-4.702-1.505-5.65-3.368L29.538 32.947zM17.952 33.029c.506.906 1.275 1.603 2.381 1.603 1.058 0 1.667-.418 1.667-2.043V22h3.333v11.101c0 3.367-1.953 4.899-4.805 4.899-2.577 0-4.437-1.746-5.195-3.368L17.952 33.029z"
                                      fill="#000001"></path>
                            </svg>
                            <svg class="w-9 h-9" style="fill: #000000" viewBox="0 0 30 30"
                                 xmlns="http://www.w3.org/2000/svg">
                                <path d="M15,3C8.373,3,3,8.373,3,15c0,5.623,3.872,10.328,9.092,11.63C12.036,26.468,12,26.28,12,26.047v-2.051 c-0.487,0-1.303,0-1.508,0c-0.821,0-1.551-0.353-1.905-1.009c-0.393-0.729-0.461-1.844-1.435-2.526 c-0.289-0.227-0.069-0.486,0.264-0.451c0.615,0.174,1.125,0.596,1.605,1.222c0.478,0.627,0.703,0.769,1.596,0.769 c0.433,0,1.081-0.025,1.691-0.121c0.328-0.833,0.895-1.6,1.588-1.962c-3.996-0.411-5.903-2.399-5.903-5.098 c0-1.162,0.495-2.286,1.336-3.233C9.053,10.647,8.706,8.73,9.435,8c1.798,0,2.885,1.166,3.146,1.481C13.477,9.174,14.461,9,15.495,9 c1.036,0,2.024,0.174,2.922,0.483C18.675,9.17,19.763,8,21.565,8c0.732,0.731,0.381,2.656,0.102,3.594 c0.836,0.945,1.328,2.066,1.328,3.226c0,2.697-1.904,4.684-5.894,5.097C18.199,20.49,19,22.1,19,23.313v2.734 c0,0.104-0.023,0.179-0.035,0.268C23.641,24.676,27,20.236,27,15C27,8.373,21.627,3,15,3z">
                                </path>
                            </svg>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- footer -->
        <Footer />
    </div>
</template>

<script>
    import Footer from "./components/Footer.vue";
    import Navbar from "./components/Navbar.vue";

    export default {
        name: "Home",
        components: { Navbar, Footer },
    };
</script>
