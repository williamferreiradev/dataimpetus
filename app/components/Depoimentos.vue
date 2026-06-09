<template>
  <section class="py-32 bg-[#050814] border-t border-[#1C2A4A]">
    <div class="container mx-auto px-6">
      <div class="text-center mb-16">
        <h2 class="text-3xl md:text-5xl font-bold text-white mb-4">O que dizem os clientes</h2>
        <p class="text-gray-400 max-w-2xl mx-auto text-lg">Resultados reais de quem já confiou na <strong class="text-[#00E0FF]">Data Impetus</strong>.</p>
      </div>
      
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-3xl mx-auto">
        <!-- Vídeo 1 -->
        <div class="bg-[#111A35] p-4 rounded-3xl border border-gray-800 flex justify-center shadow-2xl hover:border-[#00E0FF]/50 transition-all">
          <div class="relative w-full max-w-[315px] aspect-[9/16] rounded-2xl overflow-hidden shadow-inner bg-black">
            <iframe 
              src="https://www.youtube.com/embed/6sM_4K5nfXg?rel=0" 
              title="Avaliação Data Impetus 1" 
              class="absolute top-0 left-0 w-full h-full border-0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
              allowfullscreen>
            </iframe>
          </div>
        </div>
        
        <!-- Vídeo 2 -->
        <div class="bg-[#111A35] p-4 rounded-3xl border border-gray-800 flex justify-center shadow-2xl hover:border-[#00E0FF]/50 transition-all md:-translate-y-4 shadow-[0_0_30px_rgba(0,224,255,0.1)]">
          <div class="relative w-full max-w-[315px] aspect-[9/16] rounded-2xl overflow-hidden shadow-inner bg-black">
            <iframe 
              src="https://www.youtube.com/embed/4siSJewTGlA?rel=0" 
              title="Avaliação Data Impetus 2" 
              class="absolute top-0 left-0 w-full h-full border-0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
              allowfullscreen>
            </iframe>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
