
<template>
    <div id="app">
        <button @click="count++">
            count is: {{ count }}
        </button>
    </div>
</template>

<script setup>
    import { ref } from 'vue'
    import 

    const count = ref(0)
</script>