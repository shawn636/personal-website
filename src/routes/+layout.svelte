<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<div
	class="fixed top-0 z-30 flex h-16 w-full items-center justify-start gap-5 rounded border-b bg-zinc-900/40 p-5 text-white shadow-md"
>
	<div class="my-2 border-2 border-white p-1 text-3xl font-semibold tracking-wider">SL</div>
	<div class="flex flex-col">
		<h1 class="text-3xl font-bold">Portfolio</h1>
		<h2 class="text-xs">by Shawn Long</h2>
	</div>
</div>
{@render children()}
