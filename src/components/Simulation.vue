<template>
    <body class="mt-0 pt-0">
        <Header/>
        <div class="mainContainer h-auto my-3 mx-5 lg:mx-16 p-0 overflow-hidden xl:mx-44">
            <div class="sim-grid-container md:grid p-0 m-0">
                <div class="sim-grid-item text-left m-0 p-0 text-white text-base leading-none xl:leading-none xl:text-xl">
                <p class="text-5xl font-bold mb-5 md:mb-0 xl:text-7xl xl:title">Rekomendasi build untuk anda.</p>
                <p class="subtitle mb-5 md:mb-0">Rekomendasi pilihan dari kami untuk PC idaman anda.</p>
                </div>
                <div class="vertical-allign-center grid justify-center items-center">
                    <div class="sim-card-container grid">
                        <BuildCard/>
                        <BuildCard/>          
                    </div>
                    <button class="sim-rekcard-btn cursor-pointer text-black bg-green1 text-xl py-2 px-8 inline-block text-center my-2 mx-10 sm:mx-30 md:mx-24 lg:mx-36 xl:mx-36">Explore Builds</button> 
                </div>
            </div>

            <div class="line w-full h-1 bg-green1 my-3 overflow-hidden"> </div>

            <p class="text-5xl font-bold mb-5 md:mb-0 xl:text-7xl title">Simulasi</p>
            <SimulationContent/>
        </div>
        <Footer/>
    </body>
</template>

<script setup>
import HelloWorld from './HelloWorld.vue'
import Header from './Header.vue'
import BuildCard from './BuildCard.vue'
import SimulationContent from './SimulationContent.vue'
import Footer from './Footer.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#Simulation {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #00B570; */
}
.sim-grid-container {
    grid-template-columns: 40% 60%;
}
.sim-card-container {
    grid-template-columns: 50% 50%;
}
</style>
