<script lang="ts">
  import NavLink from './NavLink.svelte';
</script>

<nav class="fixed top-0 left-0 right-0 z-50 bg-white/80 backdrop-blur-md border-b border-gray-100">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-16">
      <!-- Left: Logo & Links -->
      <div class="flex items-center gap-8">
        <a href="/" class="flex items-center gap-2">
          <!-- Wilber Logo -->
          <svg width="32" height="39" viewBox="0 0 78 96" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M45.5105 63.889C63.2296 63.889 77.5938 49.5868 77.5938 31.9444C77.5938 14.302 63.2296 0 45.5105 0H0.59375V63.889H45.5105Z" fill="black"/>
            <path d="M0.59375 0L77.5938 95.8333H26.2605L0.59375 63.889L0.59375 0Z" fill="black"/>
            <path d="M51.4831 63.3363C49.5479 63.6992 47.5515 63.889 45.5105 63.889H0.59375V0L51.4831 63.3363Z" fill="black"/>
          </svg>
          <span class="font-bold text-xl text-gray-900">Wilber</span>
        </a>
        <div class="hidden md:flex items-center gap-6">
          <NavLink label="Features" />
          <NavLink label="Pricing" />
        </div>
      </div>

      <!-- Right: Actions -->
      <div class="flex items-center gap-4">
        <NavLink label="Login" />
        <a
          href="#"
          class="bg-gray-900 text-white px-4 py-2 rounded-full text-sm font-medium hover:bg-gray-800 transition-colors"
        >
          Get started
        </a>
      </div>
    </div>
  </div>
</nav>
