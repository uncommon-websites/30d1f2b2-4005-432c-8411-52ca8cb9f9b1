<script lang="ts">
	import FeatureBlock from './FeatureBlock.svelte';
</script>

<!-- Block 1: Four-Phase Methodology -->
<FeatureBlock 
	title="Systematic research-to-production methodology" 
	description="Our four-phase approach transforms frontier AI research into production systems with measurable outcomes."
	buttons={[
		{ text: "EXPLORE METHODOLOGY", icon: true },
		{ text: "VIEW CASE STUDIES" }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm p-6 font-mono text-xs">
		<div class="space-y-4">
			<div class="flex items-start gap-3 pb-3 border-b border-border">
				<div class="w-8 h-8 rounded-full bg-black text-white flex items-center justify-center text-[10px] font-bold shrink-0">01</div>
				<div>
					<div class="font-bold mb-1">DISCOVER</div>
					<div class="text-[10px] text-muted">Literature review & problem formulation</div>
				</div>
			</div>
			<div class="flex items-start gap-3 pb-3 border-b border-border">
				<div class="w-8 h-8 rounded-full bg-black text-white flex items-center justify-center text-[10px] font-bold shrink-0">02</div>
				<div>
					<div class="font-bold mb-1">PROTOTYPE</div>
					<div class="text-[10px] text-muted">Rapid experimentation & proof-of-concept</div>
				</div>
			</div>
			<div class="flex items-start gap-3 pb-3 border-b border-border">
				<div class="w-8 h-8 rounded-full bg-black text-white flex items-center justify-center text-[10px] font-bold shrink-0">03</div>
				<div>
					<div class="font-bold mb-1">VALIDATE</div>
					<div class="text-[10px] text-muted">Rigorous testing & peer review</div>
				</div>
			</div>
			<div class="flex items-start gap-3">
				<div class="w-8 h-8 rounded-full bg-accent text-white flex items-center justify-center text-[10px] font-bold shrink-0">04</div>
				<div>
					<div class="font-bold mb-1">DEPLOY</div>
					<div class="text-[10px] text-muted">Production integration & scaling</div>
				</div>
			</div>
		</div>
	</div>
</FeatureBlock>

<!-- Block 2: Venture Studio -->
<FeatureBlock 
	title="Venture studio from ideation to IPO" 
	description="We build AI-first companies through hands-on co-building, combining technical expertise with proven business acumen."
	buttons={[
		{ text: "START YOUR VENTURE", icon: true }
	]}
	alignRight={true}
>
	<div class="w-full max-w-md bg-white border border-border rounded shadow-sm p-6 flex flex-col gap-4">
		<div class="flex items-center justify-between border-b border-border pb-3">
			<div class="text-xs font-mono font-bold">VENTURE PROGRESS</div>
			<div class="text-[10px] text-muted font-mono">MONTH 12/18</div>
		</div>
		<div class="space-y-3">
			<div class="flex items-center gap-3">
				<div class="w-5 h-5 rounded-full bg-green-500 flex items-center justify-center text-white text-[10px]">✓</div>
				<div class="text-[10px] font-mono">Ideation & Validation</div>
			</div>
			<div class="flex items-center gap-3">
				<div class="w-5 h-5 rounded-full bg-green-500 flex items-center justify-center text-white text-[10px]">✓</div>
				<div class="text-[10px] font-mono">Build & Launch</div>
			</div>
			<div class="flex items-center gap-3">
				<div class="w-5 h-5 rounded-full bg-accent flex items-center justify-center text-white text-[10px]">→</div>
				<div class="text-[10px] font-mono font-bold">Growth & Optimization</div>
			</div>
			<div class="flex items-center gap-3">
				<div class="w-5 h-5 rounded-full bg-gray-200 flex items-center justify-center text-gray-400 text-[10px]">○</div>
				<div class="text-[10px] font-mono text-muted">Scale & Fundraise</div>
			</div>
		</div>
		<div class="w-full bg-gray-100 h-2 rounded-full overflow-hidden mt-2">
			<div class="bg-accent h-full w-2/3"></div>
		</div>
		<div class="mt-2 flex items-center gap-2 text-[10px] text-muted font-mono uppercase">
			<span class="w-2 h-2 bg-green-500 rounded-full"></span>
			ON TRACK FOR SERIES A
		</div>
	</div>
</FeatureBlock>

<!-- Block 3: Technical Co-Founding -->
<FeatureBlock 
	title="Technical co-founding & CTO-as-a-Service" 
	description="Expert AI engineering leadership for startups. We bridge the gap between vision and execution with hands-on technical co-founding."
	buttons={[
		{ text: "GET TECHNICAL SUPPORT", icon: true }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm overflow-hidden font-mono text-[10px]">
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border bg-gray-50 text-muted font-bold">
			<div>SERVICE</div>
			<div>EXPERTISE</div>
			<div>STATUS</div>
		</div>
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border/50 items-center">
			<div class="font-bold text-foreground">AI Architecture</div>
			<div class="flex items-center gap-1">
				<div class="w-2 h-2 rounded-full bg-black"></div>
				<span class="text-muted">MLOps, Edge AI</span>
			</div>
			<div class="text-green-600 font-bold">ACTIVE</div>
		</div>
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border/50 items-center">
			<div class="font-bold text-foreground">Product Dev</div>
			<div class="flex items-center gap-1">
				<div class="w-2 h-2 rounded-full bg-black"></div>
				<span class="text-muted">MVP, Scaling</span>
			</div>
			<div class="text-green-600 font-bold">ACTIVE</div>
		</div>
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border/50 items-center">
			<div class="font-bold text-foreground">Team Building</div>
			<div class="flex items-center gap-1">
				<div class="w-2 h-2 rounded-full bg-black"></div>
				<span class="text-muted">Hiring, Culture</span>
			</div>
			<div class="text-green-600 font-bold">ACTIVE</div>
		</div>
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border/50 items-center">
			<div class="font-bold text-foreground">GTM Strategy</div>
			<div class="flex items-center gap-1">
				<div class="w-2 h-2 rounded-full bg-black"></div>
				<span class="text-muted">Launch, Growth</span>
			</div>
			<div class="text-accent font-bold">PLANNING</div>
		</div>
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border/50 items-center">
			<div class="font-bold text-foreground">Fundraising</div>
			<div class="flex items-center gap-1">
				<div class="w-2 h-2 rounded-full bg-black"></div>
				<span class="text-muted">Pitch, Intros</span>
			</div>
			<div class="text-muted font-bold">UPCOMING</div>
		</div>
	</div>
</FeatureBlock>

<!-- Block 4: Research Focus Areas -->
<FeatureBlock 
	title="Five core research pillars" 
	description="Deep technical expertise across cutting-edge AI domains, from edge computing to conversational systems."
	buttons={[
		{ text: "EXPLORE RESEARCH", icon: true }
	]}
	alignRight={true}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm overflow-hidden font-mono text-[10px]">
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border bg-gray-50 text-muted font-bold">
			<div>RESEARCH AREA</div>
			<div>FOCUS</div>
			<div>PERFORMANCE</div>
		</div>
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border/50 items-center">
			<div class="font-bold text-foreground">Edge AI</div>
			<div class="text-muted">Sub-10ms latency</div>
			<div class="flex gap-0.5">
				{#each Array(5) as _}
					<div class="w-1.5 h-3 bg-accent"></div>
				{/each}
			</div>
		</div>
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border/50 items-center">
			<div class="font-bold text-foreground">Geospatial ML</div>
			<div class="text-muted">Location intel</div>
			<div class="flex gap-0.5">
				{#each Array(4) as _}
					<div class="w-1.5 h-3 bg-black"></div>
				{/each}
				<div class="w-1.5 h-3 bg-gray-200"></div>
			</div>
		</div>
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border/50 items-center">
			<div class="font-bold text-foreground">Compliance AI</div>
			<div class="text-muted">Risk assessment</div>
			<div class="flex gap-0.5">
				{#each Array(5) as _}
					<div class="w-1.5 h-3 bg-black"></div>
				{/each}
			</div>
		</div>
		<div class="grid grid-cols-3 gap-2 p-3 border-b border-border/50 items-center">
			<div class="font-bold text-foreground">MLOps</div>
			<div class="text-muted">Model lifecycle</div>
			<div class="flex gap-0.5">
				{#each Array(4) as _}
					<div class="w-1.5 h-3 bg-black"></div>
				{/each}
				<div class="w-1.5 h-3 bg-gray-200"></div>
			</div>
		</div>
		<div class="grid grid-cols-3 gap-2 p-3 items-center">
			<div class="font-bold text-foreground">Conversational AI</div>
			<div class="text-muted">Advanced RAG</div>
			<div class="flex gap-0.5">
				{#each Array(5) as _}
					<div class="w-1.5 h-3 bg-black"></div>
				{/each}
			</div>
		</div>
	</div>
</FeatureBlock>

<!-- Block 5: Proven Results -->
<FeatureBlock 
	title="Proven results across industries" 
	description="Measurable outcomes from real-world deployments in fintech, retail, and healthcare."
	buttons={[
		{ text: "VIEW CASE STUDIES", icon: true }
	]}
>
	<div class="w-full h-full bg-white border border-border rounded shadow-sm p-6 flex flex-col gap-4">
		<div class="flex items-center justify-between border-b border-border pb-3">
			<div class="text-xs font-mono font-bold">CLIENT OUTCOMES</div>
			<div class="text-[10px] text-green-600 font-mono flex items-center gap-1">
				<span class="w-2 h-2 bg-green-500 rounded-full"></span>
				DEPLOYED
			</div>
		</div>
		
		<!-- Results grid -->
		<div class="space-y-4">
			<div class="border-l-2 border-accent pl-3">
				<div class="text-[10px] font-bold mb-1">FINTECH LEADER</div>
				<div class="text-[9px] text-muted mb-2">Real-time fraud detection</div>
				<div class="flex gap-3 text-[10px]">
					<div><span class="font-bold">99.7%</span> accuracy</div>
					<div><span class="font-bold">40ms</span> latency</div>
					<div><span class="font-bold">85%</span> ↓ false positives</div>
				</div>
			</div>

			<div class="border-l-2 border-black pl-3">
				<div class="text-[10px] font-bold mb-1">GLOBAL RETAILER</div>
				<div class="text-[9px] text-muted mb-2">Supply chain optimization</div>
				<div class="flex gap-3 text-[10px]">
					<div><span class="font-bold">500+</span> locations</div>
					<div><span class="font-bold">30%</span> cost reduction</div>
				</div>
			</div>

			<div class="border-l-2 border-black pl-3">
				<div class="text-[10px] font-bold mb-1">HEALTHCARE NETWORK</div>
				<div class="text-[9px] text-muted mb-2">Automated diagnostics</div>
				<div class="flex gap-3 text-[10px]">
					<div><span class="font-bold">95%</span> detection accuracy</div>
				</div>
			</div>
		</div>

		<div class="mt-auto pt-3 border-t border-border text-[9px] text-muted font-mono">
			$100M+ DEPLOYED CAPITAL
		</div>
	</div>
</FeatureBlock>
