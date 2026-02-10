<script lang="ts">
	import FeatureRow from './FeatureRow.svelte';
</script>

<section class="bg-[#050505] py-32 px-6">
	<div class="max-w-7xl mx-auto">
		<div class="mb-32 max-w-4xl">
			<h2 class="font-serif-display text-4xl md:text-6xl text-white leading-tight mb-8">
				One platform engineered to elevate your entire team. <span class="text-gray-500">Navigate every legal challenge with purpose-built tools.</span>
			</h2>
		</div>

		<div class="space-y-32">
			<FeatureRow 
				title="Assistant" 
				description="Ask questions, analyze documents, and draft faster with domain-specific AI."
				imagePosition="right"
				imageType="assistant"
			/>
			<FeatureRow 
				title="Vault" 
				description="Securely store, organize, and bulk analyze legal documents."
				imagePosition="left"
				imageType="vault"
			/>
			<FeatureRow 
				title="Workflows" 
				description="Run pre-built workflows or build your own, tailored to your firm's needs."
				imagePosition="right"
				imageType="workflows"
			/>
			<FeatureRow 
				title="Knowledge" 
				description="Research complex legal, regulatory, and tax questions across domains."
				imagePosition="left"
				imageType="knowledge"
			/>
			<FeatureRow 
				title="Ecosystem" 
				description="Leverage the power of Harvey where you already work."
				imagePosition="right"
				imageType="ecosystem"
			/>
		</div>
	</div>
</section>
