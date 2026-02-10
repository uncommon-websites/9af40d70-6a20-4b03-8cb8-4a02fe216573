<script lang="ts">
	export let title: string;
	export let description: string;
	export let imagePosition: 'left' | 'right' = 'left';
	export let imageType: 'assistant' | 'vault' | 'workflows' | 'knowledge' | 'ecosystem' = 'assistant';
</script>

<div class="flex flex-col md:flex-row items-center gap-12 md:gap-24 py-24">
	<!-- Text Content -->
	<div class="w-full md:w-1/2 {imagePosition === 'right' ? 'md:order-1' : 'md:order-2'}">
		<h3 class="font-serif-display text-4xl md:text-5xl text-white mb-6">{title}</h3>
		<p class="text-gray-400 text-lg mb-8 leading-relaxed">{description}</p>
		<button class="px-6 py-2 border border-gray-600 rounded text-sm text-white hover:bg-white hover:text-black transition-colors">
			Learn More
		</button>
	</div>

	<!-- Image/Graphic Content -->
	<div class="w-full md:w-1/2 {imagePosition === 'right' ? 'md:order-2' : 'md:order-1'}">
		<div class="aspect-[4/3] bg-gray-900 rounded-xl overflow-hidden border border-gray-800 relative">
			<!-- Placeholder Content based on imageType -->
			{#if imageType === 'assistant'}
				<div class="absolute inset-0 p-8 flex flex-col">
					<div class="bg-gray-800 rounded-lg p-4 mb-4 w-3/4 self-end">
						<div class="h-2 bg-gray-700 rounded w-full mb-2"></div>
						<div class="h-2 bg-gray-700 rounded w-2/3"></div>
					</div>
					<div class="bg-gray-700 rounded-lg p-4 mb-4 w-3/4">
						<div class="h-2 bg-gray-600 rounded w-full mb-2"></div>
						<div class="h-2 bg-gray-600 rounded w-1/2"></div>
					</div>
					<div class="mt-auto">
						<div class="bg-gray-800 rounded-full h-10 w-full flex items-center px-4">
							<div class="h-2 bg-gray-700 rounded w-1/2"></div>
						</div>
					</div>
				</div>
			{:else if imageType === 'vault'}
				<div class="absolute inset-0 p-8">
					<div class="space-y-4">
						<div class="flex items-center justify-between border-b border-gray-800 pb-2">
							<div class="h-3 w-24 bg-gray-700 rounded"></div>
							<div class="h-3 w-12 bg-gray-800 rounded"></div>
						</div>
						<div class="flex items-center justify-between border-b border-gray-800 pb-2">
							<div class="h-3 w-32 bg-gray-700 rounded"></div>
							<div class="h-3 w-12 bg-gray-800 rounded"></div>
						</div>
						<div class="flex items-center justify-between border-b border-gray-800 pb-2">
							<div class="h-3 w-20 bg-gray-700 rounded"></div>
							<div class="h-3 w-12 bg-gray-800 rounded"></div>
						</div>
					</div>
				</div>
			{:else if imageType === 'workflows'}
				<div class="absolute inset-0 p-8 flex items-center justify-center">
					<div class="relative w-full h-full">
						<div class="absolute top-10 left-1/2 -translate-x-1/2 bg-gray-800 px-4 py-2 rounded border border-gray-700 text-xs text-gray-400">Trigger</div>
						<div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 bg-gray-800 px-4 py-2 rounded border border-gray-700 text-xs text-gray-400">Action</div>
						<div class="absolute bottom-10 left-1/2 -translate-x-1/2 bg-gray-800 px-4 py-2 rounded border border-gray-700 text-xs text-gray-400">Result</div>
						<div class="absolute inset-0 border-l border-dashed border-gray-700 left-1/2 -translate-x-1/2 z-[-1]"></div>
					</div>
				</div>
			{:else if imageType === 'knowledge'}
				<div class="absolute inset-0 p-8 grid grid-cols-2 gap-4 content-center">
					<div class="bg-gray-800 p-4 rounded flex items-center gap-2">
						<div class="w-4 h-4 rounded-full bg-red-500"></div>
						<div class="h-2 w-16 bg-gray-600 rounded"></div>
					</div>
					<div class="bg-gray-800 p-4 rounded flex items-center gap-2">
						<div class="w-4 h-4 rounded-full bg-blue-500"></div>
						<div class="h-2 w-16 bg-gray-600 rounded"></div>
					</div>
					<div class="bg-gray-800 p-4 rounded flex items-center gap-2">
						<div class="w-4 h-4 rounded-full bg-green-500"></div>
						<div class="h-2 w-16 bg-gray-600 rounded"></div>
					</div>
					<div class="bg-gray-800 p-4 rounded flex items-center gap-2">
						<div class="w-4 h-4 rounded-full bg-yellow-500"></div>
						<div class="h-2 w-16 bg-gray-600 rounded"></div>
					</div>
				</div>
			{:else if imageType === 'ecosystem'}
				<div class="absolute inset-0 p-8 flex flex-wrap gap-4 justify-center items-center content-center">
					<div class="w-12 h-12 bg-white rounded flex items-center justify-center text-black font-bold">W</div>
					<div class="w-12 h-12 bg-blue-600 rounded flex items-center justify-center text-white font-bold">O</div>
					<div class="w-12 h-12 bg-black border border-gray-700 rounded flex items-center justify-center text-white font-serif font-bold">H</div>
					<div class="w-12 h-12 bg-blue-400 rounded flex items-center justify-center text-white font-bold">i</div>
				</div>
			{/if}
		</div>
	</div>
</div>
