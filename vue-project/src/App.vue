<template>
  <div>
  <HeaderComponent title="Hello title"/>
  </div>
  <MessageComponent title="Привіт, Vue!" message="Я вмію створювати компоненти із пропсами!"/>
  <MessageComponent title="Що далі?" message="Тепер я можу передавати різні дані в компоненти!"/>
  <BusinessCardComponent phone="+3802314576" email="example@gmail.com"/>
</template>

<script>
import BusinessCard from './components/BusinessCard.vue';
import HeaderComponent from './components/Header.vue';
import MessageComponent from './components/MessageComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MessageComponent,
    BusinessCardComponent   
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
