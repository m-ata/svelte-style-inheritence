<script>
	import '$lib/components/TestComp/styles.css';
	import TestComp from '$lib/components/TestComp/TestComp.svelte';
	import './calendar.css'; // read ->  @olsitec/svelte-calendar/styles/global.css
	import './styles.css';
</script>

<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>
<div class="text-column">
	<h1>About this app</h1>
	<TestComp>blah</TestComp>
	<TestComp classOverride="overrideTestComp" />
	<TestComp classOverride="TestComp extendTestComp" />
</div>
