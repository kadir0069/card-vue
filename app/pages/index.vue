<template>
  <div class="min-h-screen bg-white font-sans flex items-center justify-center">
    <div class="max-w-[1600px] mx-auto w-full p-12">
      
      <div class="grid grid-cols-1 lg:grid-cols-[1fr,auto,2fr] gap-[48px] items-center justify-items-center lg:justify-items-stretch">
        
        <div class="space-y-8 w-full max-w-md">
          <h1 class="text-[48px] font-normal leading-[1.1] tracking-tighter text-slate-900">
            <span class="block text-transparent bg-clip-text bg-gradient-to-r from-[#3878FA] to-[#A3BEF5]">Our Partnerships</span> 
            The Voices Behind Our Partnerships
          </h1>
          <p class="text-[#5E656E] text-[18px] leading-relaxed">
            Built on real-world collaboration, our partners share how TechBridge helps scale operations and automate workflows.
          </p>
          <button class="w-full sm:w-[478px] h-[56px] px-[20px] py-[10px] rounded-[100px] text-white font-medium text-lg bg-gradient-to-b from-[#7491FF] to-[#0035FF] shadow-[inset_0_5px_25px_-16px_rgba(255,255,255,0.15),inset_0_5px_10px_0_rgba(255,255,255,0.15)] hover:opacity-90 transition-all active:scale-[0.98]">
            View Client Stories
          </button>
        </div>

        <div class="hidden lg:block h-[350px] w-[1px] bg-gray-200"></div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-[24px] w-full">
          <div class="w-full max-w-[491px] h-[348px] p-[32px] rounded-[12px] bg-[#EDEFF2] flex flex-col justify-between gap-[8px] overflow-hidden justify-self-center lg:justify-self-start">
            <div>
              <span class="text-7xl text-blue-400 opacity-40 font-serif leading-none"> <img src="/quote-down.png" class=""> </span>
              <p class="text-[rgba(94, 101, 110, 1)] mt-4 leading-relaxed text-[16px] italic ">
                "Organizations across industries partner with <span class="text-[#3878FA]"> TechBridge </span> to automate workflows, improve efficiency, and build reliable AI systems."
              </p>
            </div>
            <img src="/sarah.png" alt="Sarah" class="w-14 h-14 rounded-full object-cover">
              <div>
                <h4 class="font-bold text-[#0F1824] text-[24px]">Sarah Chen</h4>
                <p class="text-sm text-slate-400 uppercase tracking-wider font-[14px]">Global Innovations Inc</p>
              </div>
          </div>

          <div class="w-full max-w-[491px] h-[348px] p-[32px] rounded-[12px] bg-[#EDEFF2] flex flex-col justify-between gap-[8px] overflow-hidden justify-self-center lg:justify-self-end">
            <div>
              <span class="text-7xl text-blue-400 opacity-40 font-serif leading-none"><img src="/quote-down.png" class=""></span>
              <p class="text-[rgba(94, 101, 110, 1)] mt-4 leading-relaxed text-[16px] italic">
                 <span class="text-[#3878FA]"> "TechBridge </span> has helped our team simplify complex workflows and bring greater efficiency to our operations."
              </p>
            </div>
              <img src="/emily.png" alt="Sarah" class="w-14 h-14 rounded-full object-cover">
              <div>
                <h4 class="font-bold text-[#0F1824] text-[24px]">Emily Watson</h4>
                <p class="text-sm text-slate-400 uppercase tracking-wider font-[14px]">Enterprise Solution Ltd</p>
              </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>