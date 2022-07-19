<template>
<Navbar/>
<Form/>
<Card/>
<Card/>
</template>

<script>
import Navbar from "./components/FriendNav.vue";
import Form from "./components/FriendForm.vue";
import Card from "./components/FriendCard.vue";
export default {
  components: {
    Navbar,
    Form,
    Card,
  }
}
</script>

<style>
#app {
  width: 50%;
  padding: 15px;
  margin: auto;
  border: 3px solid rgb(190, 6, 113);
}

#app .card{
  margin-top: 15px;
}
</style>
