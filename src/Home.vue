<template>
    <div class="min-h-screen h-screen bg-marshland-500">
        <!-- Header -->
        <header
            class="flex flex-wrap sm:justify-start sm:flex-nowrap z-50 w-full bg-white text-sm py-4 dark:bg-gray-800">
            <nav class="max-w-[85rem] w-full mx-auto px-4 sm:flex sm:items-center sm:justify-between"
                aria-label="Global">
                <div class="flex items-center justify-between">
                    <a class="flex-none text-xl font-semibold dark:text-white" href="#">NowoDev</a>
                    <div class="sm:hidden">
                        <button type="button"
                            class="hs-collapse-toggle p-2 inline-flex justify-center items-center gap-2 rounded-md border font-medium bg-white text-gray-700 shadow-sm align-middle hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-white focus:ring-blue-600 transition-all text-sm dark:bg-gray-800 dark:hover:bg-slate-800 dark:border-gray-700 dark:text-gray-400 dark:hover:text-white dark:focus:ring-offset-gray-800"
                            data-hs-collapse="#navbar-collapse-with-animation"
                            aria-controls="navbar-collapse-with-animation"
                            aria-label="Toggle navigation">
                            <svg class="hs-collapse-open:hidden w-4 h-4" width="16" height="16"
                                fill="currentColor" viewBox="0 0 16 16">
                                <path fill-rule="evenodd"
                                    d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z" />
                            </svg>
                            <svg class="hs-collapse-open:block hidden w-4 h-4" width="16"
                                height="16" fill="currentColor" viewBox="0 0 16 16">
                                <path
                                    d="M4.646 4.646a.5.5 0 0 1 .708 0L8 7.293l2.646-2.647a.5.5 0 0 1 .708.708L8.707 8l2.647 2.646a.5.5 0 0 1-.708.708L8 8.707l-2.646 2.647a.5.5 0 0 1-.708-.708L7.293 8 4.646 5.354a.5.5 0 0 1 0-.708z" />
                            </svg>
                        </button>
                    </div>
                </div>
                <div id="navbar-collapse-with-animation"
                    class="hs-collapse hidden overflow-hidden transition-all duration-300 basis-full grow sm:block">
                    <div
                        class="flex flex-col gap-5 mt-5 sm:flex-row sm:items-center sm:justify-end sm:mt-0 sm:pl-5">
                        <a class="font-medium text-blue-500" href="#" aria-current="page">About</a>
                        <a class="font-medium text-gray-600 hover:text-gray-400 dark:text-gray-400 dark:hover:text-gray-500"
                            href="#">Portfolio</a>
                        <a class="font-medium text-gray-600 hover:text-gray-400 dark:text-gray-400 dark:hover:text-gray-500"
                            href="#">Work</a>
                        <a class="font-medium text-gray-600 hover:text-gray-400 dark:text-gray-400 dark:hover:text-gray-500"
                            href="#">Contact</a>
                    </div>
                </div>
            </nav>
        </header>

        <main class="h-full w-full">
            <!-- Hero -->
            <section class="h-full w-full flex bg-deco-500">
                <div class="relative z-10 md:w-1/2">
                    <div
                        class="flex h-full flex-col justify-center items-center md:items-start space-y-1 md:space-y-2 px-6 max-w-[42.5rem] ml-auto">
                        <h1 class="text-xl md:text-2xl font-extrabold">FULLSTACK DEVELOPER</h1>
                        <h2 class="text-xl md:text-7xl font-extrabold">I'm Favour</h2>
                        <button
                            class="font-bold hover:text-white border border-cardinal-pink-400 bg-cardinal-pink-200 inline-flex w-fit px-5 rounded-lg items-center transition-all duration-500 hover:bg-cardinal-pink-400 hover:translate-y-2 focus:ring-2 focus:ring-cardinal-pink-500 outline-none">
                            Learn more
                            <span aria-label="Scroll down" class="animate-pulse">
                                <svg xmlns="http://www.w3.org/2000/svg"
                                    class="icon icon-tabler icon-tabler-chevrons-down" width="24"
                                    height="44" viewBox="0 0 24 24" stroke-width="1.5"
                                    stroke="#820263" fill="none" stroke-linecap="round"
                                    stroke-linejoin="round">
                                    <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                                    <polyline points="7 7 12 12 17 7" />
                                    <polyline points="7 13 12 18 17 13" />
                                </svg>
                            </span>
                        </button>
                    </div>
                </div>

                <div class="absolute w-full h-full grid place-items-center z-0 md:hidden">
                    <img src="./assets/images/casual.png" width="280px" alt="">
                </div>

                <div class="relative z-20 h-full w-1/2 bg-sinbad-500 hidden md:flex">
                    <div class="w-full h-full grid place-items-center px-6 max-w-[42.5rem]">
                        <img src="./assets/images/casual.png" class="max-w-lg w-full" alt="">
                    </div>
                </div>
            </section>

            <section class="px-0 py-12 mx-auto max-w-7xl sm:px-4">
                <div class="text-white bg-deco-800 border-deco-800 rounded-none sm:rounded-lg">
                    <div
                        class="flex flex-col items-center justify-between px-1 py-4 lg:flex-row sm:py-4 sm:px-7">
                        <p class="mb-6 font-semibold lg:mb-0 text-lg">Sleep peacefully knowing
                            that your project is being built by the best hands.</p>
                        <button
                            class="w-full bg-white py-2 px-6 rounded-md inline-block text-lg text-green-800 shadow sm:w-auto font-bold">Contact
                            me</button>
                    </div>
                </div>
            </section>

            <section class="text-gray-600 body-font">
                <div class="container px-5 py-24 mx-auto">
                    <div class="text-center mb-20">
                        <h1
                            class="sm:text-3xl text-2xl font-medium text-center title-font text-gray-900 mb-4">
                            Raw Denim Heirloom Man Braid</h1>
                        <p class="text-base leading-relaxed xl:w-2/4 lg:w-3/4 mx-auto">Blue bottle
                            crucifix vinyl post-ironic four dollar toast vegan taxidermy. Gastropub
                            indxgo juice poutine, ramps microdosing banh mi pug.</p>
                    </div>
                    <div class="flex flex-wrap lg:w-4/5 sm:mx-auto sm:mb-2 -mx-2">
                        <div class="p-2 sm:w-1/2 w-full">
                            <div class="bg-gray-100 rounded flex p-4 h-full items-center">
                                <svg fill="none" stroke="currentColor" stroke-linecap="round"
                                    stroke-linejoin="round" stroke-width="3"
                                    class="text-indigo-500 w-6 h-6 flex-shrink-0 mr-4"
                                    viewBox="0 0 24 24">
                                    <path d="M22 11.08V12a10 10 0 11-5.93-9.14"></path>
                                    <path d="M22 4L12 14.01l-3-3"></path>
                                </svg>
                                <span class="title-font font-medium">Authentic Cliche Forage</span>
                            </div>
                        </div>
                        <div class="p-2 sm:w-1/2 w-full">
                            <div class="bg-gray-100 rounded flex p-4 h-full items-center">
                                <svg fill="none" stroke="currentColor" stroke-linecap="round"
                                    stroke-linejoin="round" stroke-width="3"
                                    class="text-indigo-500 w-6 h-6 flex-shrink-0 mr-4"
                                    viewBox="0 0 24 24">
                                    <path d="M22 11.08V12a10 10 0 11-5.93-9.14"></path>
                                    <path d="M22 4L12 14.01l-3-3"></path>
                                </svg>
                                <span class="title-font font-medium">Kinfolk Chips Snackwave</span>
                            </div>
                        </div>
                        <div class="p-2 sm:w-1/2 w-full">
                            <div class="bg-gray-100 rounded flex p-4 h-full items-center">
                                <svg fill="none" stroke="currentColor" stroke-linecap="round"
                                    stroke-linejoin="round" stroke-width="3"
                                    class="text-indigo-500 w-6 h-6 flex-shrink-0 mr-4"
                                    viewBox="0 0 24 24">
                                    <path d="M22 11.08V12a10 10 0 11-5.93-9.14"></path>
                                    <path d="M22 4L12 14.01l-3-3"></path>
                                </svg>
                                <span class="title-font font-medium">Coloring Book Ethical</span>
                            </div>
                        </div>
                        <div class="p-2 sm:w-1/2 w-full">
                            <div class="bg-gray-100 rounded flex p-4 h-full items-center">
                                <svg fill="none" stroke="currentColor" stroke-linecap="round"
                                    stroke-linejoin="round" stroke-width="3"
                                    class="text-indigo-500 w-6 h-6 flex-shrink-0 mr-4"
                                    viewBox="0 0 24 24">
                                    <path d="M22 11.08V12a10 10 0 11-5.93-9.14"></path>
                                    <path d="M22 4L12 14.01l-3-3"></path>
                                </svg>
                                <span class="title-font font-medium">Typewriter Polaroid Cray</span>
                            </div>
                        </div>
                        <div class="p-2 sm:w-1/2 w-full">
                            <div class="bg-gray-100 rounded flex p-4 h-full items-center">
                                <svg fill="none" stroke="currentColor" stroke-linecap="round"
                                    stroke-linejoin="round" stroke-width="3"
                                    class="text-indigo-500 w-6 h-6 flex-shrink-0 mr-4"
                                    viewBox="0 0 24 24">
                                    <path d="M22 11.08V12a10 10 0 11-5.93-9.14"></path>
                                    <path d="M22 4L12 14.01l-3-3"></path>
                                </svg>
                                <span class="title-font font-medium">Pack Truffaut Blue</span>
                            </div>
                        </div>
                        <div class="p-2 sm:w-1/2 w-full">
                            <div class="bg-gray-100 rounded flex p-4 h-full items-center">
                                <svg fill="none" stroke="currentColor" stroke-linecap="round"
                                    stroke-linejoin="round" stroke-width="3"
                                    class="text-indigo-500 w-6 h-6 flex-shrink-0 mr-4"
                                    viewBox="0 0 24 24">
                                    <path d="M22 11.08V12a10 10 0 11-5.93-9.14"></path>
                                    <path d="M22 4L12 14.01l-3-3"></path>
                                </svg>
                                <span class="title-font font-medium">The Catcher In The Rye</span>
                            </div>
                        </div>
                    </div>
                    <button
                        class="flex mx-auto mt-16 text-white bg-indigo-500 border-0 py-2 px-8 focus:outline-none hover:bg-indigo-600 rounded text-lg">Button</button>
                </div>
            </section>

            <!-- Section 1 -->
            <section class="h-auto bg-marshland-400">
                <div class="px-10 py-24 mx-auto max-w-7xl">
                    <div class="w-full mx-auto text-left md:text-center">
                        <h1
                            class="mb-6 text-5xl font-extrabold leading-none max-w-5xl mx-auto tracking-normal text-gray-900 sm:text-6xl md:text-6xl lg:text-7xl md:tracking-tight">
                            The <span
                                class="w-full text-transparent bg-clip-text bg-gradient-to-r from-sinbad-400 via-cardinal-pink-500 to-deco-500 lg:inline">Number
                                One Source</span> for<br class="lg:block hidden"> all your
                            development
                            needs. </h1>
                    </div>
                </div>
            </section>

            <!-- Section 3 -->
            <section class="flex items-center justify-center py-20 bg-white">
                <div class="px-16 bg-white">
                    <div class="max-w-[85rem] flex flex-col items-start mx-auto lg:items-center">
                        <h2
                            class="relative flex items-start justify-start w-full max-w-3xl text-5xl font-bold lg:justify-center">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor"
                                class="absolute right-0 hidden w-12 h-12 -mt-2 -mr-16 text-gray-200 lg:inline-block"
                                viewBox="0 0 975.036 975.036">
                                <path
                                    d="M925.036 57.197h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.399 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l36 76c11.6 24.399 40.3 35.1 65.1 24.399 66.2-28.6 122.101-64.8 167.7-108.8 55.601-53.7 93.7-114.3 114.3-181.9 20.601-67.6 30.9-159.8 30.9-276.8v-239c0-27.599-22.401-50-50-50zM106.036 913.497c65.4-28.5 121-64.699 166.9-108.6 56.1-53.7 94.4-114.1 115-181.2 20.6-67.1 30.899-159.6 30.899-277.5v-239c0-27.6-22.399-50-50-50h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.4 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l35.9 75.8c11.601 24.399 40.501 35.2 65.301 24.399z">
                                </path>
                            </svg>
                            See what others have to say
                        </h2>
                        <div class="block w-full h-0.5 max-w-lg mt-6 bg-purple-100 rounded-full">
                        </div>

                        <div class="items-center justify-center w-full mt-12 mb-4 lg:flex">
                            <div
                                class="flex flex-col items-start justify-start w-full h-auto mb-12 lg:w-1/3 lg:mb-0">
                                <div class="flex items-center justify-center">
                                    <div
                                        class="w-16 h-16 mr-4 overflow-hidden bg-gray-200 rounded-full">
                                        <img src="https://images.unsplash.com/photo-1527980965255-d3b416303d12?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=1700&amp;q=80"
                                            class="object-cover w-full h-full">
                                    </div>
                                    <div class="flex flex-col items-start justify-center">
                                        <h4 class="font-bold text-gray-800">John Doe</h4>
                                        <p class="text-gray-600">CEO of Something</p>
                                    </div>
                                </div>
                                <blockquote class="mt-8 text-lg text-gray-500">"This is a no-brainer
                                    if you want to take your business to the next level. If you are
                                    looking for the ultimate toolset, this is it!"</blockquote>
                            </div>
                            <div
                                class="flex flex-col items-start justify-start w-full h-auto px-0 mx-0 mb-12 border-l border-r border-transparent lg:w-1/3 lg:mb-0 lg:px-8 lg:mx-8 lg:border-gray-200">
                                <div class="flex items-center justify-center">
                                    <div
                                        class="w-16 h-16 mr-4 overflow-hidden bg-gray-200 rounded-full">
                                        <img src="https://images.unsplash.com/photo-1544725176-7c40e5a71c5e?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=2547&amp;q=80"
                                            class="object-cover w-full h-full">
                                    </div>
                                    <div class="flex flex-col items-start justify-center">
                                        <h4 class="font-bold text-gray-800">Jane Doe</h4>
                                        <p class="text-gray-600">CTO of Business</p>
                                    </div>
                                </div>
                                <blockquote class="mt-8 text-lg text-gray-500">"Thanks for creating
                                    this service. My life is so much
                                    easier.
                                    Thanks for making such a great product."</blockquote>
                            </div>
                            <div
                                class="flex flex-col items-start justify-start w-full h-auto lg:w-1/3">
                                <div class="flex items-center justify-center">
                                    <div
                                        class="w-16 h-16 mr-4 overflow-hidden bg-gray-200 rounded-full">
                                        <img src="https://images.unsplash.com/photo-1545167622-3a6ac756afa4?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=1256&amp;q=80"
                                            class="object-cover w-full h-full">
                                    </div>
                                    <div class="flex flex-col items-start justify-center">
                                        <h4 class="font-bold text-gray-800">John Smith</h4>
                                        <p class="text-gray-600">Creator of Stuff</p>
                                    </div>
                                </div>
                                <blockquote class="mt-8 text-lg text-gray-500">"Packed with awesome
                                    content and exactly what I was
                                    looking
                                    for. I would highly recommend this to anyone."</blockquote>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Section 4 -->
            <section class="text-gray-700 bg-white body-font">
                <div
                    class="container flex flex-col items-center px-8 py-8 mx-auto max-w-7xl sm:flex-row">
                    <a href="#_"
                        class="text-xl font-black leading-none text-gray-900 select-none logo">nowodev<span
                            class="text-indigo-600">.</span></a>
                    <p
                        class="mt-4 text-sm text-gray-500 sm:ml-4 sm:pl-4 sm:border-l sm:border-gray-200 sm:mt-0">
                        © 2022 - NowoDev
                    </p>
                    <span
                        class="inline-flex justify-center mt-4 space-x-5 sm:ml-auto sm:mt-0 sm:justify-start">
                        <a href="#" class="text-gray-400 hover:text-gray-500">
                            <span class="sr-only">GitHub</span>
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"
                                aria-hidden="true">
                                <path fill-rule="evenodd"
                                    d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
                                    clip-rule="evenodd"></path>
                            </svg>
                        </a>

                        <a href="#" class="text-gray-400 hover:text-gray-500">
                            <span class="sr-only">Twitter</span>
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"
                                aria-hidden="true">
                                <path
                                    d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84">
                                </path>
                            </svg>
                        </a>

                        <a href="#" class="text-gray-400 hover:text-gray-500">
                            <span class="sr-only">Instagram</span>
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"
                                aria-hidden="true">
                                <path fill-rule="evenodd"
                                    d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"
                                    clip-rule="evenodd"></path>
                            </svg>
                        </a>
                    </span>
                </div>
            </section>


        </main>
    </div>
</template>

<script>
export default {

}
</script>
