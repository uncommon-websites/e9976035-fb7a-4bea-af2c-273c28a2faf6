<script lang="ts">
  // Meeting Notes Section
</script>

<section class="py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
  <div class="mb-4">
    <span class="text-green-600 font-medium">Visual Workflow Builder</span>
  </div>
  
  <h2 class="text-4xl font-bold mb-4">Build complex workflows with simple drag-and-drop</h2>
  
  <div class="flex gap-4 text-sm text-gray-500 mb-12 items-center">
    <span class="font-medium text-gray-900">Replaces:</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-purple-600"></div> Zapier</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-orange-500"></div> Make</span>
    <span class="flex items-center gap-1.5"><div class="w-3 h-3 rounded-full bg-blue-600"></div> n8n</span>
  </div>

  <div class="grid md:grid-cols-2 gap-16 mb-20">
    <div>
      <h3 class="font-bold text-lg mb-4">Why Wilber?</h3>
      <p class="text-gray-600 mb-4 leading-relaxed">
        Most workflow tools are either too simple or overwhelmingly complex. If basic automation is all you need, any tool will work. Many are even cheaper.
      </p>
      <p class="text-gray-600 leading-relaxed">
        But if you want to validate ideas faster and extract real insights from customer interviews, you need Wilber. A platform that understands your process and automates your busy work intelligently.
      </p>
    </div>
    
    <div class="space-y-8">
      <!-- Testimonial 1 -->
      <div class="bg-gray-50 p-6 rounded-2xl relative">
        <div class="flex text-orange-400 mb-2">★★★★★</div>
        <div class="flex items-center gap-3 mb-3">
          <div class="w-8 h-8 bg-gray-300 rounded-full"></div>
          <div>
            <div class="font-bold text-sm">Sarah Chen</div>
            <div class="text-xs text-gray-500">Founder • TechFlow</div>
          </div>
        </div>
        <p class="text-sm text-gray-700">
          Wilber cut our customer interview process from 3 weeks to 3 days. The AI-powered insights help us identify patterns we would have missed manually. It's transformed how we validate ideas.
        </p>
        <div class="absolute top-4 right-4 w-6 h-6 bg-gray-900 rounded-md"></div>
      </div>

       <!-- Testimonial 2 -->
       <div class="bg-gray-50 p-6 rounded-2xl relative">
        <div class="flex text-orange-400 mb-2">★★★★★</div>
        <div class="flex items-center gap-3 mb-3">
          <div class="w-8 h-8 bg-gray-300 rounded-full"></div>
          <div>
            <div class="font-bold text-sm">Marcus Rodriguez</div>
            <div class="text-xs text-gray-500">Co-founder • GrowthLab</div>
          </div>
        </div>
        <p class="text-sm text-gray-700">
          The drag-and-drop interface makes complex workflows feel simple. We automated our entire customer onboarding process in an afternoon. Our CRM stays updated automatically now. Game changer.
        </p>
        <div class="absolute top-4 right-4 w-6 h-6 bg-gray-700 rounded-md"></div>
      </div>
    </div>
  </div>

  <div class="max-w-3xl mb-12">
    <h3 class="font-bold text-lg mb-4">Intelligent Automation & Insights</h3>
    <p class="text-gray-600 mb-4 leading-relaxed">
      When customer interviews go unstructured, insights get lost. Founders waste weeks conducting interviews that don't move the needle. But every conversation should validate or invalidate your assumptions. Generic automation tools miss the nuances. Wilber understands context and extracts actionable insights automatically.
    </p>
    <p class="text-gray-600 leading-relaxed">
      The problem with most workflow tools is they don't understand your business context. We solve this with AI-powered relationship intelligence that learns from every interaction.
    </p>
  </div>

  <!-- Large Interface Image -->
  <div class="w-full bg-gray-900 rounded-2xl overflow-hidden shadow-2xl border border-gray-800 pt-2 md:pt-8 px-2 md:px-8 pb-0">
    <!-- Feature Tabs (Dark Header) -->
    <div class="flex justify-center gap-8 mb-6 text-sm font-medium text-gray-400">
      <div class="flex items-center gap-2 hover:text-white cursor-pointer transition-colors">
        <div class="w-4 h-4 rounded-full border border-gray-600"></div>
        Drag & Drop
      </div>
      <div class="flex items-center gap-2 text-white cursor-pointer">
        <div class="w-4 h-4 rounded-full bg-white text-gray-900 flex items-center justify-center text-[10px]">✨</div>
        AI Insights
      </div>
      <div class="flex items-center gap-2 hover:text-white cursor-pointer transition-colors">
        <div class="w-4 h-4 rounded-full border border-gray-600"></div>
        Auto-sync CRM
      </div>
    </div>

    <!-- App Window -->
    <div class="bg-white rounded-t-lg overflow-hidden h-[500px] flex flex-col shadow-2xl relative">
       <!-- Header -->
       <div class="border-b border-gray-100 p-4 flex justify-between items-center bg-white z-10">
         <div class="flex items-center gap-3">
           <div class="w-8 h-8 bg-gray-900 rounded-lg flex items-center justify-center text-white text-lg">⚡</div>
           <div class="font-bold text-gray-900">Customer Interview Analysis</div>
         </div>
         <div class="flex items-center gap-3">
           <div class="flex -space-x-2">
             <div class="w-6 h-6 rounded-full bg-gray-200 border-2 border-white"></div>
             <div class="w-6 h-6 rounded-full bg-gray-300 border-2 border-white"></div>
             <div class="w-6 h-6 rounded-full bg-gray-400 border-2 border-white"></div>
           </div>
           <div class="h-4 w-px bg-gray-200"></div>
           <button class="text-xs font-medium text-gray-500">Export</button>
           <button class="bg-gray-900 text-white px-3 py-1.5 rounded-md text-xs font-medium">Share</button>
         </div>
       </div>

       <!-- Content Area -->
       <div class="flex-1 overflow-y-auto bg-white p-6 md:p-8">
         <!-- Metadata -->
         <div class="grid grid-cols-[100px_1fr] gap-y-4 text-sm mb-8">
           <div class="text-gray-500">Workflow</div>
           <div class="text-gray-900">Interview → Insights → CRM Update</div>
           
           <div class="text-gray-500">Interviews</div>
           <div class="flex items-center gap-2">
             <div class="w-1 h-4 bg-gray-900 rounded-full"></div>
             <span class="font-medium">15 completed this week</span>
           </div>
           
           <div class="text-gray-500">Status</div>
           <div class="flex items-center gap-2">
             <div class="w-6 h-6 rounded-full bg-green-100 flex items-center justify-center text-green-600 text-xs">✓</div>
             <span class="text-xs text-gray-700">All synced to Salesforce</span>
           </div>
         </div>
         
         <!-- Tabs -->
         <div class="flex gap-6 border-b border-gray-100 mb-6">
           <button class="pb-2 border-b-2 border-black font-medium text-sm">Key Insights</button>
           <button class="pb-2 border-b-2 border-transparent text-gray-500 font-medium text-sm hover:text-gray-800">Patterns</button>
         </div>
         
         <!-- Summary Content -->
         <div class="space-y-6 max-w-2xl">
            <div>
              <div class="flex items-center gap-2 mb-2">
                <span class="text-xs font-bold uppercase tracking-wider text-gray-400">Customer Pain Points</span>
              </div>
              <h4 class="font-bold text-gray-900 mb-2">Top Validated Problems</h4>
              <ul class="list-disc pl-5 text-sm text-gray-600 space-y-2 marker:text-gray-300">
                <li>87% of founders report spending 2-3 weeks on unfocused customer interviews before finding product-market fit signals</li>
                <li>Manual CRM updates take 4-6 hours per week on average, with 40% of insights never making it into the system</li>
                <li>Workflow automation tools are either too complex (requiring developers) or too simple (lacking AI intelligence)</li>
              </ul>
            </div>
            
             <div>
              <h4 class="font-bold text-gray-900 mb-2">Feature Requests</h4>
              <ul class="list-disc pl-5 text-sm text-gray-600 space-y-2 marker:text-gray-300">
                <li>Visual workflow builder with drag-and-drop interface (mentioned by 12/15 interviewees)</li>
                <li>AI-powered pattern recognition across multiple interviews (9/15 interviewees)</li>
              </ul>
            </div>
         </div>
       </div>
    </div>
  </div>

  <!-- Integration Icons -->
  <div class="mt-12 text-center">
    <div class="flex flex-wrap justify-center gap-8 text-3xl text-gray-300 mb-4 select-none">
      <span class="font-bold">Salesforce</span>
      <span class="font-bold">HubSpot</span>
      <span class="font-bold">Pipedrive</span>
      <span class="font-bold">Notion</span>
      <span class="font-bold">Airtable</span>
      <span class="font-bold">Slack</span>
    </div>
    <p class="text-xs text-gray-400">
      Connects with <span class="underline decoration-dotted">50+ business tools</span> to keep your data in sync automatically.
    </p>
  </div>
</section>
