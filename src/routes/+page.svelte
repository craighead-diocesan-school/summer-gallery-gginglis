<script>
  import Header from "$lib/Header.svelte";
  import Footer from "$lib/Footer.svelte";
  import Nav from "$lib/Nav.svelte";
</script>

<Header title="Summer Gallery" subtitle="Images from summer" />

<Nav />
<main>
  <h2>SvelteKit</h2>
  <div class="columns">
    <div class="column">
      <p>
        Welcome to coding with SvelteKit, a modern JavaScript framework that
        makes it easy to code great apps.
      </p>
    </div>
    <div class="column">
      <h2>I'm G</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto obcaecati
        voluptates, esse inventore quisquam illo architecto. Voluptatum
        obcaecati dolorem vero tempore voluptatem voluptas, vel hic reiciendis
        praesentium quis possimus pariatur!
      </p>
    </div>
    <div class="column">
      <h2>This is Digi</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed est nemo id
        sapiente voluptas possimus aut a fugit deleniti iure illum assumenda
        tempora, unde cumque exercitationem, tenetur eum, quo eveniet.
      </p>
    </div>
  </div>
</main>

<Footer />
