<script>
	import './styles.css';
	let className = '';
	let extendedClassname = `TestComp ${className}`;
	export { className as class };
</script>

<div class={extendedClassname}>
	<p>Test Comp</p>
</div>
