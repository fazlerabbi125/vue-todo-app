<template>
  <TaskList />
</template>

<script>
// @ is an alias to /src
import TaskList from "@/components/TaskList.vue";

export default {
  name: "Home",
  components: {
    TaskList,
  },
};
</script>
