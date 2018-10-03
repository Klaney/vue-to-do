<template>
  <div id="to-do-form">
      <input v-model="title">
      <input v-model="description">
      <!-- <input type="submit" value="create"/> -->
    <p>
      title is now {{title}}, description is {{description}}
    </p>
  </div>
</template>

<script>
export default {
  name: "ToDoForm",
  data: function() {
    return {
      title: "",
      description: ""
    };
  }
};
</script>