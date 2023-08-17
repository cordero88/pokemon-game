<script lang = "ts">
      import Pokemonoptions from '@/components/PokemonOptions.vue';
      import PokemonPicture from '@/components/PokemonPicture.vue';

      export default {
      components:{ Pokemonoptions,PokemonPicture}
      }

</script>


<template>

    <h1>¿Quien es este pokémon?</h1>
    <PokemonPicture :pokemonId="93" :showPokemon="false"/>
    <Pokemonoptions/>


</template>


<style>



</style>