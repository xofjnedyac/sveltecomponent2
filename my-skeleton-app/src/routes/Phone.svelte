<script>
	import Menu from "./Menu.svelte"
	import MenuItem from "./MenuItem.svelte"
	export let type = "light"
	export let name = "Select Action"
</script>
<div class="bg-gray-900 w-96 h-160 pt-64 rounded-2xl m-1">
	<Menu type={type} name={name}>
	</Menu>
</div>