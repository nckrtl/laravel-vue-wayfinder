<script setup lang="ts">
import { Link } from '@inertiajs/vue3';
import home from '@routes/home';
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
