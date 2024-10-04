<script>
	import "../app.pcss";

	import { Metadata, Noise, SiteHeader } from "$lib/components";
</script>

<Metadata />
<Noise />
<main class="mx-4 flex max-w-2xl flex-1 flex-col antialiased md:flex-row lg:mx-auto lg:flex-col">
	<SiteHeader />
	<slot />
</main>
