<script>
  export let title = "Main Heading";
  export let subtitle = "Secondary Heading";
</script>

<!-- svelte-ignore missing-declaration -->
<!-- <Header title="Summer Gallery" subtitle="Images from summer" /> -->

<header class="hero is-small is-danger">
  <div class="hero-body">
    <h1 class="title">{title}</h1>
    <h2 class="subtitle">{subtitle}</h2>
  </div>
</header>
