<template>
  <section id="portfolio" class="py-24 bg-white">
    <div class="container mx-auto px-6">
      <div class="text-center mb-16">
        <span class="text-gold font-semibold tracking-widest uppercase text-sm mb-2 block">Nossas Histórias</span>
        <h2 class="text-4xl md:text-5xl font-bold text-gray-900">Portfólio de Eventos</h2>
        <div class="w-24 h-1 bg-gold mx-auto mt-6"></div>
      </div>
      
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Item 1 -->
        <div class="group relative overflow-hidden rounded-2xl cursor-pointer">
          <img src="https://images.unsplash.com/photo-1511285560929-80b456fea0bc?ixlib=rb-4.0.3&auto=format&fit=crop&w=1000&q=80" alt="Casamento na Praia" class="w-full h-96 object-cover transition-transform duration-700 group-hover:scale-110" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/20 to-transparent opacity-80 group-hover:opacity-90 transition-opacity duration-300"></div>
          <div class="absolute bottom-0 left-0 w-full p-8 translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <span class="text-gold text-sm font-medium mb-2 block">Casamento na Praia</span>
            <h3 class="text-2xl text-white font-serif">Ana & Carlos</h3>
          </div>
        </div>
        
        <!-- Item 2 -->
        <div class="group relative overflow-hidden rounded-2xl cursor-pointer">
          <img src="https://images.unsplash.com/photo-1519741497674-611481863552?ixlib=rb-4.0.3&auto=format&fit=crop&w=1000&q=80" alt="Casamento Clássico" class="w-full h-96 object-cover transition-transform duration-700 group-hover:scale-110" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/20 to-transparent opacity-80 group-hover:opacity-90 transition-opacity duration-300"></div>
          <div class="absolute bottom-0 left-0 w-full p-8 translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <span class="text-gold text-sm font-medium mb-2 block">Casamento Clássico</span>
            <h3 class="text-2xl text-white font-serif">Mariana & João</h3>
          </div>
        </div>
        
        <!-- Item 3 -->
        <div class="group relative overflow-hidden rounded-2xl cursor-pointer">
          <img src="https://images.unsplash.com/photo-1464366400600-7168b8af9bc3?ixlib=rb-4.0.3&auto=format&fit=crop&w=1000&q=80" alt="Festa de 15 Anos" class="w-full h-96 object-cover transition-transform duration-700 group-hover:scale-110" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/20 to-transparent opacity-80 group-hover:opacity-90 transition-opacity duration-300"></div>
          <div class="absolute bottom-0 left-0 w-full p-8 translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <span class="text-gold text-sm font-medium mb-2 block">15 Anos</span>
            <h3 class="text-2xl text-white font-serif">Júlia - O Baile</h3>
          </div>
        </div>
      </div>
      
      <div class="text-center mt-12">
        <a href="#" class="inline-flex items-center text-gray-900 font-medium hover:text-gold transition-colors">
          Ver Galeria Completa
          <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
        </a>
      </div>
    </div>
  </section>
</template>
