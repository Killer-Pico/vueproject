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
.message-box{
    border: 2px solid #42b983;
    border-radius: 5px;
    padding: 15px;
    margin: 10px auto;
    width: 350px;
    text-align: center;
    font-size:18px;
    color:#333;
    background-color: #f0f9f5;
}
h2 {
    color: #2c3e50;
    font-size: 22px;
    margin-bottom: 10px;
}
</style>

