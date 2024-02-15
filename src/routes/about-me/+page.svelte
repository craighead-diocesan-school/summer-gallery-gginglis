<script>
    import Header from "$lib/Header.svelte";
    import Footer from "$lib/Footer.svelte";
    import Nav from "$lib/Nav.svelte";
</script>

<Header title="Summer Gallery" subtitle="Images from summer" />

<Nav />

<main class="content-section">
    <img src="/amberandg.JPG" alt="" />
    <img src="/avaandg.JPG" alt="" />
    <img src="/bffs.JPG" alt="" />
    <img src="/sc23.JPG" alt="" />
    <img src="/cuesyrupy.JPG" alt="" />
</main>

<Footer />

<style>
    img {
        height: 250px;
        margin: 2% 0.2%;
    }
</style>
