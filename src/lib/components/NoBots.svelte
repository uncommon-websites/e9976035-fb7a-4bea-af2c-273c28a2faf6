<script lang="ts">
  // No Bots Section
</script>

<section class="py-24 bg-gray-50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid md:grid-cols-2 gap-16 items-center">
      <div>
        <h2 class="text-3xl font-bold mb-6">Intuitive drag-and-drop interface</h2>
        <p class="text-gray-600 mb-8">
          Complex workflows shouldn't require complex tools. With Wilber's visual interface, you can build sophisticated automations without writing a single line of code:
        </p>
        
        <ul class="space-y-4">
          {#each ['Visual workflow builder with real-time preview', 'Pre-built templates for common use cases', 'Smart suggestions based on your business context', 'One-click deployment to production'] as item}
            <li class="flex items-start gap-3">
              <div class="w-5 h-5 rounded-full bg-green-100 flex items-center justify-center mt-0.5 shrink-0">
                <svg class="w-3 h-3 text-green-600" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" />
                </svg>
              </div>
              <span class="text-gray-700 text-sm">{item}</span>
            </li>
          {/each}
        </ul>
      </div>
      
      <div class="relative">
        <!-- Workflow Canvas Mockup -->
        <div class="bg-gradient-to-br from-gray-100 to-gray-50 rounded-2xl p-8 shadow-lg">
           <div class="bg-white rounded-xl overflow-hidden shadow-2xl relative aspect-video flex items-center justify-center p-6">
              <!-- Workflow Nodes -->
              <div class="flex items-center gap-4 w-full justify-center">
                <!-- Node 1 -->
                <div class="bg-gray-900 text-white p-4 rounded-lg shadow-lg flex flex-col items-center gap-2 w-24">
                  <div class="text-2xl">📋</div>
                  <div class="text-xs font-medium text-center">Interview</div>
                </div>
                
                <!-- Arrow -->
                <svg class="w-8 h-8 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
                </svg>
                
                <!-- Node 2 -->
                <div class="bg-gray-900 text-white p-4 rounded-lg shadow-lg flex flex-col items-center gap-2 w-24">
                  <div class="text-2xl">🤖</div>
                  <div class="text-xs font-medium text-center">AI Extract</div>
                </div>
                
                <!-- Arrow -->
                <svg class="w-8 h-8 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
                </svg>
                
                <!-- Node 3 -->
                <div class="bg-gray-900 text-white p-4 rounded-lg shadow-lg flex flex-col items-center gap-2 w-24">
                  <div class="text-2xl">💼</div>
                  <div class="text-xs font-medium text-center">Update CRM</div>
                </div>
              </div>
              
              <!-- Drag indicator -->
              <div class="absolute top-4 right-4 bg-gray-100 px-3 py-1 rounded-full text-xs text-gray-600 font-medium">
                Drag to connect
              </div>
           </div>
        </div>
        <p class="text-xs text-gray-500 mt-4 text-center">
          Build workflows visually. No coding required. Changes deploy instantly.
        </p>
      </div>
    </div>
    
    <div class="mt-16 p-6 bg-green-50 rounded-xl border border-green-100">
      <p class="text-sm text-green-800">
        <span class="font-bold">The visual interface is incredibly intuitive</span>. I built our entire customer interview workflow in 20 minutes without any technical help. The AI suggestions are spot-on and save us hours every week.
      </p>
      <div class="mt-2 text-xs text-green-600 font-medium">Alex Thompson • Founder, StartupKit</div>
    </div>
  </div>
</section>
