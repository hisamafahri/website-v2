<script>
	import profile from '$lib/assets/image/profile.jpeg';
	import Link from './components/Link.svelte';
</script>

<svelte:head>
	<title>Hisam Fahri</title>
</svelte:head>

<div class="flex flex-row items-center justify-start space-x-4 mt-24">
	<img class="rounded-full w-14 h-14" src={profile} alt="profile" />
	<div>
		<h2 class="text-lg font-semibold">Hisam Fahri</h2>
		<p class="text-base font-normal text-gray-400">Software Engineer</p>
	</div>
</div>

<div class="mt-8">
	<p class="text-sm text-gray-700">
		I'm an engineer interested in system and design architecture (well technically every part of building a product), currently working at <a
			class="underline underline-offset-4 hover:no-underline hover:text-orange-500"
			href="https://pitik.id"
			target="_blank">🐔 Pitik</a
		>.
	</p>
</div>

<div class="mt-8">
	<h3 class="mb-6">Links</h3>
	<Link name="GitHub" href="https://github.com/hisamafahri" account="@hisamafahri" />
	<Link name="Twitter" href="https://twitter.com/hisamafahri" account="@hisamafahri" />
	<Link name="LinkedIn" href="https://linkedin.com/in/hisamafahri" account="/in/hisamafahri" />
	<Link name="Email me" href="mailto:me@hisamafahri.com" account="me@hisamafahri.com" />
</div>
