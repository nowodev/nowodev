<template>
    <button
        class="text-xs px-6 py-2 rounded ring-2 ring-gray-800 hover:bg-gray-800 hover:scale-110 transition-all focus:bg-gray-800 focus:ring focus:ring-gray-800">
        <slot></slot>
    </button>
</template>

<script>
export default {
    name: "Button",
};
</script>