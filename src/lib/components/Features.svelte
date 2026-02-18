<script lang="ts">
	import { Target, Shield, Zap } from 'lucide-svelte';
</script>

<section class="py-32 px-6 max-w-7xl mx-auto">
	<div class="grid grid-cols-1 md:grid-cols-3 gap-16 md:gap-24">
		<!-- Feature 1 -->
		<div class="text-center md:text-left">
			<div class="inline-flex items-center justify-center w-12 h-12 mb-8 text-gray-900">
				<Target class="w-12 h-12" strokeWidth="1" />
			</div>
			<h3 class="font-serif-display text-3xl text-gray-900 mb-4 font-light">AI prioritization</h3>
			<p class="text-gray-500 leading-relaxed font-light">
				Know exactly who to call and when. Our AI monitors 10 million companies to surface the perfect moment when buying signals align.
			</p>
		</div>

		<!-- Feature 2 -->
		<div class="text-center md:text-left">
			<div class="inline-flex items-center justify-center w-12 h-12 mb-8 text-gray-900">
				<Shield class="w-12 h-12" strokeWidth="1" />
			</div>
			<h3 class="font-serif-display text-3xl text-gray-900 mb-4 font-light">95% accuracy</h3>
			<p class="text-gray-500 leading-relaxed font-light">
				Triple-verified contact data from 15+ aggregated sources. Never waste time on dead ends or outdated information again.
			</p>
		</div>

		<!-- Feature 3 -->
		<div class="text-center md:text-left">
			<div class="inline-flex items-center justify-center w-12 h-12 mb-8 text-gray-900">
				<Zap class="w-12 h-12" strokeWidth="1" />
			</div>
			<h3 class="font-serif-display text-3xl text-gray-900 mb-4 font-light">Native integration</h3>
			<p class="text-gray-500 leading-relaxed font-light">
				Works seamlessly within LinkedIn and your CRM. Automated logging eliminates manual data entry and tab-switching.
			</p>
		</div>
	</div>
</section>
