<script lang="ts">
	export let title: string;
	export let description: string;
	export let imagePosition: 'left' | 'right' = 'left';
	export let imageUrl: string;
</script>

<div class="flex flex-col md:flex-row items-center gap-12 md:gap-24 py-24">
	<!-- Text Content -->
	<div class="w-full md:w-1/2 {imagePosition === 'right' ? 'md:order-1' : 'md:order-2'}">
		<h3 class="font-serif-display text-4xl md:text-5xl text-white mb-6">{title}</h3>
		<p class="text-gray-400 text-lg mb-8 leading-relaxed">{description}</p>
	</div>

	<!-- Image/Graphic Content -->
	<div class="w-full md:w-1/2 {imagePosition === 'right' ? 'md:order-2' : 'md:order-1'}">
		<div class="aspect-[4/3] bg-gray-900 rounded-xl overflow-hidden border border-gray-800 relative">
			<img src={imageUrl} alt={title} class="w-full h-full object-cover opacity-80" />
		</div>
	</div>
</div>
