<template>
    <div>
        <h1>{{ title }}</h1>
        <p> {{ name }}</p>
        <button @click="updateName">Change Name</button>
    </div>
</template>
<script>
export default {
    props: {
        title: {
            type: String,
            required: true
        }
    },

    data() {
        return {
            name: 'Han Jaechul'
        }
    },

    methods: {
        updateName() {
            this.name = 'Han Jaechul update';
        }
    }
}
</script>
<style scoped>

</style>