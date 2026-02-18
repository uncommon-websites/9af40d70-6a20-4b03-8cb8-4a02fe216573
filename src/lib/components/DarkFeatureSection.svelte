<script lang="ts">
	import FeatureRow from './FeatureRow.svelte';
</script>

<section class="bg-[#050505] py-32 px-6">
	<div class="max-w-7xl mx-auto">
		<div class="mb-32 max-w-4xl">
			<h2 class="font-serif-display text-4xl md:text-6xl text-white leading-tight mb-8">
				One platform engineered to elevate your entire team. <span class="text-gray-500">Navigate every sales challenge with AI-driven intelligence.</span>
			</h2>
		</div>

		<div class="space-y-32">
			<FeatureRow 
				title="Signal Monitoring" 
				description="Continuously monitor 10 million companies for job changes, funding rounds, hiring spikes, and intent data."
				imagePosition="right"
				imageUrl="/generated/image-a-visualization-of-a-global-data-network-1771339248865-0.webp"
			/>
			<FeatureRow 
				title="Native CRM Sync" 
				description="Automated CRM logging for Salesforce, Hubspot, Pipedrive, and Copper. Eliminate manual data entry forever."
				imagePosition="left"
				imageUrl="/generated/image-a-clean-professional-interface-showing-a-1771339251644-1.webp"
			/>
			<FeatureRow 
				title="Contextual Intelligence" 
				description="Don't just get a number. Get the 'reason to call' and 'what to say' based on real-time buying signals."
				imagePosition="right"
				imageUrl="/generated/image-a-close-up-of-a-sales-reps-screen-showin-1771339254129-2.webp"
			/>
			<FeatureRow 
				title="Moonlight API" 
				description="Scale your sales intelligence with our robust API, designed for complex enterprise use cases."
				imagePosition="left"
				imageUrl="/generated/image-a-sleek-modern-api-documentation-page-wi-1771339256070-3.webp"
			/>
			<FeatureRow 
				title="Performance Lift" 
				description="Elevate your bottom 50% performers to top 25% levels with guided workflows and prioritized leads."
				imagePosition="right"
				imageUrl="/generated/image-a-performance-chart-showing-a-teams-sale-1771339258036-4.webp"
			/>
		</div>
	</div>
</section>
