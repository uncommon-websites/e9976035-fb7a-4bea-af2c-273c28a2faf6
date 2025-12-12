<script lang="ts">
  // Hero Section
</script>

<section class="pt-32 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto flex flex-col items-center text-center">
  <h1 class="text-5xl md:text-7xl font-bold tracking-tight text-gray-900 max-w-4xl mb-8 leading-[1.1]">
    Transform complex workflows into <span class="text-gray-900 bg-gray-100 px-2 rounded">simple visual processes</span>
  </h1>

  <p class="text-xl text-gray-600 max-w-2xl mb-12">
    Stop wasting weeks on unfocused customer interviews. Wilber's intelligent automation and intuitive drag-and-drop interface helps founders validate ideas faster.
  </p>

  <div class="flex flex-col sm:flex-row gap-4 mb-16">
    <button class="bg-gray-900 text-white px-8 py-3 rounded-full text-lg font-medium hover:bg-gray-800 transition-colors">
      Get started free
    </button>
    <button class="bg-white text-gray-900 border border-gray-200 px-8 py-3 rounded-full text-lg font-medium hover:bg-gray-50 transition-colors flex items-center gap-2">
      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-play-circle"><circle cx="12" cy="12" r="10"/><polygon points="10 8 16 12 10 16 10 8"/></svg>
      See how it works
    </button>
  </div>

  <!-- Hero Image Placeholder (App Interface) -->
  <div class="w-full max-w-5xl bg-white rounded-xl shadow-2xl border border-gray-200 overflow-hidden relative aspect-[16/10] text-left">
    <!-- Fake Browser Header -->
    <div class="bg-gray-50 border-b border-gray-200 p-3 flex items-center gap-2">
      <div class="flex gap-1.5">
        <div class="w-3 h-3 rounded-full bg-red-400"></div>
        <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
        <div class="w-3 h-3 rounded-full bg-green-400"></div>
      </div>
      <div class="mx-auto text-xs text-gray-400 font-medium">Customer Interview Workflow</div>
    </div>
    
    <!-- App Content -->
    <div class="flex h-full">
      <!-- Sidebar -->
      <div class="w-64 border-r border-gray-100 bg-gray-50/50 p-4 hidden md:block">
        <div class="space-y-4">
          <div class="h-4 w-24 bg-gray-200 rounded"></div>
          <div class="space-y-2">
             <div class="h-8 w-full bg-gray-900 text-white text-xs flex items-center px-3 rounded-lg shadow-sm font-medium">Workflows</div>
             <div class="h-8 w-full bg-transparent text-xs flex items-center px-3 rounded-lg text-gray-600">Templates</div>
             <div class="h-8 w-full bg-transparent text-xs flex items-center px-3 rounded-lg text-gray-600">Insights</div>
          </div>
        </div>
      </div>
      
      <!-- Main Content - Visual Workflow -->
      <div class="flex-1 p-8 bg-gradient-to-br from-gray-50 to-white">
        <div class="max-w-3xl mx-auto">
           <h2 class="text-2xl font-bold mb-6">Customer Interview Workflow</h2>
           
           <!-- Visual Workflow Diagram -->
           <div class="space-y-4">
             <!-- Step 1 -->
             <div class="flex items-center gap-4">
               <div class="w-12 h-12 rounded-lg bg-gray-900 text-white flex items-center justify-center font-bold shrink-0">1</div>
               <div class="flex-1 p-4 bg-white border-2 border-gray-200 rounded-lg">
                 <div class="font-medium text-sm">Schedule Interview</div>
                 <div class="text-xs text-gray-500 mt-1">Auto-send calendar invite</div>
               </div>
             </div>
             
             <!-- Arrow -->
             <div class="flex justify-center">
               <svg class="w-6 h-6 text-gray-300" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                 <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3" />
               </svg>
             </div>
             
             <!-- Step 2 -->
             <div class="flex items-center gap-4">
               <div class="w-12 h-12 rounded-lg bg-gray-900 text-white flex items-center justify-center font-bold shrink-0">2</div>
               <div class="flex-1 p-4 bg-white border-2 border-gray-200 rounded-lg">
                 <div class="font-medium text-sm">Conduct & Record</div>
                 <div class="text-xs text-gray-500 mt-1">AI captures key insights</div>
               </div>
             </div>
             
             <!-- Arrow -->
             <div class="flex justify-center">
               <svg class="w-6 h-6 text-gray-300" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                 <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3" />
               </svg>
             </div>
             
             <!-- Step 3 -->
             <div class="flex items-center gap-4">
               <div class="w-12 h-12 rounded-lg bg-gray-900 text-white flex items-center justify-center font-bold shrink-0">3</div>
               <div class="flex-1 p-4 bg-white border-2 border-gray-200 rounded-lg">
                 <div class="font-medium text-sm">Update CRM</div>
                 <div class="text-xs text-gray-500 mt-1">Sync to Salesforce automatically</div>
               </div>
             </div>
           </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Trusted By -->
  <div class="mt-20 relative w-full max-w-5xl">
    <p class="text-sm text-gray-500 mb-6 text-left ml-4">Trusted by founders and teams at</p>
    <div class="flex flex-wrap justify-between items-center gap-8 opacity-50 grayscale">
       <span class="font-bold text-xl">Y Combinator</span>
       <span class="font-bold text-xl">Techstars</span>
       <span class="font-bold text-xl">500 Global</span>
       <span class="font-bold text-xl">Sequoia</span>
       <span class="font-bold text-xl">a16z</span>
       <span class="font-bold text-xl">Stripe</span>
       <span class="font-bold text-xl">Notion</span>
       <span class="font-bold text-xl">Linear</span>
    </div>
    
    <!-- Handwritten Note -->
    <div class="absolute -bottom-12 -left-4 hidden lg:block">
      <div class="relative">
        <svg class="absolute -top-4 -right-8 w-12 h-12 text-gray-300 transform rotate-12" viewBox="0 0 100 100" fill="none" stroke="currentColor">
           <path d="M10,80 Q50,10 90,80" stroke-width="2" />
           <path d="M90,80 L80,70 M90,80 L85,90" stroke-width="2" />
        </svg>
        <p class="font-serif italic text-gray-400 text-sm whitespace-nowrap transform -rotate-6">
          * Used by 100+ early-stage startups
        </p>
      </div>
    </div>
  </div>
</section>
