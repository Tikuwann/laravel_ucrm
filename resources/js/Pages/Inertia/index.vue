<script setup>
import { Link } from '@inertiajs/inertia-vue3';

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
});
</script>

<template>
    FUUUUUUUUUUCK YOU<br>
    <a href="/inertia-test">atag</a><br><br>
    <Link href="/inertia-test">Linktag</Link>
    <Link :href="route('inertia.index')">Named Route</Link>

</template>
