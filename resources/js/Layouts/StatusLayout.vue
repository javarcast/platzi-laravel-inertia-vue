<template>
    <div class="bg-blue-500 text-white text-sm font-bold p-4">
        <p> {{status}}</p>
    </div>
</template>

<script>
export default {
    name:'StatusLayout',
    props:{
        status,
    }
}
</script>

<style>

</style>