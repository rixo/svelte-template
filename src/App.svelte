<script>
	import { Foo, Bar } from './components/index.js'
	export let name;
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello {name}!</h1>

<Foo />

<!-- <Bar /> is unused -->
