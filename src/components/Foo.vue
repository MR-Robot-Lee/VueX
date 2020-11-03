<template>
    <div>
        <h2>Foo 组件</h2>
        <p>{{ count }}</p>
        <button @click="increment">自增</button>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                count: 0
            }
        },
        methods: {
            increment() {
                this.count++;
            }
        }
    }
</script>

<style scoped>

</style>