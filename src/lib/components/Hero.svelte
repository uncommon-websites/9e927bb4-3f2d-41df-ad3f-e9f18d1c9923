<script>
    // Hero Component
</script>

<section class="pt-32 pb-16 md:pt-40 md:pb-24 bg-gray-50 relative overflow-hidden font-sans">
    <!-- Grid Background Pattern -->
    <div class="absolute inset-0 z-0 opacity-[0.4]" 
         style="background-image: linear-gradient(#e5e7eb 1px, transparent 1px), linear-gradient(90deg, #e5e7eb 1px, transparent 1px); background-size: 40px 40px;">
    </div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 flex flex-col items-center text-center">
        
        <!-- Headline -->
        <h1 class="text-5xl md:text-7xl lg:text-8xl font-serif-display text-gray-900 leading-[1.1] tracking-tight mb-6 max-w-5xl mx-auto">
            Social strategy <br class="hidden md:block" />
            that runs 
            <span class="inline-flex items-center align-middle mx-1 md:mx-2 relative -top-1 md:-top-2">
                <svg width="60" height="60" viewBox="0 0 100 100" class="w-10 h-10 md:w-16 md:h-16 animate-spin-slow" fill="currentColor" style="color: oklch(0.696 0.17 162.48)">
                    <!-- Stylized Asterisk/Flower -->
                    <path d="M50 0 L60 35 L95 25 L70 50 L95 75 L60 65 L50 100 L40 65 L5 75 L30 50 L5 25 L40 35 Z" />
                </svg>
            </span>
            itself
        </h1>

        <!-- Subheadline -->
        <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
            Thinktank transforms social strategy into execution via AI agents that research, plan, and create content autonomously.
        </p>

        <!-- CTA -->
        <div class="mb-16">
            <a href="#" class="inline-flex items-center justify-center px-8 py-4 border border-transparent text-base font-medium rounded-full text-white bg-gray-900 hover:bg-gray-800 transition-all shadow-lg hover:shadow-xl transform hover:-translate-y-0.5">
                Get Started Free
                <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
            </a>
        </div>

        <!-- Dashboard Preview -->
        <div class="w-full max-w-5xl mx-auto rounded-lg overflow-hidden shadow-2xl bg-white border border-gray-200 aspect-video relative">
            <!-- Browser Chrome -->
            <div class="bg-gray-100 border-b border-gray-200 px-4 py-3 flex items-center gap-2">
                <div class="flex gap-1.5">
                    <div class="w-3 h-3 rounded-full bg-red-400"></div>
                    <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
                    <div class="w-3 h-3 rounded-full bg-green-400"></div>
                </div>
                <div class="flex-1 bg-white rounded px-3 py-1 text-xs text-gray-500 ml-2">
                    app.thinktank.ai/dashboard
                </div>
            </div>

            <!-- Dashboard Content -->
            <div class="p-8 bg-gradient-to-br from-gray-50 to-white h-full">
                <div class="grid grid-cols-3 gap-4 mb-6">
                    <div class="bg-white rounded-lg p-4 shadow-sm border border-gray-100">
                        <div class="text-xs text-gray-500 uppercase font-bold mb-1">Posts Scheduled</div>
                        <div class="text-3xl font-bold text-gray-900">127</div>
                        <div class="text-xs text-green-600 font-medium mt-1">+23% this week</div>
                    </div>
                    <div class="bg-white rounded-lg p-4 shadow-sm border border-gray-100">
                        <div class="text-xs text-gray-500 uppercase font-bold mb-1">Engagement Rate</div>
                        <div class="text-3xl font-bold text-gray-900">8.4%</div>
                        <div class="text-xs text-green-600 font-medium mt-1">+2.1% this week</div>
                    </div>
                    <div class="bg-white rounded-lg p-4 shadow-sm border border-gray-100">
                        <div class="text-xs text-gray-500 uppercase font-bold mb-1">AI Agents Active</div>
                        <div class="text-3xl font-bold text-gray-900">5</div>
                        <div class="text-xs text-gray-500 font-medium mt-1">Running 24/7</div>
                    </div>
                </div>
                
                <!-- Content Preview Cards -->
                <div class="space-y-3">
                    <div class="bg-white rounded-lg p-3 shadow-sm border border-gray-100 flex items-center gap-3">
                        <div class="w-12 h-12 rounded bg-blue-100 flex-shrink-0"></div>
                        <div class="flex-1 min-w-0">
                            <div class="text-sm font-medium text-gray-900 truncate">LinkedIn post about AI trends...</div>
                            <div class="text-xs text-gray-500">Scheduled for tomorrow at 9:00 AM</div>
                        </div>
                        <div class="text-xs font-bold text-green-600 bg-green-50 px-2 py-1 rounded">Ready</div>
                    </div>
                    <div class="bg-white rounded-lg p-3 shadow-sm border border-gray-100 flex items-center gap-3">
                        <div class="w-12 h-12 rounded bg-purple-100 flex-shrink-0"></div>
                        <div class="flex-1 min-w-0">
                            <div class="text-sm font-medium text-gray-900 truncate">Twitter thread on social strategy...</div>
                            <div class="text-xs text-gray-500">Agent is researching and drafting</div>
                        </div>
                        <div class="text-xs font-bold text-blue-600 bg-blue-50 px-2 py-1 rounded">In Progress</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
