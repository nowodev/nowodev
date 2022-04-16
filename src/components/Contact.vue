<template>
    <section id="contact" class="flex relative w-full min-h-screen">
        <div class="container items-center px-8 mx-auto text-white">
            <h1 class="text-6xl font-bold text-center text-white">Contact</h1>

            <h3 class="my-8 text-2xl font-semibold text-center">Fill the form</h3>

            <div class="grid grid-cols-1 gap-3 mx-auto md:grid-cols-2 lg:max-w-3xl">
                <div class="flex flex-col space-y-3">
                    <label>Name</label>
                    <input class="px-3 py-2 text-black rounded-lg" type="text" />
                </div>

                <div class="flex flex-col space-y-3">
                    <label>Email</label>
                    <input class="px-3 py-2 text-black rounded-lg" type="text" />
                </div>

                <div class="flex flex-col space-y-3">
                    <label>Message</label>
                    <textarea class="px-3 py-2 text-black rounded-lg" type="text"></textarea>
                </div>
            </div>

            <button class="flex px-6 py-3 mx-auto mt-4 font-bold bg-gray-400 rounded-lg">Submit</button>
        </div>
    </section>
</template>

<script>
    export default {
        name: "Contact"
    }
</script>