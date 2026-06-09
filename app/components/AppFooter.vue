<template>
  <footer class="bg-[#050814] pt-16 pb-8 border-t border-gray-900">
    <div class="container mx-auto px-6">
      <div class="flex flex-col md:flex-row justify-between items-center mb-12">
        <div class="text-2xl font-bold font-['Outfit'] text-white tracking-wider flex items-center gap-2 mb-6 md:mb-0">
          <svg class="w-8 h-8 text-[#00E0FF]" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/></svg>
          DATA <span class="text-[#00E0FF]">IMPETUS</span>
        </div>
        
        <!-- 3 Redes Sociais -->
        <div class="flex gap-4">
          <!-- Instagram -->
          <a href="#" class="w-12 h-12 bg-[#111A35] border border-gray-800 hover:border-[#00E0FF] hover:text-[#00E0FF] rounded-full flex items-center justify-center transition-all text-gray-400">
            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zM12 0C8.741 0 8.333.014 7.053.072 2.695.272.273 2.69.073 7.052.014 8.333 0 8.741 0 12c0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98C8.333 23.986 8.741 24 12 24c3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98C15.668.014 15.259 0 12 0zm0 5.838a6.162 6.162 0 100 12.324 6.162 6.162 0 000-12.324zM12 16a4 4 0 110-8 4 4 0 010 8zm6.406-11.845a1.44 1.44 0 100 2.881 1.44 1.44 0 000-2.881z"/></svg>
          </a>
          <!-- LinkedIn -->
          <a href="#" class="w-12 h-12 bg-[#111A35] border border-gray-800 hover:border-[#00E0FF] hover:text-[#00E0FF] rounded-full flex items-center justify-center transition-all text-gray-400">
            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
          </a>
          <!-- Facebook -->
          <a href="#" class="w-12 h-12 bg-[#111A35] border border-gray-800 hover:border-[#00E0FF] hover:text-[#00E0FF] rounded-full flex items-center justify-center transition-all text-gray-400">
            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z"/></svg>
          </a>
        </div>
      </div>
      
      <div class="border-t border-gray-900 pt-8 flex flex-col md:flex-row justify-between items-center text-sm text-gray-600">
        <p>&copy; {{ new Date().getFullYear() }} Data Impetus. Todos os direitos reservados.</p>
        <p class="mt-2 md:mt-0">Criando máquinas de vendas 24/7.</p>
      </div>
    </div>
  </footer>
</template>
