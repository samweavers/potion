<script>
  import '../app.css'
  import '../fonts.css'
  import Nav from '$lib/Nav.svelte'
  import Footer from '$lib/Footer.svelte'
</script>

<div class="min-h-screen flex flex-row gap-8">
  <Nav />

  <main class="grid gap-8 place-items-center container mx-auto p-4">
    <slot />
  </main>
</div>
