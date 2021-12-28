<script>
	export let imageLink;
	export let link;
	export let name;
</script>

<div class="project">
	<div class="image">
		<img src={imageLink} />
	</div>
	<a href={link}>
		<span>{name}</span>
	</a>
	<div>
		<slot />
	</div>
</div>

<style>
	.project {
		background-color: #333;
		border-radius: 10px;
		width: 32%;
		padding: 10px;
		margin: 5px 0;
	}

	.image {
	}
</style>
