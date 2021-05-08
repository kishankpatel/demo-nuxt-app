<template>
    <div class="text-center">
        <h1>This is users page</h1>
        <br>
        <input type="text" v-model="userId" />
        <button @click="showUser">Show user</button>
        <nuxt-child />
    </div>
</template>

<script>
export default {
    data () {
        return {
            userId: ''
        }
    },
    methods: {
        showUser () {
            this.$router.push('/all_users/'+ this.userId)
        }
    },
    layout: 'layout_users'
}
</script>

<style scoped>
.text-center {
    text-align: center;
}
</style>
