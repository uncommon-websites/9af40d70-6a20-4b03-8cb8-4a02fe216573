<script lang="ts">
	import { ArrowUpRight } from 'lucide-svelte';
</script>

<section class="bg-[#0a0a0a] py-32 px-6 relative overflow-hidden">
	<!-- Subtle texture/noise overlay could go here -->
	<div class="absolute inset-0 opacity-5 bg-[url('https://grainy-gradients.vercel.app/noise.svg')] mix-blend-overlay pointer-events-none"></div>

	<div class="max-w-7xl mx-auto relative z-10">
		<div class="flex flex-col md:flex-row justify-between gap-16 mb-24">
			<h2 class="font-serif-display text-4xl md:text-5xl text-white max-w-md leading-tight">
				Enterprise-grade security and controls
			</h2>
			<div class="max-w-lg">
				<p class="text-gray-400 text-lg leading-relaxed mb-8">
					Harvey meets the highest industry standards for security and compliance. We include all default controls that enterprise teams expect: SAML SSO, audit logs, IP allow-listing, data lifecycle management, and more.
				</p>
				<button class="px-6 py-2 border border-gray-700 rounded text-sm text-white hover:bg-white hover:text-black transition-colors">
					More About Security
				</button>
			</div>
		</div>

		<div class="grid grid-cols-2 md:grid-cols-4 gap-8 border-t border-gray-800 pt-16">
			<!-- Badge 1 -->
			<div class="flex flex-col items-center text-center group cursor-pointer">
				<div class="w-16 h-16 mb-6 rounded-full border border-gray-700 flex items-center justify-center text-gray-500 group-hover:border-gray-500 group-hover:text-white transition-colors">
					<svg class="w-8 h-8" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
						<path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z" />
					</svg>
				</div>
				<h3 class="text-white font-medium mb-1">SOC2 II</h3>
				<div class="flex items-center text-xs text-gray-500 group-hover:text-white transition-colors">
					Details <ArrowUpRight class="w-3 h-3 ml-1" />
				</div>
			</div>

			<!-- Badge 2 -->
			<div class="flex flex-col items-center text-center group cursor-pointer">
				<div class="w-16 h-16 mb-6 rounded-full border border-gray-700 flex items-center justify-center text-gray-500 group-hover:border-gray-500 group-hover:text-white transition-colors">
					<svg class="w-8 h-8" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
						<rect x="3" y="11" width="18" height="11" rx="2" ry="2" />
						<path d="M7 11V7a5 5 0 0 1 10 0v4" />
					</svg>
				</div>
				<h3 class="text-white font-medium mb-1">CCPA</h3>
				<div class="flex items-center text-xs text-gray-500 group-hover:text-white transition-colors">
					Details <ArrowUpRight class="w-3 h-3 ml-1" />
				</div>
			</div>

			<!-- Badge 3 -->
			<div class="flex flex-col items-center text-center group cursor-pointer">
				<div class="w-16 h-16 mb-6 rounded-full border border-gray-700 flex items-center justify-center text-gray-500 group-hover:border-gray-500 group-hover:text-white transition-colors">
					<svg class="w-8 h-8" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
						<circle cx="12" cy="12" r="10" />
						<path d="M2 12h20" />
						<path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z" />
					</svg>
				</div>
				<h3 class="text-white font-medium mb-1">ISO 27001</h3>
				<div class="flex items-center text-xs text-gray-500 group-hover:text-white transition-colors">
					Details <ArrowUpRight class="w-3 h-3 ml-1" />
				</div>
			</div>

			<!-- Badge 4 -->
			<div class="flex flex-col items-center text-center group cursor-pointer">
				<div class="w-16 h-16 mb-6 rounded-full border border-gray-700 flex items-center justify-center text-gray-500 group-hover:border-gray-500 group-hover:text-white transition-colors">
					<svg class="w-8 h-8" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
						<path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z" />
						<path d="M9 12l2 2 4-4" />
					</svg>
				</div>
				<h3 class="text-white font-medium mb-1">GDPR</h3>
				<div class="flex items-center text-xs text-gray-500 group-hover:text-white transition-colors">
					Details <ArrowUpRight class="w-3 h-3 ml-1" />
				</div>
			</div>
		</div>
	</div>
</section>
