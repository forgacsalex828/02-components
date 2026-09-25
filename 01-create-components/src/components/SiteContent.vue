<template>
  <main class="site-content">
    <section class="hero">
      <h1>Welcome to the Component Playground</h1>
      <p>Choose a component from the navigation to explore.</p>
    </section>
    <section class="examples">
      <slot />
    </section>
  </main>
</template>

<script>
export default {
  name: 'SiteContent',
}
</script>

<style scoped>
.site-content {
  padding: 2rem;
}
.hero {
  margin-bottom: 1.5rem;
}
</style>
