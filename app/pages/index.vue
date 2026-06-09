<template>
  <div class="font-sans text-gray-200 bg-[#0A1128] min-h-screen">
    <AppHeader />
    <main>
      <HeroSection />
      <SobreNos />
      <ComoAjudamos />
      <PassosProcesso />
      <Portfolio />
      <Depoimentos />
      <Faq />
      <Contato />
    </main>
    <AppFooter />
  </div>
</template>

<script setup>
import { useHead } from '#imports'

useHead({
  title: 'Data Impetus | Sites para Cerimonialistas',
  meta: [
    { name: 'description', content: 'Tenha seu site de cerimonial 24/7 com alta conversão e entrega em 24h.' }
  ]
})
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;700;800&family=Inter:wght@400;500;600&display=swap');

html {
  scroll-behavior: smooth;
  background-color: #0A1128;
}

h1, h2, h3, h4, h5, h6 {
  font-family: 'Outfit', sans-serif;
}

body {
  font-family: 'Inter', sans-serif;
}

.text-cyan {
  color: #00E0FF;
}
.bg-cyan {
  background-color: #00E0FF;
}
.border-cyan {
  border-color: #00E0FF;
}
.hover\:bg-cyan-dark:hover {
  background-color: #00B3CC;
}
</style>
