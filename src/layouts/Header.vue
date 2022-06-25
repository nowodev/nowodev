<template>
    <div class="min-hscreen hscreen">
        <header class="text-gray-400 bg-gray-900 body-font z-20 w-full top-0 fixed">
            <!-- class="text-gray-400 bg-gray-900 body-font border-b border-gray-400 z-20 w-full top-0 fixed"> -->
            <div class="container mx-auto flex flex-row p-5 md:items-center">
                <div class="flex w-full md:w-fit">
                    <a class="flex title-font font-medium items-center text-white">
                        <svg xmlns="http://www.w3.org/2000/svg"
                            class="w-10 h-10 text-white p-2 bg-pink-500 rounded-full"
                            viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd"
                                d="M12.395 2.553a1 1 0 00-1.45-.385c-.345.23-.614.558-.822.88-.214.33-.403.713-.57 1.116-.334.804-.614 1.768-.84 2.734a31.365 31.365 0 00-.613 3.58 2.64 2.64 0 01-.945-1.067c-.328-.68-.398-1.534-.398-2.654A1 1 0 005.05 6.05 6.981 6.981 0 003 11a7 7 0 1011.95-4.95c-.592-.591-.98-.985-1.348-1.467-.363-.476-.724-1.063-1.207-2.03zM12.12 15.12A3 3 0 017 13s.879.5 2.5.5c0-1 .5-4 1.25-4.5.5 1 .786 1.293 1.371 1.879A2.99 2.99 0 0113 13a2.99 2.99 0 01-.879 2.121z"
                                clip-rule="evenodd" />
                        </svg>
                        <span class="ml-3 text-xl font-mono">nowodev</span>
                    </a>

                    <button
                        class="text-gray-500 w-10 h-10 p-2 relative focus:outline-none ml-auto md:hidden"
                        @click="open = !open">
                        <span class="sr-only">Open main menu</span>
                        <span
                            class="block w-5 absolute left-1/2 top-1/2 transform -translate-x-1/2 -translate-y-1/2">
                            <span aria-hidden="true"
                                class="block absolute h-0.5 w-5 bg-current transform transition duration-500 ease-in-out"
                                :class="{ 'rotate-45': open, ' -translate-y-1.5': !open }"></span>
                            <span aria-hidden="true"
                                class="block absolute h-0.5 w-5 bg-current transform transition duration-500 ease-in-out"
                                :class="{ 'opacity-0': open }"></span>
                            <span aria-hidden="true"
                                class="block absolute h-0.5 w-5 bg-current transform transition duration-500 ease-in-out"
                                :class="{ '-rotate-45': open, ' translate-y-1.5': !open }"></span>
                        </span>
                    </button>
                </div>

                <nav class="hidden ml-4 md:flex items-center w-full gap-x-12">
                    <div class="flex space-x-5 justify-end w-full font-black font-mono">
                        <a class="hover:text-white cursor-pointer">About</a>
                        <a class="hover:text-white cursor-pointer">Experience</a>
                        <a class="hover:text-white cursor-pointer">Works</a>
                        <a class="hover:text-white cursor-pointer">Contact</a>
                    </div>

                    <div class="flex space-x-3 ml-auto">
                        <Github />
                        <Twitter />
                    </div>
                </nav>
            </div>
        </header>

        <div class="absolute flex top-0 h-screen z-10">
            <div class="transition-all duration-700 overflow-hidden bg-gray-700 flex items-center justify-center"
                :class="[open ? 'max-w-lg' : 'max-w-0']">

                <nav
                    class="md:hidden md:ml-auto flex flex-col space-y-4 w-screen text-white items-center text-base justify-center font-black font-mono">
                    <a>About</a>
                    <a>Experience</a>
                    <a>Works</a>
                    <a>Contact</a>

                    <div class="flex w-full justify-center gap-x-5">
                        <Github size="w-7 h-7" />
                        <Twitter size="w-7 h-7" />
                    </div>
                </nav>
            </div>
        </div>
    </div>
</template>

<script>
import Twitter from '../components/social-links/Twitter.vue'
import Github from '../components/social-links/Github.vue';
export default {
    name: "Header",

    data() {
        return {
            open: false,
        };
    },

    components: { Twitter, Github }
}
</script>