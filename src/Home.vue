<template>
    <div class="bg-gray-900">
        <Header />
        <!-- <section class="h-full w-full flex relative">
                <div
                    class="w-full lg:w-1/3 lgfixed outline lgrounded-r-full outline-sky-500 grid place-items-center lg:z-10 h-1/2 lg:h-full">
                    <img alt="Favour" class="w-72 lg:w-4/5 lg:mr-10"
                        src="./assets/images/casual.png" />
                </div>
            </section> -->

        <main class="h-screen flex">

            <!-- Fixed sidebar -->
            <aside
                class="bg-gray-600 w-1/3 justify-center h-screen flex text-center place-items-center">
                <!-- Sidebar content -->
                <div class="flex flex-col text-white px-4 gap-y-4">
                    <h1 class="text-6xl">OKUNOWO FAVOUR</h1>
                    <h2 class="text-lg">Fullstack Web Developer</h2>

                    <div class="space-x-4">
                        <Button>Get in touch</Button>
                        <Button>Resume</Button>
                    </div>

                    <div class="flex gap-x-2 justify-center">
                        <Github />
                        <Twitter />
                        <Github />
                        <Twitter />
                        <Github />
                        <Twitter />
                    </div>
                </div>
                <!-- <img alt="Favour" class="w-72 lg:w-4/5 lg:mr-10" src="./assets/images/casual.png" /> -->
            </aside>

            <!-- Scroll wrapper -->
            <section class="flex-1 grid overflow-hidden place-content-center z-50">
                <!-- Scrollable container -->
                <div class="flex-1 overflow-y-scroll text-white">
                    <!-- Your content -->
                    <h1></h1>
                </div>
            </section>
        </main>


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
        <!-- <Footer /> -->
    </div>
</template>

<script>
import About from "./components/About.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";
import Header from "./layouts/Header.vue";
import Navbar from "./components/NavbarOld.vue";
import Button from "./components/Button.vue";
import Github from "./components/social-links/Github.vue";
import Twitter from "./components/social-links/Twitter.vue";

export default {
    name: "Home",
    components: { Header, About, Contact, Navbar, Footer, Button, Github, Twitter },
};
</script>
