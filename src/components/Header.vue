<script setup lang="ts">
import Button from "./ui/Button.vue"
</script>


<template>

        <div class="relative">
            <img src="../assets/backgroundImage.jpg" class="bg-cover absolute top-0 left-0" />

            <div class="absolute w-4/12 left-44 top-56">
                <p class="text-4xl font-bold leading-snug">Plaisirs <span class="text-amber-500">italiens</span>  à chaque bouchée, seulement chez <span class="text-amber-500">Casanova</span> </p>
            <p class="mt-4 text-sm">
                Bienvenue chez Casanova, où l'Italie rencontre votre assiette. Découvrez nos spécialités italiennes préparées avec passion par notre chef. Plongez dans une expérience culinaire inoubliable. À Casanova, chaque plat raconte une histoire d'amour avec la cuisine italienne.            
            </p>

            <Button class="mt-4">Plus d'informations</Button>
            </div>
        </div>
</template>


<style>
</style>