<script>
	import '@/main';
	import favicon from '@/lib/assets/favicon.svg';
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>Rafico</title>
</svelte:head>
{@render children()}
