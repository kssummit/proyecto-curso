<template>
    <div>
        {{display}}
        <button @click="handleClick()">7</button>
    </div>
</template>

<script>
    export default {
        name: 'calculatorVue',
        data() {
            return {
                display: 0
            }
        },
        methods: {
            handleClick: () =>{
                this.display = 7;
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>