<script lang="ts">
	import { projects } from "$lib/data";
</script>

<section class="py-10">
	<h2 class="w-full text-4xl font-medium tracking-tight md:text-5xl lg:text-7xl">projects</h2>
	<div class="pt-5">
		<ul class="text-sm">
			{#each projects as project}
				<li class="py-2">
					—
					<a href={project.href} target="_blank">{project.title}</a>
				</li>
			{/each}
		</ul>
	</div>
</section>
