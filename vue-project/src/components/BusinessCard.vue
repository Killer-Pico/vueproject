<template>
    <div class="message-box">
        <h2>{{ name }}</h2>
        <p>{{ phone }}</p>
        <p>{{ email }}</p>
    </div>
</template>
<script>
export default {
    name: "BusinessCard",
    props: {
       phone: {
        type: String,
        required: true
       },
       email: {
        type: String,
        required: true
       }
    }
};
</script>
<style>

</style>

