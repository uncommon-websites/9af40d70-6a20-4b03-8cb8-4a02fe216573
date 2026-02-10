<script lang="ts">
	import { ChevronDown } from 'lucide-svelte';
</script>

<nav class="fixed top-0 left-0 w-full bg-white/90 backdrop-blur-md z-50 border-b border-gray-100">
	<div class="max-w-7xl mx-auto px-6 h-16 flex items-center justify-between">
		<!-- Logo -->
		<a href="/" class="font-serif-display text-2xl font-medium tracking-tight text-gray-900">
			Harvey
		</a>

		<!-- Navigation Links -->
		<div class="hidden md:flex items-center space-x-8">
			<button class="group flex items-center text-sm font-medium text-gray-600 hover:text-gray-900 transition-colors">
				Platform
				<ChevronDown class="w-3 h-3 ml-1 text-gray-400 group-hover:text-gray-900 transition-colors" />
			</button>
			<button class="group flex items-center text-sm font-medium text-gray-600 hover:text-gray-900 transition-colors">
				Solutions
				<ChevronDown class="w-3 h-3 ml-1 text-gray-400 group-hover:text-gray-900 transition-colors" />
			</button>
			<a href="/customers" class="text-sm font-medium text-gray-600 hover:text-gray-900 transition-colors">
				Customers
			</a>
			<a href="/security" class="text-sm font-medium text-gray-600 hover:text-gray-900 transition-colors">
				Security
			</a>
			<button class="group flex items-center text-sm font-medium text-gray-600 hover:text-gray-900 transition-colors">
				Resources
				<ChevronDown class="w-3 h-3 ml-1 text-gray-400 group-hover:text-gray-900 transition-colors" />
			</button>
			<button class="group flex items-center text-sm font-medium text-gray-600 hover:text-gray-900 transition-colors">
				About
				<ChevronDown class="w-3 h-3 ml-1 text-gray-400 group-hover:text-gray-900 transition-colors" />
			</button>
		</div>

		<!-- Right Side -->
		<div class="flex items-center">
			<a href="/login" class="text-sm font-medium text-gray-900 hover:text-gray-600 transition-colors">
				Login
			</a>
		</div>
	</div>
</nav>
