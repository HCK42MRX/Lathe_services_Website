<script>
	import CtaButton from '../../Buttons/CtaButton.svelte';
</script>

<header class="rounded-xl text-white relative">
	<div class="h-full flex flex-col gap-y-2 justify-end py-12 px-8 w-[800px]">
		<h3 class="h3 font-bold">Percision Lathe Services</h3>
		<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos, inventore.</p>
		<CtaButton />
	</div>
</header>

<style>
	header {
		background:
			linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
			url('$lib/assets/images/hero-img.webp') no-repeat;
		background-size: cover;
		background-position-y: -120px;
		height: 500px;
	}
</style>
