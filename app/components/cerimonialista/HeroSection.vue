<template>
  <section class="relative min-h-screen flex items-center justify-center pt-20 overflow-hidden">
    <!-- Background Image with Overlay -->
    <div class="absolute inset-0 z-0">
      <img src="https://images.unsplash.com/photo-1519225421980-715cb0215aed?ixlib=rb-4.0.3&auto=format&fit=crop&w=2070&q=80" alt="Casamento Elegante" class="w-full h-full object-cover object-center opacity-80" />
      <div class="absolute inset-0 bg-gradient-to-r from-white/90 via-white/70 to-transparent"></div>
    </div>
    
    <div class="container mx-auto px-6 relative z-10 flex flex-col items-start w-full">
      <div class="max-w-2xl">
        <span class="text-gold font-semibold tracking-widest uppercase text-sm mb-4 block">Assessoria & Cerimonial</span>
        <h1 class="text-5xl md:text-7xl font-bold text-gray-900 mb-6 leading-tight">
          Transformando sonhos em momentos <span class="italic text-gold">inesquecíveis</span>.
        </h1>
        <p class="text-lg text-gray-700 mb-10 max-w-lg leading-relaxed">
          Planejamento perfeito, execução impecável e amor em cada detalhe para que o seu dia seja exatamente como você sonhou.
        </p>
        
        <div class="flex flex-col sm:flex-row gap-4">
          <a href="#contato" class="bg-gold hover:bg-gold-dark text-white px-8 py-4 rounded-full text-center transition-all shadow-lg hover:shadow-xl font-medium text-lg">
            Agende uma Reunião
          </a>
          <a href="#portfolio" class="bg-white hover:bg-gray-50 text-gray-900 border border-gray-200 px-8 py-4 rounded-full text-center transition-all font-medium text-lg">
            Ver Casamentos
          </a>
        </div>
      </div>
    </div>
  </section>
</template>
