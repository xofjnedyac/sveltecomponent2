

<script>
	let name = 'world';
	import Phone from "./Phone.svelte"
</script>

<svelte:head>
<link rel="stylesheet" href="https://unpkg.com/tailwindcss@2.2.19/dist/tailwind.min.css"/>
</svelte:head>
<div class="flex flex-row space-x-4 p-4 w-full h-full justify-center bg-gray-400">
<Phone type="light"></Phone>
<Phone type="dark" ></Phone>
</div>



