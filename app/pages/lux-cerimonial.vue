<template>
  <div class="min-h-screen bg-[#050505] text-white selection:bg-[#B8860B]/30 font-serif">
    <!-- Header Premium -->
    <header class="absolute top-0 w-full p-8 z-50 flex justify-between items-center border-b border-gray-800/50">
      <div class="text-2xl font-bold tracking-[0.2em] uppercase">
        Lux<span class="text-[#B8860B]">.</span>
      </div>
      <button class="px-6 py-2 border border-[#B8860B] text-[#B8860B] hover:bg-[#B8860B] hover:text-[#050505] transition-all uppercase tracking-widest text-sm">
        Consultoria
      </button>
    </header>

    <!-- Hero -->
    <section class="h-screen relative flex items-center justify-center overflow-hidden">
      <div class="absolute inset-0">
        <img src="https://images.unsplash.com/photo-1511285560929-80b456fea0bc?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80" class="w-full h-full object-cover opacity-40 mix-blend-luminosity" />
        <div class="absolute inset-0 bg-gradient-to-t from-[#050505] via-transparent to-transparent"></div>
      </div>
      
      <div class="relative z-10 text-center px-4 max-w-4xl mx-auto">
        <h2 class="text-sm uppercase tracking-[0.3em] text-[#B8860B] mb-6">Cerimonial & Assessoria</h2>
        <h1 class="text-5xl md:text-8xl font-light mb-8">
          Experiências <br/> <span class="italic font-serif text-[#B8860B]">Memoráveis</span>
        </h1>
        <p class="text-gray-400 text-lg md:text-xl font-sans max-w-2xl mx-auto font-light leading-relaxed">
          O padrão mais elevado em planejamento de casamentos para quem não aceita nada menos que a perfeição absoluta.
        </p>
      </div>
    </section>

    <!-- Depoimentos de Luxo -->
    <section class="py-32 bg-[#050505]">
      <div class="max-w-4xl mx-auto px-6 text-center">
        <h3 class="text-3xl italic text-[#B8860B] mb-12">"Um nível de detalhe que beira a magia. Nosso casamento foi impecável."</h3>
        <p class="uppercase tracking-widest text-xs text-gray-500 font-sans">- Família Vettori</p>
      </div>
    </section>
  </div>
</template>
