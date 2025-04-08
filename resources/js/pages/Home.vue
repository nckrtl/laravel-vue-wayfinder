<script setup lang="ts">
import about from '@/routes/about';
import { Link } from '@inertiajs/vue3';
</script>

<template>
    <div class="flex flex-col gap-4">
        <Link :href="about()">
            <span>Link to About (with about())</span>
        </Link>
        <Link :href="about().url">
            <span>Link to About (with about().url)</span>
        </Link>
    </div>
</template>
