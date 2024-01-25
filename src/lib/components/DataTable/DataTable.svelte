<script>
	import './styles.css';
	let className = '';
	let extendedClassname = `DataTable ${className}`;
	export { className as class };
</script>

<div class={extendedClassname}>
	<table class="table">
		<thead class="table-header">
			<tr>
				<th class="table-header-cell">Column 1</th>
				<th class="table-header-cell">Column 2</th>
				<th class="table-header-cell">Column 3</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Row 1</td>
				<td>Row 1</td>
				<td>Row 1</td>
			</tr>
			<tr>
				<td>Row 2</td>
				<td>Row 2</td>
				<td>Row 2</td>
			</tr>
			<tr>
				<td>Row 3</td>
				<td>Row 3</td>
				<td>Row 3</td>
			</tr>
		</tbody>
	</table>
</div>
