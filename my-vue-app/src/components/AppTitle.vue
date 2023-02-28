<template>
<div class="bg-red">
    {{ descrizione }}

</div>
</template>


<script>
export default {
    data() {
        return {
            descrizione: 'La mia prima app con Vite!'
        }
    }
}
</script>

<style>
.bg-red {
    background-color: red;
    color: white;
}
</style>