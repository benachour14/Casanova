<template>

    <div class=" fixed top-0 left-0 w-screen h-screen flex justify-center items-center z-50 bg-black-50">
        <div class=" bg-white top-1/2 left-1/2 shadow-md w-1/3 rounded-md">
            <div class=" bg-amber-500 p-8 rounded-md ">
                <div class="m text-white mb-4 font-bold flex flex-row justify-between items-center">
                    <h1 class="font-bold text-2xl">Casanova</h1>
                    <i class="fa-regular fa-circle-xmark text-3xl" @click="$emit('closeModal')"></i>
                </div>
                <div class="mb-4">
                    <p class="text-emerald-800 ">Contactez-nous</p>
                    <p class="text-white">+212 61 23 45 67 89</p>
                </div>
                <div>
                    <p class="text-emerald-800">Adresse</p>
                    <p class="text-white">Adresse du restaurant</p>
                </div>
            </div>
            <div class="p-8">
                    <div class="text-gray-400 flex flex-row justify-between mb-1">
                        <p class="font-bold">Lundi</p>
                        <p>12:00 - 02:00</p>
                    </div>
                    <hr />

                    <div class="text-gray-400 flex flex-row justify-between mt-2 mb-1">
                        <p class="font-bold">Mardi</p>
                        <p>12:00 - 02:00</p>
                    </div>
                    <hr />

                    <div class="text-gray-400 flex flex-row justify-between mt-2 mb-1">
                        <p class="font-bold">Mercredi</p>
                        <p>12:00 - 02:00</p>
                    </div>
                    <hr />

                    <div class="text-gray-400 flex flex-row justify-between mt-2 mb-1">
                        <p class="font-bold">Jeudi</p>
                        <p>12:00 - 02:00</p>
                    </div>
                    <hr />

                    <div class="text-gray-400 flex flex-row justify-between mt-2 mb-1">
                        <p class="font-bold">Vendredi</p>
                        <p>12:00 - 02:00</p>
                    </div>
                    <hr />

                    <div class="text-gray-400 flex flex-row justify-between mt-2 mb-1">
                        <p class="font-bold">Samedi</p>
                        <p>12:00 - 02:00</p>
                    </div>
                    <hr />

                    <div class="text-gray-400 flex flex-row justify-between mt-2 mb-1">
                        <p class="font-bold">Dimanche</p>
                        <p>12:00 - 02:00</p>
                    </div>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">
</script>

<style>
</style>