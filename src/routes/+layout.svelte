<script>
	import '../app.css';

	let { children } = $props();
</script>

{@render children()}
<slot></slot>
