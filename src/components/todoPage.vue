<template>
  <List />
  <Add />
</template>

<script>
import List from './todolist.vue';
import Add from './addtodo.vue';

export default {
  name : 'Todo',
  components : {
    List,
    Add
  }
}
</script>

<style>
</style>
