<template>
    <div class="bg-gray-900">
        <Header>
            <section class="h-full">
                <div
                    class="w-full lg:w-1/3 lg:fixed outline lg:rounded-r-full outline-sky-500 grid place-items-center bg-gray-700 lg:z-10 h-1/2 lg:h-full">
                    <img alt="Favour" class="w-72 md:w-4/5" src="./assets/images/casual.png" />
                </div>
            </section>
        </Header>

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
import Header from "./components/Header.vue";
import Navbar from "./components/NavbarOld.vue";

export default {
    name: "Home",
    components: { Header, About, Contact, Navbar, Footer },
};
</script>
