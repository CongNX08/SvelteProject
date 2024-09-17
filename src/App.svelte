<script>
	let name = 'Svelte';
	let src = 'https://picsum.photos/200/300';
	let string = 'Some <strong>Svelte</strong> with html ';
</script>

<img {src} alt="Some text {name}" />
<h1>Hello {name.toLocaleLowerCase()}</h1>
<p>{@html string}</p>

<style>
	h1 {
		color: red;
	}
</style>
