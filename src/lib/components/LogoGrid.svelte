<script>
    const logos = [
        { name: 'Glossier', hasCaseStudy: false },
        { name: 'Allbirds', hasCaseStudy: true, caseStudyText: 'CASE STUDY' },
        { name: 'Warby Parker', hasCaseStudy: false },
        { name: 'Casper', hasCaseStudy: true, icon: true, caseStudyText: 'CASE STUDY' },
        { name: 'Away', hasCaseStudy: true, caseStudyText: 'CASE STUDY' },
        { name: 'Bombas', hasCaseStudy: false },
        { name: 'Outdoor Voices', hasCaseStudy: false },
        { name: 'Parachute', hasCaseStudy: false, icon: true },
        { name: 'Brooklinen', hasCaseStudy: false },
        { name: 'Hims & Hers', hasCaseStudy: false },
        { name: 'Ritual', hasCaseStudy: false },
        { name: 'Koio', hasCaseStudy: false, icon: true },
        { name: 'Everlane', hasCaseStudy: false, icon: true },
        { name: 'Rothy\'s', hasCaseStudy: false, icon: true },
        { name: 'Cotopaxi', hasCaseStudy: false }
    ];
</script>

<section class="py-12 bg-white border-b border-gray-200 font-sans">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <p class="text-center text-[10px] uppercase tracking-widest font-bold mb-8" style="color: oklch(0.696 0.17 162.48)">
            TRUSTED BY LEADING DTC BRANDS TO SCALE THEIR SOCIAL PRESENCE
        </p>

        <div class="grid grid-cols-2 md:grid-cols-5 gap-0 border-t border-l border-gray-200">
            {#each logos as logo}
                <div class="flex items-center justify-center p-6 border-r border-b border-gray-200 h-24 relative group">
                    <!-- Logo Placeholder -->
                    <span class="text-lg md:text-xl font-bold text-gray-400 group-hover:text-gray-900 transition-colors flex items-center gap-2">
                        {#if logo.icon}
                        <!-- Generic Icon for some -->
                        <div class="w-6 h-6 bg-gray-300 rounded-sm"></div>
                        {/if}
                        {logo.name}
                    </span>

                    {#if logo.hasCaseStudy}
                        <a href="#" class="absolute top-2 right-2 text-[8px] font-bold text-pink-600 bg-pink-50 px-1.5 py-0.5 rounded border border-pink-100 hover:bg-pink-100 flex items-center transition-colors">
                            {logo.caseStudyText} 
                            <svg class="w-2 h-2 ml-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                        </a>
                    {/if}
                </div>
            {/each}
        </div>
    </div>
</section>
