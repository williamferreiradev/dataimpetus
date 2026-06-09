<template>
  <footer class="bg-gray-900 text-white pt-16 pb-8">
    <div class="container mx-auto px-6">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-12 border-b border-gray-800 pb-12 mb-8">
        <div>
          <div class="text-2xl font-bold font-serif tracking-wider mb-6">
            CE<span class="text-gold">RI</span>MÔNIA
          </div>
          <p class="text-gray-400 leading-relaxed">
            Realizando sonhos e criando memórias inesquecíveis. Cada detalhe pensado para o seu evento ser perfeito.
          </p>
        </div>
        
        <div>
          <h4 class="text-lg font-bold font-serif mb-6 text-gold">Links Rápidos</h4>
          <ul class="space-y-3">
            <li><a href="#portfolio" class="text-gray-400 hover:text-white transition-colors">Nosso Portfólio</a></li>
            <li><a href="#sobre" class="text-gray-400 hover:text-white transition-colors">Sobre a Empresa</a></li>
            <li><a href="#sobre-mim" class="text-gray-400 hover:text-white transition-colors">A Cerimonialista</a></li>
            <li><a href="#contato" class="text-gray-400 hover:text-white transition-colors">Solicitar Orçamento</a></li>
          </ul>
        </div>
        
        <div>
          <h4 class="text-lg font-bold font-serif mb-6 text-gold">Horário de Atendimento</h4>
          <ul class="space-y-3 text-gray-400">
            <li>Segunda a Sexta: 09h às 18h</li>
            <li>Sábados: 09h às 13h</li>
            <li>Domingo: Fechado (Eventos)</li>
          </ul>
        </div>
      </div>
      
      <div class="flex flex-col md:flex-row justify-between items-center text-gray-500 text-sm">
        <p>&copy; {{ new Date().getFullYear() }} Cerimônia Eventos. Todos os direitos reservados.</p>
        <p class="mt-4 md:mt-0">Desenvolvido com sofisticação.</p>
      </div>
    </div>
  </footer>
</template>
