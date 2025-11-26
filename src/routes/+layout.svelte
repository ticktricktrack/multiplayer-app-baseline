<script lang="ts">
	import './layout.css';
	import '../app.css';
	import logo from '$lib/assets/logo.svg';
	import Nav from '$lib/components/nav.svelte';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={logo} />
</svelte:head>

<Nav/>
{@render children()}
