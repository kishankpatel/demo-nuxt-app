<template>
    <div>
        <h1>This is all users show page: {{$route.params.id}}</h1>
        <button @click="goBack">Back</button>
    </div>
</template>


<script>
export default {
    methods: {
        goBack () {
            this.$router.push('/all_users')
        }
    },
    validate (data) {
        return /^\d+$/.test(data.params.id)
    }
}
</script>
