<script setup>
import Header from "@/Components/Frontend/Header.vue";
</script>
<template>
    <!-- Header -->
    <Header />
    <div class="bg-slate-200 dark:bg-slate-900">
        <main class="min-h-screen">
            <slot />
        </main>
        <!--Footer-->
    </div>
</template>
