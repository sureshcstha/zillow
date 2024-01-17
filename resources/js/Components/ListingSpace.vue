<template>
    <div>
        <span class="font-bold">{{ listing.beds }}</span> Beds <span class="text-gray-400">| </span>
        <span class="font-bold">{{ listing.baths }}</span> Baths <span class="text-gray-400">| </span>
        <span class="font-bold">{{ listing.area }}</span> Sq Ft
    </div>
</template>

<script setup>
defineProps({
    listing: Object,
})
</script>
