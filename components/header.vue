<template>
  <div class="header">
    <ul>
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/users">Users</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/all_users">All Users</nuxt-link>
      </li>
    </ul>
  </div>
</template>

<style scoped >
  .header ul li {
    list-style-type: none;
    display: inline-block;
    padding: 3px;
  }
  .header {
    background: rgb(216, 216, 216);
    padding: 10px;
  }
</style>
