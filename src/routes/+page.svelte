<script lang="ts">
    import { base } from '$app/paths';
		let name="Svelte"
</script>
<html class="bg-black" lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>UIL Computer Science</title>
  </head>
  <body class="font-mono">
    <main class="text-blue-500 mx-auto">
      <header>
        <h1 class="text-lg text-center">UIL Computer Science</h1>
      </header>
      <div class="flex">
        <div class="border-solid border-green-500 basis-1/5 pl-12">
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
    </main>
  </body>
</html>
<h1 class="bg-green-500 p-4 m-4 rounded hover:bg-blue-500">Hello {name.toUpperCase()}!</h1>
<p class="text-center">Made with Svelte and Tailwind CSS</p><nav>
	<a class="text-blue-500 p-12" href="{base}/cs">cs</a>
</nav>