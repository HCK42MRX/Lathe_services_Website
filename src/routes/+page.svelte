<script>
	import Hero from '../components/sections/home/Hero.svelte';
	import Services from '../components/sections/home/Services.svelte';
	import CtaButton from '../components/Buttons/CtaButton.svelte';
	import Contact from '../components/sections/home/Contact.svelte';
</script>

<div class="py-5 container-custom">
	<Hero />
	<div class="about-us mt-8 mb-10 flex flex-col gap-y-3 w-[700px]">
		<h3 class="h3 text-black">Industries We Serve</h3>
		<p class="text-[15px]">
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas numquam pariatur fuga fugiat
			eligendi quia perspiciatis ullam eveniet provident dicta!
		</p>
	</div>
	<Services />
	<Contact />
</div>
