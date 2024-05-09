<template>
    <h1>Counter</h1>
    <button @click="decrement">-</button>
    <span>{{ count }}</span>
    <button @click="increment">+</button>
</template>

<script>
export default {
    name: 'Counter',
    data: () => ({
        count: 0
    }),
    methods: {
        increment() {
            this.count++
        },

        decrement() {
            this.count--
        }
    }
}
</script>