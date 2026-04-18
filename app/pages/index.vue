<template>
  <div class="min-h-screen bg-[#0E1012] flex items-center justify-center px-[40px] py-20 font-sans">
    
    <div class="flex flex-col lg:flex-row flex-nowrap justify-center gap-[24px] w-full max-w-[1300px]">
      
      <div class="bg-[#1C1E21] rounded-[12px] h-[536px] w-full lg:w-[400px] flex flex-col overflow-hidden shadow-2xl transition-all hover:bo/50 hover:-translate-y-2 group">
        <div class="w-full h-64 flex items-center justify-center bg-[#15171A] overflow-hidden">
          <img 
            src="/card-1.png" 
            alt="Contract-First Development" 
            class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105"
          />
        </div>
        
        <div class="p-8 space-y-5 text-[#55585D] bg-[#55585D]">
          <h3 class="text-[28px] font-medium tracking-tight text-white">
            Contract-First Development
          </h3>
          <p class="text-[15px] text-[#E3E4E8] leading-relaxed">
            gRPC APIs enable efficient, type-safe communication; protobufs ensure consistency.
          </p>
          <ul class="space-y-2 text-[15px] text-white">
            <li class="flex items-baseline gap-3">
              <span class=" text-[20px] mt-1">‣</span>
              <span>Strongly-typed schemas</span>
            </li>
            <li class="flex items-baseline gap-3">
              <span class=" text-[20px] mt-1">‣</span>
              <span>Automated code generation</span>
            </li>
            <li class="flex items-baseline gap-3">
              <span class=" text-[20px] mt-1">‣</span>
              <span>Version control built-in</span>
            </li>
          </ul>
        </div>
      </div>

      <div class="bg-[#1C1E21] rounded-[12px] h-[536px] w-full lg:w-[400px] flex flex-col overflow-hidden shadow-2xl transition-all hover:bo/50 hover:-translate-y-2 group">
        <div class="w-full h-64 flex items-center justify-center bg-[#15171A] overflow-hidden">
          <img 
            src="/card-2.png" 
            alt="Security by Design" 
            class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105"
          />
        </div>
         
        <div class="p-8 space-y-5 text-[#55585D] bg-[#55585D]">
          <h3 class="text-2xl font-semibold tracking-tight text-white">
            Security by Design
          </h3>
          <p class="text-[15px] text-[#E3E4E8] leading-relaxed">
            Zero-trust architecture with encryption. Every request authenticated and validated.
          </p>
          <ul class="space-y-2 text-[15px] text-white">
            <li class="flex items-baseline gap-3">
              <span class=" text-[20px] mt-1">‣</span>
              <span>mTLS encryption standard</span>
            </li>
            <li class="flex items-baseline gap-3">
              <span class=" text-[20px] mt-1">‣</span>
              <span>Real-time threat detection</span>
            </li>
            <li class="flex items-baseline gap-3">
              <span class=" text-[20px] mt-1">‣</span>
              <span>Real-time threat detection</span>
            </li>
          </ul>
        </div>
      </div>

      <div class="bg-[#1C1E21] rounded-[12px] h-[536px] w-full lg:w-[400px] flex flex-col overflow-hidden shadow-2xl transition-all hover:bo/50 hover:-translate-y-2 group">
        <div class="w-full h-64 flex items-center justify-center bg-[#15171A] overflow-hidden">
          <img 
            src="/card-3.png" 
            alt="Global Scale" 
            class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105"
          />
        </div>
        
        <div class="p-8 space-y-5 text-[#55585D] bg-[#55585D]">
          <h3 class="text-2xl font-semibold tracking-tight text-white">
            Global Scale
          </h3>
          <p class="text-[15px] text-[#E3E4E8] leading-relaxed">
            Microservices span 6 continents. Auto-scaling handles billions of requests.
          </p>
          <ul class="space-y-2 text-[15px] text-white">
            <li class="flex items-baseline gap-3">
              <span class="text-[20px] mt-1">‣</span>
              <span>Multi-region redundancy</span>
            </li>
            <li class="flex items-baseline gap-3">
              <span class=" text-[20px] mt-1">‣</span>
              <span>Kubernetes orchestration</span>
            </li>
            <li class="flex items-baseline gap-3">
              <span class=" text-[20px] mt-1">‣</span>
              <span>Edge computing enabled</span>
            </li>
          </ul>
        </div>
      </div>

    </div>
  </div>
</template>