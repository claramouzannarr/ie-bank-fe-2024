<template>
  <div class="homepage">
    <div class="container">
      <h1>Welcome to IE Bank Corp</h1>
      <p>This is the homepage of the bank account management system.</p>
      <p>Click below to manage accounts:</p>
      <router-link to="/accounts">
        <button type="button" class="btn btn-primary">Manage Accounts</button>
      </router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "Homepage"
};
</script>

<style scoped>
.homepage {
  text-align: center;
  margin-top: 50px;
}
</style>
