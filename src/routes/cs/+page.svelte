<script lang="ts">
    import { base } from '$app/paths';
    import Nav from '../../lib/components/Nav.svelte';
		let name="Svelte"
</script>
<html class="bg-black" lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Svelte</title>
  </head>
  <body class="mt-12 ml-6 mr-6 font-mono">
  <Nav {base}/>
    <main class="text-blue-500 mx-auto">
      <header>
      </header>
      <div class="pt-12 flex">
        <p>Hello World</p> 
			</div>
    </main>
  </body>
</html>
<p class="text-center">Made with Svelte and Tailwind CSS</p>