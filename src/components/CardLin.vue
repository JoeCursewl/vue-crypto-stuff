<script setup lang="ts">
name: 'CardLin';

props: {
  lintted_name: {
    type: String
    required: true
  }
  arroz: {
    type: Number
    required: true
  }
};

defineProps<{ arroz: string, lintted_name: string }>()

</script>


<template>
    <div>
        <h1>{{ arroz }}</h1>
    </div>

    <div>
        <h2>{{ lintted_name }}</h2>
    </div>
</template>

<style>
h1 {
    padding: 0;
    margin: 0;
    font-size: 20px;
}
</style>
