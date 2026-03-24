<script>
	import '@/main';
	import favicon from '@/lib/assets/favicon.svg';
	let { children } = $props();

	// eslint-disable-next-line svelte/valid-prop-names-in-kit-pages
	export const ssr = false;
	// eslint-disable-next-line svelte/valid-prop-names-in-kit-pages
	export const prerender = true;
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>Rafico</title>
</svelte:head>
{@render children()}
