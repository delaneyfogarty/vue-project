<template>
  <header>
    <h1>{{ title }}</h1>
    <ButtonItem text="Add Task" color="green" />
  </header>
</template>

<script>
import ButtonItem from "./Button";

export default {
  name: "HeaderItem",
  props: ["title"],
  components: {
    ButtonItem,
  },
};
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>
