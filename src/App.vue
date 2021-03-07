<template>
  <section
    id="app"
    class="todoapp"
  >
    <header class="header">
      <h1>todos</h1>
      <input
        class="new-todo"
        placeholder="What needs to be done?"
        autocomplete="off"
        autofocus
      >
    </header>
    <section class="main">
      <input
        id="toggle-all"
        class="toggle-all"
        type="checkbox"
      >
      <label for="toggle-all">Mark all as complete</label>
      <ul class="todo-list">
        <li
        >
          <div class="view">
            <input class="toggle" type="checkbox">
            <label >fsdfsd</label>
            <button class="destroy">fsdfs</button>
          </div>
          <input
            class="edit"
            type="text"
            >
        </li>
      </ul>
    </section>
    <footer
      class="footer"
      v-show="count"
    >
      <span class="todo-count">
        <strong>11</strong> items left
      </span>
      <ul class="filters">
        <li><a href="#/all">All</a></li>
        <li><a href="#/active">Active</a></li>
        <li><a href="#/completed">Completed</a></li>
      </ul>
      <button class="clear-completed">
        Clear completed
      </button>
    </footer>
  </section>
  <footer class="info">
    <p>Double-click to edit a todo</p>
    <!-- Remove the below line ↓ -->
    <p>Template by <a href="http://sindresorhus.com">Sindre Sorhus</a></p>
    <!-- Change this out with your name and url ↓ -->
    <p>Created by <a >Tommy·Yang</a></p>
    <p>Part of <a href="http://todomvc.com" target="_blank">TodoMVC</a></p>
  </footer>
</template>

<script>
import "./assets/index.css";
export default {

}
</script>

<style>
</style>
