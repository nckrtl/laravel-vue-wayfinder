<script setup lang="ts">
import home from '@/routes/home';
import { Link } from '@inertiajs/vue3';
</script>

<template>
    <div class="flex flex-col gap-4">
        <Link :href="home()">
            <span>Link to Home (with home())</span>
        </Link>
        <Link :href="home().url">
            <span>Link to Home (with home().url)</span>
        </Link>
    </div>
</template>
