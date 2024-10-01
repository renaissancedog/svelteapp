<script lang="ts">
    import { base } from '$app/paths';
    import Nav from './Nav.svelte';
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
        <h1 class="pt-12 text-2xl text-center">UIL Computer Science</h1>
      </header>
      <div class="pt-12 mr-4 flex">
        <div class="border-solid border-green-500 basis-1/5">
          <p class="leading-6">Mr. Hall</p>
          <p>dhall2@neisd.net</p>
          <p>IND321</p>
          <p>Thursdays 4:30 to 5:30 (for now)</p>
        </div>
        <div class="basis-4/5 pr-12">
          <p>We do multiple-choice computer science questions in Java and code solutions to problems.</p>
          <p>Besides UIL, we also prepare students for USACO and other competitive programming contests.</p>
          <p> For more, see <a href="https://www.uiltexas.org/academics/stem/computer-science" target="_blank">Computer Science.</a></p>
        </div>
			</div>
			<h1 class="mt-12 text-blue-200 bg-green-700 p-4 rounded hover:bg-blue-500">Hello {name.toUpperCase()}!</h1>
    </main>
  </body>
</html>
<p class="text-center">Made with Svelte and Tailwind CSS</p>