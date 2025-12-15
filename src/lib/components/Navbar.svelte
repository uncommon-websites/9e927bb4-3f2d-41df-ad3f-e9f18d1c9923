<script>
  import { onMount } from 'svelte';
  
  let isScrolled = false;

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 0;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<div class="fixed top-0 w-full z-50 flex flex-col font-sans">
  <!-- Top Banner -->
  <div class="bg-[#F3F4F6] border-b border-gray-200 py-2 px-4 text-center text-[10px] sm:text-xs font-medium tracking-wide text-gray-900">
    <span class="mr-1">Transform your social strategy with AI agents - Join the waitlist</span>
    <a href="#" class="inline-flex items-center hover:underline font-bold ml-1">
      GET EARLY ACCESS 
      <svg class="w-3 h-3 ml-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
    </a>
  </div>

  <!-- Main Nav -->
  <nav class="bg-white/95 backdrop-blur-sm border-b border-gray-100 transition-all duration-200 {isScrolled ? 'py-3' : 'py-4'}">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex items-center justify-between">
      <!-- Logo -->
      <div class="flex items-center">
        <a href="/" class="flex items-center gap-2">
          <svg width="38" height="35" viewBox="0 0 75 70" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M0.357422 0H57.5526C66.9818 0 74.6257 7.64392 74.6257 17.0732C74.6257 26.5024 66.9818 34.1463 57.5526 34.1463H17.4306C16.9591 34.1463 16.5769 34.5285 16.5769 35C16.5769 35.4715 16.9591 35.8537 17.4306 35.8537H57.5526C66.9818 35.8537 74.6257 43.4976 74.6257 52.9268C74.6257 62.3561 66.9818 70 57.5526 70H0.357422V53.7805H57.5526C58.024 53.7805 58.4062 53.3983 58.4062 52.9268C58.4062 52.4554 58.024 52.0732 57.5526 52.0732H17.4306C8.00134 52.0732 0.357422 44.4293 0.357422 35C0.357422 25.5707 8.00135 17.9268 17.4306 17.9268H57.5526C58.024 17.9268 58.4062 17.5446 58.4062 17.0732C58.4062 16.6017 58.024 16.2195 57.5526 16.2195H0.357422V0Z" fill="black"/>
          </svg>
          <span class="text-2xl font-bold tracking-tight text-gray-900">Thinktank</span>
        </a>
        
        <!-- Desktop Links -->
        <div class="hidden md:flex items-center ml-10 space-x-8 text-sm font-medium text-gray-600">
          <a href="#" class="hover:text-gray-900">Platform</a>
          <a href="#" class="hover:text-gray-900">Use Cases</a>
          <a href="#" class="hover:text-gray-900">Resources</a>
          <a href="#" class="hover:text-gray-900">Pricing</a>
        </div>
      </div>

      <!-- Right Actions -->
      <div class="flex items-center space-x-4 sm:space-x-6">
        <a href="#" class="hidden md:block text-sm font-medium text-gray-600 hover:text-gray-900">Log In</a>
        <a href="#" class="hidden md:block text-sm font-medium text-gray-600 hover:text-gray-900">Start Free Trial</a>
        <a href="#" class="inline-flex items-center justify-center px-4 py-2 border border-transparent text-sm font-medium rounded-full text-white bg-gray-900 hover:bg-gray-800 transition-colors shadow-sm">
          Get Started
          <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
        </a>
      </div>
    </div>
  </nav>
</div>
