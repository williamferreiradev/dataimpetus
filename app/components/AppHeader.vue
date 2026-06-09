<template>
  <header class="fixed w-full top-0 z-50 bg-[#0A1128]/90 backdrop-blur-md border-b border-gray-800 transition-all duration-300">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <div class="text-2xl font-bold font-['Outfit'] text-white tracking-wider flex items-center gap-2">
        <svg class="w-8 h-8 text-[#00E0FF]" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/></svg>
        DATA <span class="text-[#00E0FF]">IMPETUS</span>
      </div>
      
      <nav class="hidden md:flex space-x-8 text-sm font-medium text-gray-300">
        <a href="#como-ajudamos" class="hover:text-[#00E0FF] transition-colors">Como Ajudamos</a>
        <a href="#portfolio" class="hover:text-[#00E0FF] transition-colors">Portfólio</a>
        <a href="#equipe" class="hover:text-[#00E0FF] transition-colors">Equipe</a>
      </nav>
      
      <a href="#contato" class="hidden md:inline-flex items-center gap-2 bg-[#00E0FF] hover:bg-[#00B3CC] text-[#0A1128] px-6 py-2.5 rounded-lg transition-all font-bold shadow-[0_0_15px_rgba(0,224,255,0.4)] hover:shadow-[0_0_25px_rgba(0,224,255,0.6)]">
        Quero meu Site
      </a>
      
      <!-- Mobile menu button -->
      <button class="md:hidden text-gray-300 focus:outline-none">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
      </button>
    </div>
  </header>
</template>
