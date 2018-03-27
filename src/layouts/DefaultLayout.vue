<template>
  <div>
    <header class="header">
      <a href="#">Logo</a>
    </header>
    <main class="main-content">
      <slot></slot>
    </main>
    <footer>
      <p>Copyright &copy; 2018</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'DefaultLayout'
}
</script>
