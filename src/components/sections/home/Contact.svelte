<script>
	import contactImg from '$lib/assets/images/contact-img.webp';
	import CtaButton from '../../Buttons/CtaButton.svelte';
</script>

<div class="mt-20 flex flex-col gap-y-4 w-full">
	<img src={contactImg} class="rounded-lg" width="auto" alt="" srcset="" />
	<h3 class="h3">Contact Us</h3>
	<p>
		Got a question?, Need help with your order?, Intrested partner with us, We're here to help! fill
		out the form below or email us at budi@kntl.com
	</p>
	<label for="name">Name : </label>
	<input type="text" class="input-text" name="" id="" />
	<label for="name">email : </label>
	<input type="email" class="input-text" name="" id="" />
	<label for="message">Message :</label>
	<textarea name="" class="input-text h-28" id=""></textarea>
	<CtaButton />
</div>
