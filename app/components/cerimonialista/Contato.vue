<template>
  <section id="contato" class="py-24 bg-[#FDFBF7]">
    <div class="container mx-auto px-6">
      <div class="max-w-5xl mx-auto bg-white rounded-3xl shadow-xl overflow-hidden">
        <div class="flex flex-col lg:flex-row">
          <!-- Info Contato -->
          <div class="lg:w-2/5 bg-gray-900 p-12 text-white flex flex-col justify-between relative overflow-hidden">
            <div class="absolute -top-24 -right-24 w-64 h-64 bg-gold rounded-full opacity-20"></div>
            <div class="absolute -bottom-24 -left-24 w-64 h-64 bg-gold rounded-full opacity-20"></div>
            
            <div class="relative z-10">
              <h3 class="text-3xl font-serif font-bold mb-2">Vamos Conversar?</h3>
              <p class="text-gray-400 mb-12">Conte-nos sobre o seu evento. Retornaremos em até 24h úteis.</p>
              
              <div class="space-y-6">
                <div class="flex items-center gap-4">
                  <div class="w-10 h-10 rounded-full bg-white/10 flex items-center justify-center shrink-0">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                  </div>
                  <span>(11) 99999-9999</span>
                </div>
                
                <div class="flex items-center gap-4">
                  <div class="w-10 h-10 rounded-full bg-white/10 flex items-center justify-center shrink-0">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                  </div>
                  <span>contato@cerimonial.com.br</span>
                </div>
                
                <div class="flex items-center gap-4">
                  <div class="w-10 h-10 rounded-full bg-white/10 flex items-center justify-center shrink-0">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                  </div>
                  <span>Av. Paulista, 1000 - São Paulo, SP</span>
                </div>
              </div>
            </div>
            
            <div class="flex gap-4 mt-12 relative z-10">
              <!-- Social Icons -->
              <a href="#" class="w-10 h-10 bg-white/10 hover:bg-gold rounded-full flex items-center justify-center transition-colors">
                <span class="sr-only">Instagram</span>
                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zM12 0C8.741 0 8.333.014 7.053.072 2.695.272.273 2.69.073 7.052.014 8.333 0 8.741 0 12c0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98C8.333 23.986 8.741 24 12 24c3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98C15.668.014 15.259 0 12 0zm0 5.838a6.162 6.162 0 100 12.324 6.162 6.162 0 000-12.324zM12 16a4 4 0 110-8 4 4 0 010 8zm6.406-11.845a1.44 1.44 0 100 2.881 1.44 1.44 0 000-2.881z"/></svg>
              </a>
            </div>
          </div>
          
          <!-- Formulário -->
          <div class="lg:w-3/5 p-12">
            <form class="space-y-6">
              <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div>
                  <label class="block text-sm font-medium text-gray-700 mb-2">Nome Completo</label>
                  <input type="text" class="w-full px-4 py-3 border border-gray-200 rounded-lg focus:ring-2 focus:ring-gold focus:border-transparent outline-none transition-all" placeholder="Seu nome" />
                </div>
                <div>
                  <label class="block text-sm font-medium text-gray-700 mb-2">Telefone / WhatsApp</label>
                  <input type="text" class="w-full px-4 py-3 border border-gray-200 rounded-lg focus:ring-2 focus:ring-gold focus:border-transparent outline-none transition-all" placeholder="(00) 00000-0000" />
                </div>
              </div>
              
              <div>
                <label class="block text-sm font-medium text-gray-700 mb-2">E-mail</label>
                <input type="email" class="w-full px-4 py-3 border border-gray-200 rounded-lg focus:ring-2 focus:ring-gold focus:border-transparent outline-none transition-all" placeholder="seu@email.com" />
              </div>
              
              <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div>
                  <label class="block text-sm font-medium text-gray-700 mb-2">Tipo de Evento</label>
                  <select class="w-full px-4 py-3 border border-gray-200 rounded-lg focus:ring-2 focus:ring-gold focus:border-transparent outline-none transition-all bg-white">
                    <option>Casamento</option>
                    <option>15 Anos</option>
                    <option>Corporativo</option>
                    <option>Outro</option>
                  </select>
                </div>
                <div>
                  <label class="block text-sm font-medium text-gray-700 mb-2">Data Prevista</label>
                  <input type="date" class="w-full px-4 py-3 border border-gray-200 rounded-lg focus:ring-2 focus:ring-gold focus:border-transparent outline-none transition-all text-gray-600" />
                </div>
              </div>
              
              <div>
                <label class="block text-sm font-medium text-gray-700 mb-2">Mensagem (Conte-nos mais sobre o evento)</label>
                <textarea rows="4" class="w-full px-4 py-3 border border-gray-200 rounded-lg focus:ring-2 focus:ring-gold focus:border-transparent outline-none transition-all resize-none" placeholder="Detalhes adicionais..."></textarea>
              </div>
              
              <button type="submit" class="w-full bg-gold hover:bg-gold-dark text-white font-medium py-4 rounded-lg transition-colors text-lg shadow-lg">
                Enviar Mensagem
              </button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
