<script>
	export let name="Default Name"
	export let type="light"
</script>

{#if type==="light"}
<div>
	<a href="/" class="flex items-center justify-left text-gray-900 block text-md font-medium pl-6 pt-3 pb-3 transition-all hover:bg-gray-200 focus:bg-gray-300 hover:text-gray-900"><svg class="mr-3"width='20' height='20'>
   <circle cy="10" cx="10" r='7' stroke='black' stroke-width='1.5' fill='none' />
</svg>{name}</a>
</div>
{/if}

{#if type==="dark"}
<div>
	<a href="/" class="flex items-center justify-left text-gray-300 block text-md font-medium pl-6 pt-3 pb-3 transition-all hover:bg-gray-900 focus:bg-gray-600 hover:text-gray-300"><svg class="mr-3"width='20' height='20'>
   <circle cy="10" cx="10" r='7' stroke='white' stroke-width='1.5' fill='none' />
</svg>{name}</a>
</div>
{/if}