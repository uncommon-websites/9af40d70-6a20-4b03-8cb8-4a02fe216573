<script lang="ts">
	import { ArrowRight } from 'lucide-svelte';
</script>

<footer class="bg-gray-900 text-white pt-32 pb-12 px-6 border-t border-gray-800">
	<div class="max-w-7xl mx-auto">
		<!-- CTA Section -->
		<div class="text-center border-b border-gray-800 pb-24 mb-24">
			<h2 class="font-serif-display text-5xl md:text-7xl mb-12 font-light">
				Ready to transform<br/>your pipeline?
			</h2>
			<button class="group inline-flex items-center gap-2 bg-white text-black px-8 py-4 text-sm font-medium hover:bg-gray-100 transition-colors">
				Get started
				<ArrowRight class="w-4 h-4 group-hover:translate-x-1 transition-transform" />
			</button>
		</div>

		<!-- Links Section -->
		<div class="grid grid-cols-2 md:grid-cols-4 gap-12 mb-16">
			<!-- Column 1 -->
			<div>
				<h4 class="text-sm text-gray-500 mb-6 font-light">Product</h4>
				<ul class="space-y-3 text-sm text-gray-400 font-light">
					<li><a href="#" class="hover:text-white transition-colors">Features</a></li>
					<li><a href="#" class="hover:text-white transition-colors">Integrations</a></li>
					<li><a href="#" class="hover:text-white transition-colors">Pricing</a></li>
				</ul>
			</div>

			<!-- Column 2 -->
			<div>
				<h4 class="text-sm text-gray-500 mb-6 font-light">Company</h4>
				<ul class="space-y-3 text-sm text-gray-400 font-light">
					<li><a href="#" class="hover:text-white transition-colors">About</a></li>
					<li><a href="#" class="hover:text-white transition-colors">Customers</a></li>
					<li><a href="#" class="hover:text-white transition-colors">Careers</a></li>
				</ul>
			</div>

			<!-- Column 3 -->
			<div>
				<h4 class="text-sm text-gray-500 mb-6 font-light">Resources</h4>
				<ul class="space-y-3 text-sm text-gray-400 font-light">
					<li><a href="#" class="hover:text-white transition-colors">Blog</a></li>
					<li><a href="#" class="hover:text-white transition-colors">Documentation</a></li>
					<li><a href="#" class="hover:text-white transition-colors">Support</a></li>
				</ul>
			</div>

			<!-- Column 4 -->
			<div>
				<h4 class="text-sm text-gray-500 mb-6 font-light">Legal</h4>
				<ul class="space-y-3 text-sm text-gray-400 font-light">
					<li><a href="#" class="hover:text-white transition-colors">Privacy</a></li>
					<li><a href="#" class="hover:text-white transition-colors">Terms</a></li>
					<li><a href="#" class="hover:text-white transition-colors">Security</a></li>
				</ul>
			</div>
		</div>

		<!-- Bottom Bar -->
		<div class="flex flex-col md:flex-row justify-between items-center pt-8 border-t border-gray-800 text-sm text-gray-500 font-light">
			<div class="mb-4 md:mb-0">
				© 2026 Surfe. All rights reserved.
			</div>
			<div class="flex gap-6">
				<a href="#" class="hover:text-white transition-colors">LinkedIn</a>
				<a href="#" class="hover:text-white transition-colors">Twitter</a>
				<a href="#" class="hover:text-white transition-colors">GitHub</a>
			</div>
		</div>
	</div>
</footer>
