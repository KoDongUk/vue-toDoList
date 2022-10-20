<template>
  <div>
    <Header />
    <ToDoInput />
    <ToDoList />
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header/Header.vue";
import Footer from "../components/Footer/Footer.vue";
import ToDoInput from "../components/ToDos/ToDoInput.vue";
import ToDoList from "../components/ToDos/ToDoList.vue";

export default {
  name: "MainView",
  components: {
    Header: Header,
    Footer: Footer,
    ToDoInput: ToDoInput,
    ToDoList: ToDoList
  }
};
</script>

<style></style>
