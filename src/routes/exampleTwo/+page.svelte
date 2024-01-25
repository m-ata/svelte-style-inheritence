<script>
	import TestComp from '$lib/components/TestComp/TestComp.svelte';
	import DataTable from '$lib/components/DataTable/DataTable.svelte';
	import './styles.css';
	import './morestyles.css';
</script>

<svelte:head>
	<title>Example Two</title>
	<meta name="description" content="Example Two" />
</svelte:head>
<div id="myparent">
	<h1>Example Two</h1>
	<h2>Plain component</h2>
	<TestComp />
	<hr/>
	<h2>Component, overridden background-color</h2>
	<pre>
		.extendTestComp2.TestComp {'{'}
			background-color: green;
		{'}'}
	</pre>
	<TestComp class="extendTestComp2" />
	<hr/>
	<h2>Component, overridden background-color, added font-size and border</h2>
	<pre>
		.extendTestComp2a.TestComp {'{'}
		font-size: x-large;
		background-color: red;
		border: 4px solid black;
		{'}'}
	</pre>
	<TestComp class="extendTestComp2a" />
	<hr/>
	<DataTable class="override" />
	<hr/>
	<DataTable class="foobar" />
</div>

