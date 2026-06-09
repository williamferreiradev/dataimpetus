<template>
  <header class="fixed w-full top-0 z-50 bg-white/80 backdrop-blur-md border-b border-gray-100 shadow-sm transition-all duration-300">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <div class="text-2xl font-bold font-serif text-gray-900 tracking-wider">
        CE<span class="text-gold">RI</span>MÔNIA
      </div>
      
      <nav class="hidden md:flex space-x-8 text-sm font-medium text-gray-600">
        <a href="#portfolio" class="hover:text-gold transition-colors">Portfólio</a>
        <a href="#sobre" class="hover:text-gold transition-colors">Sobre Nós</a>
        <a href="#sobre-mim" class="hover:text-gold transition-colors">A Cerimonialista</a>
      </nav>
      
      <a href="#contato" class="hidden md:inline-block bg-gold hover:bg-gold-dark text-white px-6 py-2 rounded-full transition-colors font-medium">
        Solicitar Orçamento
      </a>
      
      <!-- Mobile menu button -->
      <button class="md:hidden text-gray-600 focus:outline-none">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
      </button>
    </div>
  </header>
</template>
