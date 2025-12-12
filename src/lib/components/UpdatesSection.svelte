<section class="py-20 border-b border-border">
	<div class="container-custom">
		<div class="grid grid-cols-1 md:grid-cols-2 gap-16">
			
			<!-- Left Column: CTA & Visual -->
			<div class="flex flex-col h-full">
				<div class="mb-8">
					<p class="font-mono text-xs text-muted mb-4">Partner with us</p>
					<h2 class="text-2xl font-medium mb-4">Building the future of AI together</h2>
					<p class="text-muted font-light mb-8 text-sm leading-relaxed max-w-md">
						Infinity Forge combines deep technical expertise with proven business acumen to transform AI research into production systems and build ventures from ideation to IPO.
					</p>
					<div class="flex gap-3 mb-12">
						<button class="border border-border px-3 py-1.5 text-xs font-mono uppercase hover:bg-primary-50 transition-colors flex items-center gap-2">
							START YOUR VENTURE
							<span class="text-muted border border-muted/30 rounded px-1 text-[9px] min-w-[16px] text-center">S</span>
						</button>
						<button class="border border-border px-3 py-1.5 text-xs font-mono uppercase hover:bg-primary-50 transition-colors flex items-center gap-2">
							EXPLORE RESEARCH
							<span class="text-muted border border-muted/30 rounded px-1 text-[9px] min-w-[16px] text-center">R</span>
						</button>
					</div>
				</div>
				
				<!-- Technical Visual -->
				<div class="mt-auto w-full h-48 bg-black relative overflow-hidden flex items-center justify-center">
					{#each Array(100) as _, i}
						<div 
							class="h-full bg-white absolute" 
							style="
								left: {i}%; 
								width: {Math.random() * 2}%; 
								opacity: {Math.random()};
							"
						></div>
					{/each}
					<div class="absolute inset-0 flex items-center justify-center">
						<div class="bg-black text-white font-mono text-[10px] px-2 py-1 z-10">
							infinity-forge.ai
						</div>
					</div>
				</div>
			</div>

			<!-- Right Column: Updates -->
			<div>
				<p class="font-mono text-xs text-muted mb-8">Latest updates</p>
				
				<div class="space-y-12">
					<!-- Update 1 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">January 2025</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Healthcare AI deployment achieves 95% accuracy</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Our automated hemoglobin analysis system for a major healthcare network demonstrates 95% anemia detection accuracy in production. The deployment showcases our systematic methodology from research to real-world impact, processing thousands of samples daily with sub-second latency.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Case Study</span>
						</div>
					</div>

					<!-- Update 2 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">December 2024</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">New research partnership with MIT and Stanford</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Infinity Forge announces expanded research collaborations with MIT and Stanford focusing on edge AI systems and federated learning. The partnerships will accelerate our work on sub-10ms latency inference and model quantization techniques for production deployments.
							</p>
							<div class="flex gap-2">
								<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Partnership</span>
								<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Research</span>
							</div>
						</div>
					</div>

					<!-- Update 3 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">November 2024</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Venture studio launches third AI-first company</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Our venture studio model continues to deliver results with the launch of our third AI-first company. Following our proven 18-month framework, the new venture focuses on compliance AI for financial services, combining our technical expertise with domain-specific knowledge.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Venture Launch</span>
						</div>
					</div>

					<!-- Update 4 -->
					<div class="flex gap-8 group">
						<div class="font-mono text-xs text-muted w-24 shrink-0 pt-1">October 2024</div>
						<div>
							<h3 class="font-medium text-sm mb-2 group-hover:text-accent transition-colors cursor-pointer">Ramphis Castro shares insights at AI Conference</h3>
							<p class="text-xs text-muted leading-relaxed mb-3">
								Founder & CEO Ramphis Castro presents "From Research to Production: Bridging the AI Commercialization Gap" at the annual AI Systems Conference, sharing lessons from deploying $100M+ in capital across AI ventures globally.
							</p>
							<span class="bg-gray-100 text-[10px] px-1.5 py-0.5 rounded text-muted">Speaking</span>
						</div>
					</div>
				</div>
			</div>

		</div>
	</div>
</section>
