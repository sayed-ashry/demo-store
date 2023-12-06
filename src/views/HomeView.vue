<template>
  <header style="height: auto; background-color: #fff7d4; text-align: center; padding: 0.5rem">
    <h1>Home Page</h1>
  </header>
  <main style="height: 90vh">
    <ul>
      <li>
        <h1>Book</h1>
        <h2>20$</h2>
        <router-link to="/about">more details</router-link>
      </li>
      <li>
        <h1>Book</h1>
        <h2>20$</h2>
        <router-link to="/about">more details</router-link>
      </li>
      <li>
        <h1>Book</h1>
        <h2>20$</h2>
        <router-link to="/about">more details</router-link>
      </li>
    </ul>
  </main>

  <footer style="height: auto; background-color: #fff7d4; text-align: center; padding: 0.5rem">
    <h3>created with love</h3>
  </footer>
</template>

<script>
export default {
  name: 'HomeView'
}
</script>
