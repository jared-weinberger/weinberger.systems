<script>
	import '../app.css';
</script>

<nav class="flex flex-nowrap h-14 p-2">
	<div class="flex items-end gap-2">
		<h1 class="text-3xl">Jared Weinberger</h1>
		<h2 class="text-l">For the Joy of Creation</h2>
	</div>
	<div class="flex-grow"></div>
	<div class="flex gap-2 items-end">
		<div class="hover:bg-slate-100">
			<a href="https://www.linkedin.com/in/jared-weinberger-764720163">
				LinkedIn <img
					class="object-contain h-4 w-4 inline-block grayscale"
					src="/logos/LinkedInLogo-black.png"
					alt="LinkedIn Icon"
				/>
			</a>
		</div>

		<div class="hover:bg-slate-100">
			<a href="https://github.com/jared-weinberger">
				GitHub <img
					class="object-contain h-4 w-4 inline-block"
					src="/logos/GitHubLogo.svg"
					alt="LinkedIn Icon"
				/>
			</a>
		</div>
	</div>
</nav>
<slot />
<footer class="absolute bottom-0 left-0">
	<p class="container m-2">&copy; Jared Weinberger 2024. All rights reserved.</p>
</footer>
