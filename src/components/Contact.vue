<template>
    <section id="contact" class="flex relative w-full min-h-screen">
        <div class="container items-center px-8 mx-auto text-white">
            <h1 class="text-6xl font-bold text-center text-white">Contact</h1>

            <div class="flex flex-col gap-3 p-3 mx-auto mt-8 rounded-md lg:p-6 outline lg:max-w-xl">
                <div class="flex flex-col space-y-3">
                    <label class="font-bold">Name</label>
                    <input class="px-3 py-2 text-black rounded-lg" type="text" />
                </div>

                <div class="flex flex-col space-y-3">
                    <label class="font-bold">Email</label>
                    <input class="px-3 py-2 text-black rounded-lg" type="text" />
                </div>

                <div class="flex flex-col space-y-3">
                    <label class="font-bold">Message</label>
                    <textarea class="px-3 py-2 text-black rounded-lg" rows="5" type="text"></textarea>
                </div>

                <button class="px-6 py-2 mx-auto mt-4 font-bold text-black bg-white rounded-lg transition hover:-translate-y-1">
                    Submit
                </button>
            </div>

        </div>
    </section>
</template>

<script>
    export default {
        name: "Contact"
    }
</script>