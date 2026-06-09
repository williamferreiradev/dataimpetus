<template>
  <section class="relative min-h-screen flex items-center justify-center pt-20 overflow-hidden bg-[#0A1128]">
    <!-- Background Elements -->
    <div class="absolute inset-0 z-0 overflow-hidden">
      <div class="absolute top-1/4 left-1/4 w-96 h-96 bg-[#00E0FF] rounded-full mix-blend-screen filter blur-[120px] opacity-20"></div>
      <div class="absolute bottom-1/4 right-1/4 w-[500px] h-[500px] bg-blue-600 rounded-full mix-blend-screen filter blur-[150px] opacity-20"></div>
    </div>
    
    <div class="container mx-auto px-6 relative z-10 flex flex-col items-center text-center w-full mt-10">
      <div class="inline-block border border-[#00E0FF]/30 bg-[#00E0FF]/10 text-[#00E0FF] px-4 py-1.5 rounded-full text-sm font-semibold tracking-wider mb-8 shadow-[0_0_10px_rgba(0,224,255,0.2)]">
        EXCLUSIVO PARA CERIMONIALISTAS
      </div>
      
      <h1 class="text-5xl md:text-7xl font-extrabold text-white mb-6 leading-tight max-w-4xl">
        Aumente sua <span class="text-transparent bg-clip-text bg-gradient-to-r from-[#00E0FF] to-blue-500">Credibilidade</span> e feche mais contratos.
      </h1>
      
      <p class="text-xl text-gray-400 mb-10 max-w-2xl leading-relaxed">
        Tenha um site de alta conversão rodando <strong class="text-white">24 horas por dia</strong>. Qualifique seus leads automaticamente e receba seu site pronto em até <strong class="text-[#00E0FF]">24 horas</strong>.
      </p>
      
      <div class="flex flex-col sm:flex-row gap-6 w-full justify-center">
        <a href="https://wa.me/556191256418" target="_blank" class="bg-[#00E0FF] hover:bg-[#00B3CC] text-[#0A1128] px-8 py-4 rounded-xl text-center transition-all shadow-[0_0_20px_rgba(0,224,255,0.4)] hover:shadow-[0_0_30px_rgba(0,224,255,0.6)] font-bold text-lg flex items-center justify-center gap-2">
          Garantir Meu Site Agora
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6"></path></svg>
        </a>
        <a href="#portfolio" class="bg-[#1C2A4A] hover:bg-[#25375c] text-white border border-gray-700 px-8 py-4 rounded-xl text-center transition-all font-semibold text-lg flex items-center justify-center">
          Ver Portfólio
        </a>
      </div>
      
      <!-- Trust Indicators -->
      <div class="mt-16 flex items-center gap-8 text-gray-500 text-sm font-medium">
        <div class="flex items-center gap-2">
          <svg class="w-5 h-5 text-[#00E0FF]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
          Entrega em 24h
        </div>
        <div class="flex items-center gap-2">
          <svg class="w-5 h-5 text-[#00E0FF]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
          Suporte Técnico
        </div>
        <div class="flex items-center gap-2">
          <svg class="w-5 h-5 text-[#00E0FF]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
          Hospedagem Inclusa
        </div>
      </div>
    </div>
  </section>
</template>
