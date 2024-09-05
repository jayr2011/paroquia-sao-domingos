<script setup>
    const redirectToLink = (link) => {
        window.open(link, '_blank');
    }
    const linkToInstagram = () => {
        redirectToLink('https://www.instagram.com/saodomingos_pascom/');
    }
    const linkToFacebook = () => {
        redirectToLink('https://www.facebook.com');
    }
</script>

<template>
    <div class="call-container flex flex-col">
        <div class="call-data flex flex-col items-center">
        <h1 class="text-4xl mb-5">Nos siga em nossas redes socias e veja nossas atualizações.</h1>
       <div class="instagram-container">
        <button @click="linkToInstagram()" type="button" class="text-white bg-gradient-to-r from-purple-500 to-pink-500 hover:bg-gradient-to-l focus:ring-4 focus:outline-none focus:ring-purple-200 dark:focus:ring-purple-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2 flex flex-row items-start">
                <p class="mr-5">Nosso Instagram</p>
                <i>
                    <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
                    <path fill="currentColor" fill-rule="evenodd" d="M3 8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v8a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5V8Zm5-3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V8a3 3 0 0 0-3-3H8Zm7.597 2.214a1 1 0 0 1 1-1h.01a1 1 0 1 1 0 2h-.01a1 1 0 0 1-1-1ZM12 9a3 3 0 1 0 0 6 3 3 0 0 0 0-6Zm-5 3a5 5 0 1 1 10 0 5 5 0 0 1-10 0Z" clip-rule="evenodd"/>
                    </svg>
                </i>
        </button>
       </div>

       <div class="face-container">
        <button @click="linkToFacebook()" type="button" class="text-white bg-gradient-to-r from-cyan-500 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-cyan-300 dark:focus:ring-cyan-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2 flex flex-row items-start">
            <p class="mr-5">Nosso Facebook</p>
            <i>
                <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
                     <path fill-rule="evenodd" d="M13.135 6H15V3h-1.865a4.147 4.147 0 0 0-4.142 4.142V9H7v3h2v9.938h3V12h2.021l.592-3H12V6.591A.6.6 0 0 1 12.592 6h.543Z" clip-rule="evenodd"/>
                </svg>
            </i>
        </button>
       </div>
    </div>
    </div>
</template>

<style scoped>
    .call-data{
        padding-top: 100px;
        height: 100vh;
        background-color: rgb(239, 234, 227);
    }
</style>