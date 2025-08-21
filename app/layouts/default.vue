<template>
    <div>
        <div class="container mx-auto pt-2">
            <ul class="flex justify-start gap-6">
                <li class="text-xl">
                    <NuxtLink to="/" active-class="text-violet-600">Home</NuxtLink>
                </li>
                <li class="text-xl">
                    <NuxtLink to="/privacy" active-class="text-violet-600">Privacy</NuxtLink>
                </li>
            </ul>
            <slot />
        </div>
    </div>
</template>
<script setup>
</script>