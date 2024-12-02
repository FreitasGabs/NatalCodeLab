<script setup>
import logo from "../assets/logo.svg"
import loja from "../assets/loja.svg"

</script>

<template>
    <section>
        <div>
            <img :src="logo" alt="">
            <h1>Uma plataforma de doação para espalhar alegria</h1>
            <p>Nessas festas de fim de ano mande um presente para a pessoa amada e compartilhe a alegria do Natal.</p>
            <button>Fazer uma doação</button>
        </div>

        <img :src="loja" alt="">
    </section>

</template>

<style scoped lang="scss">

</style>