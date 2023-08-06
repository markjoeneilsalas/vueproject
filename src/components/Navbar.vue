<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
    <section class="header-section">
        
    <b-container>
        <nav class="navbar-section d-flex justify-content-between align-items-center p-4 ">
            <div class="web-logo">
                <p class="fw-bold">I-Buyhay</p>
            </div>
            <ul class="navbar-ul d-flex gap-5">
                <li>Home</li>
                <li>About</li>
                <li>Contact</li>
            </ul>
        </nav>
    </b-container>
        <div class="btn-div">
            <p class="p-hero">"No investment on earth is so safe, so sure,
                <br>so certain to enrich its owner as undeveloped realty."
            </p>
            <button class="btn-hero">INQUIRE NOW</button>
        </div>
    </section>
</template>

<style scoped>
    .navbar-section {
        color: white;
        padding-right: 3rem;
        padding-left: 3rem;
    }
    .header-section {
        background-image: url('../assets/Hero.png');
        width: auto;
        height: 80vh;
        background-repeat: no-repeat;
        background-size: cover;
    }
    
    .navbar-ul {
        list-style: none;
        padding-right: 3rem;

    }

    .web-logo {
        font-size: 20px;
        padding-left: 3rem;
    }

    .btn-hero {
        width: 250px;
        height: 50px;
        left: 147px;
        font-size: 25px;
        font-weight: 700;
        top: 583px;
        border: 2px solid #ffffff;
        border-radius: 50px;
        background-color: #77604F;
        color: white;
    }

    .btn-hero:hover {
        background-color: white;
        color: black;
    }

    .p-hero {
        padding-bottom: 1rem;
    }

    @media only screen and (max-width: 1920px) {
        .header-section {
        background-image: url('../assets/Hero.png');
        width: auto;
        height: 90vh;
        background-repeat: no-repeat;
        background-size: cover;
    }

    .btn-div {
        padding-left: 15rem;
        padding-top: 30rem;
        color: white;
    }


    }

    @media only screen and (max-width: 1826px) {
    .btn-div {
        padding-left: 13rem;
        padding-top: 30rem;
        color: white;
    }
    }

    @media only screen and (max-width: 1489px) {
    .btn-div {
        padding-left: 11rem;
        padding-top: 25rem;
        color: white;
    }
    }

    @media only screen and (max-width: 600px) {
    .btn-div {
        padding-left: 11rem;
        padding-top: 25rem;
        color: white;
    }
    }

    

</style>
