<template>
  <div :key="task.id" v-for="task in tasks">
    <h3>{{ task.text }}</h3>
  </div>
</template>

<script>
  export default {
    name: 'TasksComponent',
    props: {
      tasks: Array
    }
  }
</script>