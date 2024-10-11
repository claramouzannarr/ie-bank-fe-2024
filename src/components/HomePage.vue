<template>
  <div class="homepage">
    <div class="container">
      <h1 class="title">Welcome to IE University</h1>
      <p class="subtitle">Empowering the future of financial management</p>
      <p class="description">
        At IE Bank Corp, we provide a seamless and secure platform for managing
        your bank accounts with ease. Whether you're looking to create new
        accounts, view account balances, or update account details, we've got
        you covered. Click below to get started!
      </p>
      <router-link to="/accounts">
        <button type="button" class="btn btn-custom">Manage Accounts</button>
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
  background-color: #f0f4f8; /* Light background color */
  padding: 40px;
  border-radius: 15px;
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1); /* Adding a nice shadow */
}

.title {
  font-size: 3rem;
  font-weight: bold;
  color: #004080; /* A deep blue color */
}

.subtitle {
  font-size: 1.5rem;
  font-weight: 300;
  margin-bottom: 20px;
  color: #0073e6; /* Lighter blue for contrast */
}

.description {
  font-size: 1.1rem;
  margin-bottom: 30px;
  color: #333;
  line-height: 1.6;
}

.btn-custom {
  background-color: #28a745; /* Green button */
  color: white;
  padding: 10px 20px;
  font-size: 1.2rem;
  border-radius: 5px;
  border: none;
  transition: background-color 0.3s ease;
}

.btn-custom:hover {
  background-color: #218838; /* Darker green on hover */
}

.container {
  max-width: 800px;
  margin: 0 auto;
}

@media (max-width: 768px) {
  .title {
    font-size: 2.5rem;
  }

  .description {
    font-size: 1rem;
  }
}
</style>
