<template>
  <div class="container">
    <header>
      <img src="~/assets/esn-logo.png" alt="ESN Växjö Logo" />
      <h1>Welcome to ESN Växjö</h1>
    </header>

    <section>
      <h2>About Us</h2>
      <p>
        ESN Växjö is a non-profit student organization dedicated to supporting international students in Växjö. 
        We organize events, provide guidance, and strive to enhance the international student experience.
      </p>
    </section>

    <section>
      <h2>Events</h2>
      <p>Stay tuned for our upcoming events and gatherings!</p>
    </section>

    <footer>
      <p>© 2023 ESN Växjö. All rights reserved.</p>
    </footer>
  </div>
</template>

<script>
export default {
  head: {
    title: 'ESN Växjö - Home'
  }
}
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

header, section, footer {
  margin-bottom: 20px;
}

header img {
  max-width: 200px;
}
</style>
