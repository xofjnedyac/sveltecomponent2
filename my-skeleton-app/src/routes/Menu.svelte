<script>
	import MenuItem from "./MenuItem.svelte"
	export let name = "Select Action"
	export let type = "light"
</script>
{#if type === "light"}
<div class="bg-gray-100 w-1/1 rounded-2xl ">
	<h1 class="text-gray-900 ml-6 pt-5 pb-3 text-xl font-bold ">{name}</h1>
	<MenuItem name="Download"></MenuItem>
	<MenuItem name="Save to Favorites"></MenuItem>
	<MenuItem name="Comment"></MenuItem>
	<MenuItem name="Share"></MenuItem>
	<MenuItem name="Report"></MenuItem>
	<div class="mt-3 border-t-2 border-solid border-gray-200"></div>
	<a href="/" class="block text-center mt-5 pb-5 text-md text-gray-500 hover:text-gray-600">Cancel</a>
</div>
{/if}

{#if type === "dark"}
<div class="bg-gray-800 w-1/1 rounded-2xl">
	<h1 class="text-gray-300 ml-6 pt-5 pb-3 text-xl font-bold">{name}</h1>
	<MenuItem name="Download" type="dark"></MenuItem>
	<MenuItem name="Save to Favorites" type="dark"></MenuItem>
	<MenuItem name="Comment" type="dark"></MenuItem>
	<MenuItem name="Share" type="dark"></MenuItem>
	<MenuItem name="Report" type="dark"></MenuItem>
	<div class="mt-3 border-t-2 border-solid border-gray-600"></div>
	<a href="/" class="block text-center mt-5 pb-5 text-md text-gray-500 hover:text-gray-400">Cancel</a>
</div>
{/if}