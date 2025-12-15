<section class="py-24 bg-white border-t border-gray-200 font-sans">
    <div class="max-w-7xl mx-auto px-4 text-center mb-16">
        <span class="text-[10px] font-bold text-gray-500 uppercase tracking-widest border border-gray-200 px-3 py-1.5 rounded-full bg-gray-50">Social Strategy Academy</span>
        <h2 class="mt-8 text-5xl md:text-6xl font-serif-display text-gray-900">Master AI-powered <br/> social strategy</h2>
        <p class="mt-6 text-gray-600 max-w-2xl mx-auto">Learn from leading social media managers how to leverage AI agents to scale your content, increase engagement, and drive real business results.</p>
        <div class="mt-8">
            <a href="#" class="inline-flex items-center justify-center px-6 py-3 border border-transparent text-sm font-bold rounded bg-gray-900 text-white hover:bg-gray-800 transition-colors">
                Explore the Academy ->
            </a>
        </div>
    </div>

    <!-- Video Grid (Mockup) -->
    <div class="max-w-7xl mx-auto px-4">
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
            <div class="aspect-video bg-gray-200 rounded-lg overflow-hidden relative group cursor-pointer">
                <img src="/generated/image-marketing-professional-presenting-at-a-m-1765838856024-0.webp" alt="Video Thumbnail" class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-300" />
                <div class="absolute inset-0 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black/20">
                    <div class="w-10 h-10 bg-white rounded-full flex items-center justify-center">
                        <svg class="w-4 h-4 ml-0.5" fill="currentColor" viewBox="0 0 24 24"><path d="M8 5v14l11-7z"/></svg>
                    </div>
                </div>
            </div>
            <div class="aspect-video bg-gray-200 rounded-lg overflow-hidden relative group cursor-pointer">
                <img src="/generated/image-close-up-of-hands-typing-on-laptop-with--1765838858515-1.webp" alt="Video Thumbnail" class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-300" />
                <div class="absolute inset-0 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black/20">
                    <div class="w-10 h-10 bg-white rounded-full flex items-center justify-center">
                        <svg class="w-4 h-4 ml-0.5" fill="currentColor" viewBox="0 0 24 24"><path d="M8 5v14l11-7z"/></svg>
                    </div>
                </div>
            </div>
            {#each Array(6) as _, i}
            <div class="aspect-video bg-gray-200 rounded-lg overflow-hidden relative group cursor-pointer">
                <img src={`https://placehold.co/400x225/333/fff?text=Video+${i+3}`} alt="Video Thumbnail" class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-300" />
                <div class="absolute inset-0 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black/20">
                    <div class="w-10 h-10 bg-white rounded-full flex items-center justify-center">
                        <svg class="w-4 h-4 ml-0.5" fill="currentColor" viewBox="0 0 24 24"><path d="M8 5v14l11-7z"/></svg>
                    </div>
                </div>
            </div>
            {/each}
        </div>
        
        <!-- Quote -->
        <div class="mt-12 flex flex-col md:flex-row items-center gap-8 max-w-5xl mx-auto">
            <div class="w-24 h-24 md:w-32 md:h-32 rounded-full overflow-hidden flex-shrink-0 border-2 border-gray-100">
                <img src="/generated/image-friendly-marketing-manager-smiling-at-ca-1765838861076-2.webp" alt="User" class="w-full h-full object-cover" />
            </div>
            <div class="flex-1 text-center md:text-left">
                <blockquote class="text-2xl md:text-3xl font-serif-display leading-tight" style="color: oklch(0.696 0.17 162.48)">
                    "The academy completely changed how I think about social strategy. Now our AI agents handle the execution flawlessly."
                </blockquote>
                <div class="mt-4 text-xs font-bold uppercase tracking-widest text-gray-400">
                    Alex Rivera <br/>
                    <span class="text-gray-300">Social Media Manager, Glossier</span>
                </div>
            </div>
        </div>
    </div>
</section>
