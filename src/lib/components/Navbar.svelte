<script lang="ts">
	import { ChevronDown } from 'lucide-svelte';
</script>

<nav class="fixed top-0 left-0 w-full bg-white/90 backdrop-blur-md z-50 border-b border-gray-100">
	<div class="max-w-7xl mx-auto px-6 h-16 flex items-center justify-between">
		<!-- Logo -->
		<a href="/" class="flex items-center">
			<svg id="Layer_2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 441.67 133.42" class="h-8 w-auto">
				<defs><style>.cls-1{fill:#073742;}</style></defs>
				<g id="LOGOS">
					<g>
						<path class="cls-1" d="M59.05,133.42c26.09,0,45.65-13.56,45.65-36.99,0-24.79-18.41-32.92-38.94-37.95l-14.39-3.49c-14-3.49-22.83-7.55-22.83-18.98,0-9.88,8.82-15.69,21.1-15.69,14.31,0,24.26,5.7,32.28,21.52l19.66-9.53C92.38,14.51,74.59,0,51,0S5.92,13.17,5.92,37.57s19.37,32.92,37.59,36.79l12.08,2.71c16.69,3.68,27.04,7.17,27.04,19.75,0,11.81-10.36,16.46-23.21,16.46-15.73,0-31.07-8.91-39.39-27.98L0,95.05c9.97,21.88,32.23,38.37,59.05,38.37Z"/>
						<g>
							<path class="cls-1" d="M148.03,133.42c12.95,0,21.54-6.19,26.72-14.99,1.37-2.33,4.93-1.38,4.93,1.32v11.73s21.67,0,21.67,0V37.18h-21.67v52.87c0,15.49-5.37,25.75-21.1,25.75-14.39,0-18.22-7.94-18.22-19.56V37.18h-21.48V102.83c0,19.56,11.12,30.6,29.15,30.6Z"/>
							<path class="cls-1" d="M241.61,131.49v-51.9c0-15.69,9.97-28.08,20.72-28.08,6.33,0,8.82,4.26,8.82,9.49s-1.16,10.46-2.59,14.72h21.1c.96-3.78,2.88-9.68,2.88-18.78,0-13.94-9.68-21.69-21.38-21.69s-19.66,6.54-24.67,15.59c-1.3,2.35-4.87,1.44-4.87-1.25v-12.4s-21.48,0-21.48,0v94.31h21.48Z"/>
							<path class="cls-1" d="M324.82,131.49V54.49h27.24v-17.31h-27.24s-2.81-19.91,12.2-19.91c12.7,0,15.04,12.05,15.04,12.05l17.48-8.49c-4.03-8.8-14.45-20.83-33.1-20.83-14.67,0-33.1,8.44-33.1,38.81v92.68h21.48Z"/>
							<path class="cls-1" d="M399.66,133.42c20.72,0,33.37-9.49,40.47-20.33l-13.23-13.94c-3.45,7.94-11.39,16.46-27.04,16.46-13.64,0-24.55-9.1-25.7-25.95h66.75c.38-1.94,.77-6,.77-9.49,0-26.14-15.54-44.93-43.54-44.93-26.28,0-44.5,19.56-44.5,49.19s18.22,48.99,46.03,48.99Zm-1.53-80.75c14.19,0,24.17,9.21,24.17,21.33h-47.95c0-11.81,10.55-21.33,23.78-21.33Z"/>
						</g>
					</g>
				</g>
			</svg>
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
