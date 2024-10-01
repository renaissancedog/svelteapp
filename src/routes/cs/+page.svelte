<script lang="ts">
    import { base } from '$app/paths';
    import Nav from '../Nav.svelte';
		let name="Svelte"
</script>
<html class="bg-black" lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Svelte 2</title>
  </head>
  <body class="mt-12 ml-12 font-mono">
  <Nav {base}/>
    <main class="text-blue-500 mx-auto">
      <div class="pt-12 flex">
        <p>Hello World</p> 
			</div>
    </main>
  <p class="text-center">Made with Svelte and Tailwind CSS</p>
  </body>
</html>