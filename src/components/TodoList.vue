<template>
    <div class="todo-list">
        <todo-list-item></todo-list-item>
    </div>
</template>
<script>
import TodoListItem from './TodoListItem';
export default {
    components: {
        TodoListItem
    }
};
</script>
<style>
.todo-list {
    display: grid;
    row-gap: 14px;
}
</style>