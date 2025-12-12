<section class="py-20 border-b border-border">
	<div class="container-custom">
		<div class="flex flex-col md:flex-row justify-between items-start mb-16 gap-8">
			<div>
				<h2 class="text-3xl font-medium mb-2">18-month journey to Series A</h2>
				<p class="text-xl text-muted font-light">Structured venture studio timeline</p>
			</div>
			<div class="max-w-xs text-[10px] text-muted leading-relaxed border-l border-border pl-4">
				<strong class="text-foreground block mb-1">About our methodology</strong>
				Our venture studio follows a proven 18-month framework from ideation to Series A readiness. We combine technical co-founding, hands-on product development, and strategic capital deployment. Each phase builds systematically on the previous, ensuring measurable progress and de-risked outcomes. Learn more about our <a href="#" class="underline">approach</a>.
			</div>
		</div>

		<div class="relative w-full h-[500px] border border-border bg-primary-50/30 p-8 font-mono text-xs">
			<!-- Timeline Grid -->
			<div class="absolute inset-0 p-8">
				<!-- Horizontal timeline -->
				<div class="absolute top-1/2 left-8 right-8 h-0.5 bg-border"></div>
			</div>
			
			<!-- X Axis Label -->
			<div class="absolute bottom-2 left-1/2 -translate-x-1/2 text-muted">
				MONTHS
			</div>

			<!-- Timeline markers -->
			<div class="absolute bottom-8 left-8 right-8 flex justify-between text-[10px] text-muted">
				<span>0</span>
				<span>3</span>
				<span>9</span>
				<span>15</span>
				<span>18</span>
			</div>

			<!-- Phase 1: Ideation & Validation (0-3 months) -->
			<div class="absolute top-[15%] left-[10%] flex flex-col items-start group cursor-pointer z-10 max-w-[180px]">
				<div class="flex items-center gap-2 mb-2">
					<div class="w-3 h-3 bg-black rounded-full"></div>
					<span class="font-bold text-[11px]">IDEATION & VALIDATION</span>
				</div>
				<div class="text-[9px] text-muted leading-relaxed">
					Market research<br/>
					Technical feasibility<br/>
					MVP definition
				</div>
				<div class="mt-1 text-[10px] font-bold">0-3 MONTHS</div>
			</div>

			<!-- Phase 2: Build & Launch (3-9 months) -->
			<div class="absolute top-[15%] left-[30%] flex flex-col items-start group cursor-pointer z-10 max-w-[180px]">
				<div class="flex items-center gap-2 mb-2">
					<div class="w-3 h-3 bg-black rounded-full"></div>
					<span class="font-bold text-[11px]">BUILD & LAUNCH</span>
				</div>
				<div class="text-[9px] text-muted leading-relaxed">
					Product development<br/>
					Team building<br/>
					Initial customers
				</div>
				<div class="mt-1 text-[10px] font-bold">3-9 MONTHS</div>
			</div>

			<!-- Phase 3: Growth & Optimization (9-15 months) -->
			<div class="absolute top-[55%] left-[50%] flex flex-col items-start group cursor-pointer z-10 max-w-[180px]">
				<div class="flex items-center gap-2 mb-2">
					<div class="w-3 h-3 bg-black rounded-full"></div>
					<span class="font-bold text-[11px]">GROWTH & OPTIMIZATION</span>
				</div>
				<div class="text-[9px] text-muted leading-relaxed">
					Product-market fit<br/>
					Scaling operations<br/>
					Revenue growth
				</div>
				<div class="mt-1 text-[10px] font-bold">9-15 MONTHS</div>
			</div>

			<!-- Phase 4: Scale & Fundraise (15-18 months) -->
			<div class="absolute top-[55%] right-[8%] flex flex-col items-start group cursor-pointer z-10 max-w-[180px]">
				<div class="flex items-center gap-2 mb-2">
					<div class="w-3 h-3 bg-accent rounded-full shadow-[0_0_0_4px_rgba(255,68,0,0.2)]"></div>
					<span class="font-bold text-[11px] text-accent">SCALE & FUNDRAISE</span>
				</div>
				<div class="text-[9px] text-muted leading-relaxed">
					Series A preparation<br/>
					Investor introductions<br/>
					Strategic partnerships
				</div>
				<div class="mt-1 text-[10px] font-bold text-accent">15-18 MONTHS</div>
			</div>

			<!-- Connecting arrows -->
			<svg class="absolute inset-0 w-full h-full pointer-events-none" xmlns="http://www.w3.org/2000/svg">
				<defs>
					<marker id="arrowhead" markerWidth="10" markerHeight="10" refX="9" refY="3" orient="auto">
						<polygon points="0 0, 10 3, 0 6" fill="rgba(0,0,0,0.3)" />
					</marker>
				</defs>
				<path d="M 180 180 Q 280 180 320 180" stroke="rgba(0,0,0,0.2)" stroke-width="1.5" fill="none" marker-end="url(#arrowhead)" stroke-dasharray="4,4"/>
				<path d="M 480 180 Q 580 280 640 320" stroke="rgba(0,0,0,0.2)" stroke-width="1.5" fill="none" marker-end="url(#arrowhead)" stroke-dasharray="4,4"/>
				<path d="M 780 320 Q 880 320 920 320" stroke="rgba(255,68,0,0.3)" stroke-width="2" fill="none" marker-end="url(#arrowhead)"/>
			</svg>
		</div>
	</div>
</section>
