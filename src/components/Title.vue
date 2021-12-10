<template>
    <div>
        <!-- parte che conterrà tutta la mia parte hmtl -->
        <h1>La mia prima app con Vue CLI!</h1>
    </div>
</template>

<script>
    //logica del componente: come informazione minima devo creare l'export del mio oggetto
    export default {
        name: "Title"
    }
</script>

<style scoped>
/* se scoped non devo preoccuparmi di eventuali sovrascrizioni */
h1 {
    color: #3fb883;
}
</style>
