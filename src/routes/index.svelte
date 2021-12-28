<script>
	import ProjectBox from '$lib/ProjectBox.svelte';
</script>

<div>
	<ProjectBox
		imageLink="/nopcommerce-patches.jpg"
		link="https://nopcommerce-patches.serret.dev/"
		name="NopCommerce Patch Generator"
	>
		Generate Git patch files for NopCommerce releases, by selecting the releases or commits you want
		to generate a patch for.
	</ProjectBox>

	<ProjectBox imageLink="/pdfsvex.jpg" link="https://pdfsvex.serret.dev/" name="pdfsvex">
		PDF generation, made easy
	</ProjectBox>
	<ProjectBox
		imageLink="/gleisbelegung.jpg"
		link="https://gleisbelegung.serret.dev/"
		name="Plugin Gleisbelegung (for stellwerksim.de)"
	>
		Plugin to display the occupancy of the individual platforms at a station
	</ProjectBox>
</div>

<style>
	div {
		display: flex;
		justify-content: space-around;
		flex-wrap: wrap;
	}
</style>
