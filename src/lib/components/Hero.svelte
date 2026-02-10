<script lang="ts">
	import { Play } from 'lucide-svelte';
</script>

<section class="pt-32 pb-20 px-6 max-w-7xl mx-auto">
	<div class="mb-16">
		<span class="text-sm font-medium text-gray-500 uppercase tracking-wide mb-4 block">Platform Overview</span>
		<h1 class="font-serif-display text-6xl md:text-7xl lg:text-8xl font-medium tracking-tight text-gray-900 leading-[0.95] mb-8">
			Engineered for<br />Every Task
		</h1>
		<p class="text-lg md:text-xl text-gray-600 max-w-2xl leading-relaxed">
			More than 100,000 legal professionals around the world use Harvey cut through complexity to navigate complex legal work.
		</p>
	</div>

	<!-- Hero Image -->
	<div class="relative w-full rounded-xl overflow-hidden shadow-2xl border border-gray-200 bg-white">
		<!-- Mockup of the interface -->
		<div class="aspect-[16/9] bg-gray-50 flex">
			<!-- Sidebar -->
			<div class="w-64 bg-gray-900 h-full p-4 flex flex-col hidden md:flex">
				<div class="h-8 w-8 bg-gray-700 rounded mb-8"></div>
				<div class="space-y-4">
					<div class="h-4 w-32 bg-gray-800 rounded"></div>
					<div class="h-4 w-24 bg-gray-800 rounded"></div>
					<div class="h-4 w-28 bg-gray-800 rounded"></div>
				</div>
				<div class="mt-auto space-y-4">
					<div class="h-4 w-20 bg-gray-800 rounded"></div>
					<div class="h-4 w-24 bg-gray-800 rounded"></div>
				</div>
			</div>
			<!-- Main Content -->
			<div class="flex-1 p-8 flex flex-col items-center justify-center bg-white relative">
				<div class="absolute top-4 left-4 flex space-x-2">
					<div class="h-3 w-3 rounded-full bg-red-400"></div>
					<div class="h-3 w-3 rounded-full bg-yellow-400"></div>
					<div class="h-3 w-3 rounded-full bg-green-400"></div>
				</div>
				
				<div class="mb-8 text-center">
					<h2 class="font-serif-display text-4xl text-gray-900 mb-2">Harvey</h2>
					<div class="flex space-x-4 justify-center text-sm text-gray-500">
						<span>Draft document</span>
						<span>Review table</span>
					</div>
				</div>

				<!-- Search Bar -->
				<div class="w-full max-w-2xl bg-white border border-gray-200 rounded-lg shadow-sm p-4 flex items-center justify-between">
					<span class="text-gray-400">Ask Harvey anything. Type @ to add sources.</span>
					<div class="flex space-x-2">
						<div class="h-6 w-6 bg-gray-100 rounded"></div>
						<div class="h-6 w-6 bg-gray-100 rounded"></div>
					</div>
				</div>
				
				<!-- Chips below search -->
				<div class="mt-4 flex space-x-2">
					<span class="px-3 py-1 bg-gray-100 rounded-full text-xs text-gray-600 flex items-center gap-1">
						<div class="w-3 h-3 bg-gray-400 rounded-full"></div> Files
					</span>
					<span class="px-3 py-1 bg-gray-100 rounded-full text-xs text-gray-600 flex items-center gap-1">
						<div class="w-3 h-3 bg-gray-400 rounded-full"></div> Sources
					</span>
				</div>
			</div>
		</div>
	</div>

	<button class="mt-8 flex items-center text-sm font-medium text-gray-900 hover:text-gray-600 transition-colors group">
		<div class="w-8 h-8 rounded-full bg-black text-white flex items-center justify-center mr-3 group-hover:bg-gray-800 transition-colors">
			<Play class="w-3 h-3 fill-current ml-0.5" />
		</div>
		Watch Video
	</button>
</section>
