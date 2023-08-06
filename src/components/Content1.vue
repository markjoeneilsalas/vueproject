<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
    <section class="content1-section">
        <b-container>
            <b-row>
                <b-col></b-col>
                <b-col>
                </b-col>
            </b-row>
        </b-container>
    </section>
</template>

<style scoped>
    .content1-section {
        background-image: url('../assets/Hero2.png');
        width: auto;
        height: 80vh;
        background-repeat: no-repeat;
        background-size: cover;
    }
</style>
