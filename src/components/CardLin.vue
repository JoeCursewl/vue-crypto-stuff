<script setup lang="ts">

defineProps<{ lintted_name: string }>()

</script>


<template>
    <div>
        <h1>{{ lintted_name }}</h1>
    </div>
</template>

<style>

h1 {
    padding: 0;
    margin: 0;
    font-size: 20px;
}

</style>
