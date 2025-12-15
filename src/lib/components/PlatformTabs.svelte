<script>
    // No script logic needed for this static recreation yet
</script>

<section class="py-20 bg-white font-sans">
    <div class="max-w-7xl mx-auto px-4 text-center">
        <span class="text-[10px] font-bold text-gray-500 uppercase tracking-widest border border-gray-200 px-3 py-1.5 rounded-full bg-gray-50">Meet the Thinktank Platform</span>
        <h2 class="mt-8 text-5xl md:text-7xl font-serif-display text-gray-900 leading-tight">Where social <br/> strategy becomes <br/> execution</h2>
    </div>
    
    <!-- Tabbed interface image area -->
    <div class="max-w-7xl mx-auto mt-16 px-4">
        <div class="border border-gray-200 rounded-xl overflow-hidden shadow-sm bg-white grid md:grid-cols-12 min-h-[600px]">
             <div class="md:col-span-4 p-8 md:p-12 border-r border-gray-200 flex flex-col justify-center">
                 <h3 class="text-3xl font-serif-display mb-4">AI agents that understand your audience</h3>
                 <p class="text-gray-600 text-base leading-relaxed mb-8">Our AI agents analyze trending topics, competitor content, and audience engagement patterns to create a winning social strategy. They research what's working in your industry, identify content opportunities, and plan posts that resonate with your target audience across all platforms.</p>
                 <div>
                    <button class="text-sm font-bold border-b border-gray-300 pb-0.5 hover:border-gray-900 transition-colors">Learn More -></button>
                 </div>
             </div>
             <div class="md:col-span-8 bg-gray-50 p-8 md:p-12 flex items-center justify-center relative overflow-hidden">
                 <!-- Simplified UI Mockup -->
                 <div class="bg-white shadow-xl rounded-lg w-full h-full border border-gray-200 p-6 relative flex flex-col">
                    <div class="flex gap-2 mb-6 border-b border-gray-100 pb-4">
                        <div class="w-3 h-3 rounded-full bg-red-400"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
                        <div class="w-3 h-3 rounded-full bg-green-400"></div>
                        <div class="ml-auto flex gap-2">
                            <div class="h-4 w-32 bg-gray-100 rounded-full"></div>
                        </div>
                    </div>
                    
                    <div class="space-y-6">
                        <!-- Header Stats -->
                        <div class="grid grid-cols-4 gap-4">
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Posts Scheduled</div>
                                 <div class="text-xl font-bold text-gray-900">142</div>
                                 <div class="text-[10px] text-green-600 font-bold">+28%</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Engagement</div>
                                 <div class="text-xl font-bold text-gray-900">8.4%</div>
                                 <div class="text-[10px] text-green-600 font-bold">+2.1%</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Reach</div>
                                 <div class="text-xl font-bold text-gray-900">124k</div>
                                 <div class="text-[10px] text-green-600 font-bold">+15%</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Agents Active</div>
                                 <div class="text-xl font-bold text-gray-900">5</div>
                                 <div class="text-[10px] text-gray-400 font-bold">Running</div>
                             </div>
                        </div>

                        <!-- Data Table -->
                        <div class="border border-gray-100 rounded-lg overflow-hidden">
                            <div class="bg-gray-50 px-4 py-2 border-b border-gray-100 flex text-[10px] font-bold text-gray-500 uppercase tracking-wider">
                                <div class="w-2/5">Content Topic</div>
                                <div class="w-1/6 text-right">Platform</div>
                                <div class="w-1/6 text-right">Est. Reach</div>
                                <div class="w-1/6 text-right">Status</div>
                            </div>
                            <div class="divide-y divide-gray-50 text-xs">
                                 {#each [
                                     {topic: 'AI trends in marketing 2024', platform: 'LinkedIn', reach: '12k', score: '95', status: 'Scheduled'},
                                     {topic: 'Behind the scenes: product launch', platform: 'Instagram', reach: '8.5k', score: '88', status: 'Ready'},
                                     {topic: 'Customer success story thread', platform: 'Twitter', reach: '5.2k', score: '82', status: 'Drafting'},
                                     {topic: 'Industry insights carousel', platform: 'LinkedIn', reach: '9.1k', score: '91', status: 'Review'},
                                     {topic: 'Weekly tips & tricks video', platform: 'TikTok', reach: '15k', score: '87', status: 'Researching'}
                                 ] as item}
                                 <div class="px-4 py-3 flex items-center hover:bg-gray-50 transition-colors">
                                     <div class="w-2/5 font-medium text-gray-900">{item.topic}</div>
                                     <div class="w-1/6 text-right">
                                         <span class="px-1.5 py-0.5 rounded text-[10px] font-bold bg-gray-100 text-gray-700">{item.platform}</span>
                                     </div>
                                     <div class="w-1/6 text-right text-gray-600">{item.reach}</div>
                                     <div class="w-1/6 text-right">
                                         <span class="text-[10px] font-bold" style="color: oklch(0.696 0.17 162.48)">{item.status}</span>
                                     </div>
                                 </div>
                                 {/each}
                            </div>
                        </div>
                    </div>
                 </div>
             </div>
        </div>
        
        <!-- Bottom Grid of 3 items -->
        <div class="grid md:grid-cols-3 gap-0 mt-0 border-x border-b border-gray-200 divide-x divide-gray-200 bg-white">
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">1</div>
                <p class="text-xs text-gray-600 leading-relaxed">AI agents research trending topics, analyze competitor content, and identify what resonates with your audience across all platforms.</p>
            </div>
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">2</div>
                <p class="text-xs text-gray-600 leading-relaxed">Automatically plan content calendars based on optimal posting times, audience behavior, and strategic goals for each platform.</p>
            </div>
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">3</div>
                <p class="text-xs text-gray-600 leading-relaxed">Create on-brand content that matches your voice, style, and messaging guidelines while maintaining human oversight and approval.</p>
            </div>
        </div>
    </div>
</section>