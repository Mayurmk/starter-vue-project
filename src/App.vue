<script setup>
import { ref } from "vue";

let count = ref(0);

function increment() {
	count.value++;
}

</script>
<template>
	<button @click="increment"> Click me: {{ count }}</button>
</template>
