<script>
	import Hello from './components/Hello.svelte';
	let { name } = $props();
</script>

<main class="grid h-svh place-items-center">
	<div class="flex flex-col gap-y-4">
		<a href="https://www.reepolee.com">
			<img src="reepolee.svg" alt="Reepolee logo" class="h-12" />
		</a>
		<Hello {name}></Hello>
		<p>Ready for your next big project?</p>
	</div>
</main>
