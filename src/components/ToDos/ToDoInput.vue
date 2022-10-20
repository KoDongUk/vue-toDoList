<template>
  <div id="ToDo_Input">
    <input type="text" v-model="newToDoItem" />
    <button v-on:click="addToDo">add</button>
  </div>
</template>

<script>
export default {
  name: "ToDoInput",
  data() {
    return {
      newToDoItem: ""
    };
  },
  methods: {
    addToDo() {
      console.log(this.newToDoItem);
      localStorage.setItem(this.newToDoItem, this.newToDoItem);
      this.newToDoItem = "";
    }
  }
};
</script>

<style scoped>
#ToDo_Input {
  text-align: center;
}
</style>
