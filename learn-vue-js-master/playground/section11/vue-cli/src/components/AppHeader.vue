<template>
    <header>
        <h1>{{ propsdata }}</h1>
        <button v-on:click="sendEvent">send</button>
    </header>
</template>

<script>
export default {
    propsdata: ['propsdata'],
    methods: {
        sendEvent: function(){
            this.$emit('renew')
        }
    }
}
</script>

<style>

</style>