<script>
export default {
    data() {
        return {
            msg: 'BonusComponent'
        }
    }
}
</script>

<template>
    <h3>message from {{ msg }}</h3>
</template>

<style>
h3 {
    color: teal;
    background-color: paleturquoise;
    padding: 1rem;
    width: fit-content;
}
</style>
