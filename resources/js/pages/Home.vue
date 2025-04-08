<script setup lang="ts">
import { Link } from '@inertiajs/vue3';
import about from '@routes/about';
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
