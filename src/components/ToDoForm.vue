<template>
  <div id="to-do-form">
      <input v-model="title">
      <input v-model="description">
      <!-- <input type="submit" value="create"/> -->
    <p>
      title is now {{title}}, description is {{description}}
    </p>
    <ToDoItem v-bind:title=title v-bind:description=description />
  </div>
</template>

<script>
import ToDoItem from "./ToDoItem"

export default {
  name: "ToDoForm",
  components:{ToDoItem},
  data: function() {
    return {
      title: "",
      description: ""
    };
  }
};
</script>