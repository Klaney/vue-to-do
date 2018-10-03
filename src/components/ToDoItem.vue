<template>
<div id="to-do-item">
  <p>
    {{title}} and {{description}}
  </p>
  </div>
</template>

<script>
export default {
  name: 'ToDoFile',
  props: {
    title: String,
    description: String
  }
}
</script>