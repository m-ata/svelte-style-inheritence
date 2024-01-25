<script>
	import TestComp from '$lib/components/TestComp/TestComp.svelte';
	import './styles.css';
	import './morestyles.css';
</script>

<svelte:head>
	<title>Example One</title>
	<meta name="description" content="Example One" />
</svelte:head>
<div id="myparent">
	<h1>Example One</h1>

	<TestComp />
	<TestComp class="extendTestComp" />
</div>

