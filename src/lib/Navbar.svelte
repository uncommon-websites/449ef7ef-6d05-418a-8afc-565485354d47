<script lang="ts">
  import Button from './Button.svelte';
  
  let isMenuOpen = false;
</script>

<nav class="fixed top-0 left-0 right-0 z-50 bg-white/90 backdrop-blur-sm border-b border-gray-200/50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-20">
      <!-- Logo -->
      <div class="flex-shrink-0 flex items-center">
        <a href="/" class="flex items-center gap-2">
          <!-- Tilt Logo Icon -->
          <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect width="32" height="32" rx="8" fill="#191817"/>
            <path d="M16 8L22 14L16 20L10 14L16 8Z" fill="#FF5D2A"/>
            <circle cx="16" cy="14" r="2" fill="white"/>
          </svg>
          <span class="font-bold text-2xl tracking-tight">Tilt</span>
        </a>
      </div>

      <!-- Desktop Navigation -->
      <div class="hidden md:flex items-center space-x-8">
        <a href="#" class="text-sm font-medium hover:text-orange-brand transition-colors">Shop Live</a>
        <a href="#" class="text-sm font-medium hover:text-orange-brand transition-colors">How It Works</a>
        <a href="#" class="text-sm font-medium hover:text-orange-brand transition-colors">Sell on Tilt</a>
      </div>

      <!-- Right Side -->
      <div class="hidden md:flex items-center space-x-6">
        <a href="#" class="text-sm font-medium hover:text-orange-brand transition-colors">Support</a>
        <Button href="#" className="!py-2 !px-4 !text-sm">Download App</Button>
      </div>

      <!-- Mobile menu button -->
      <div class="md:hidden flex items-center">
        <button on:click={() => isMenuOpen = !isMenuOpen} class="text-gray-600 hover:text-gray-900 focus:outline-none">
          <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
          </svg>
        </button>
      </div>
    </div>
  </div>
</nav>
