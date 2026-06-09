<template>
  <div class="min-h-screen bg-[#0A0B0D] text-gray-100 font-sans selection:bg-[#FF5A1F]/20 selection:text-white overflow-x-hidden">
    <Head>
      <Title>Campello Pneus — Centro Automotivo Select</Title>
      <Meta name="description" content="Cuidamos do seu carro com excelência! Alinhamento 3D, balanceamento, suspensão, pneus e muito mais em Parnamirim/RN." />
      <Link rel="preconnect" href="https://fonts.googleapis.com" />
      <Link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="" />
      <Link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;500;700;900&family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet" />
    </Head>

    <!-- Header component -->
    <CampellopneusHeader />

    <main>
      <!-- HERO SECTION -->
      <section id="inicio" class="relative min-h-screen flex items-center pt-24 pb-16 overflow-hidden">
        <!-- Background Image with Overlay -->
        <div class="absolute inset-0 z-0">
          <img src="https://images.unsplash.com/photo-1611016186353-9af58c69a533?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80" alt="Esportivo no elevador automotivo" class="w-full h-full object-cover object-center opacity-30" />
          <div class="absolute inset-0 bg-gradient-to-t from-[#0A0B0D] via-[#0A0B0D]/80 to-transparent" />
          <div class="absolute inset-0 bg-gradient-to-r from-[#0A0B0D] via-[#0A0B0D]/60 to-transparent" />
        </div>

        <!-- Ambient Glows -->
        <div class="absolute top-1/4 right-[-10%] w-[500px] h-[500px] bg-[#FF5A1F]/10 rounded-full blur-[150px] pointer-events-none" />
        <div class="absolute bottom-10 left-[-10%] w-[600px] h-[600px] bg-[#F59E0B]/5 rounded-full blur-[180px] pointer-events-none" />

        <div class="max-w-7xl mx-auto px-6 relative z-10 w-full grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
          
          <!-- Text Content -->
          <div class="lg:col-span-7 flex flex-col items-start text-left">
            <!-- Badge -->
            <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-[#14161A] border border-[#22252D] text-xs font-semibold text-[#F59E0B] mb-6 shadow-md">
              <span class="w-2.5 h-2.5 rounded-full bg-[#FF5A1F] animate-pulse" />
              Temos Novidades: Novo Endereço!
            </div>

            <!-- Title -->
            <h1 class="text-4xl sm:text-5xl md:text-6xl font-black tracking-tight text-white mb-6 leading-tight" style="font-family: 'Orbitron', sans-serif;">
              SEU CARRO EM<br />
              <span class="text-transparent bg-clip-text bg-gradient-to-r from-[#FF5A1F] to-[#F59E0B]">BOAS MÃOS</span>, SEMPRE!
            </h1>

            <!-- Description -->
            <p class="text-base sm:text-lg text-gray-400 font-medium mb-8 max-w-xl leading-relaxed" style="font-family: 'Plus Jakarta Sans', sans-serif;">
              Cuidamos do seu veículo com a excelência que ele merece. Equipamentos de última geração para alinhamento 3D, balanceamento, suspensão e pneus de alta performance.
            </p>

            <!-- Location Callout -->
            <div class="flex items-center gap-4 p-4 rounded-xl bg-[#14161A]/90 border border-[#22252D] mb-10 w-full max-w-lg shadow-inner backdrop-blur-sm">
              <div class="w-12 h-12 rounded-lg bg-[#FF5A1F]/10 flex items-center justify-center text-[#FF5A1F] shrink-0">
                <svg class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                </svg>
              </div>
              <div>
                <p class="text-xs text-gray-500 font-bold uppercase tracking-wider">Nosso Novo Endereço</p>
                <p class="text-sm text-white font-semibold">Av. dos Pinheirais, 1043 — ao lado da antiga Maré Mansa</p>
              </div>
            </div>

            <!-- CTAs -->
            <div class="flex flex-col sm:flex-row items-center gap-4 w-full sm:w-auto">
              <a href="https://wa.me/message/IPGIT7ZRZSKQK1" target="_blank"
                class="w-full sm:w-auto inline-flex justify-center items-center gap-3 bg-gradient-to-r from-[#FF5A1F] to-[#F59E0B] hover:from-[#FF4500] hover:to-[#D4AF37] text-white font-bold px-8 py-4 rounded-xl transition-all duration-300 shadow-[0_4px_25px_rgba(255,90,31,0.4)] hover:shadow-[0_8px_35px_rgba(255,90,31,0.6)] hover:-translate-y-1 text-base">
                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                  <path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946C.06 5.348 5.397.01 12.008.01c3.202.001 6.212 1.246 8.477 3.513 2.262 2.268 3.507 5.28 3.505 8.484-.004 6.657-5.34 11.997-11.953 11.997-2.005-.001-3.973-.502-5.725-1.457L0 24zm6.59-4.846c1.6.95 3.188 1.449 4.825 1.451 5.436 0 9.86-4.37 9.864-9.799.002-2.63-1.023-5.101-2.885-6.967C16.57 2.022 14.09 1 11.993 1c-5.43 0-9.852 4.37-9.856 9.799-.001 1.761.47 3.479 1.365 5.011L2.502 21.5l5.965-1.566z"/>
                </svg>
                <span>Falar no WhatsApp</span>
              </a>
              <a href="#servicos"
                class="w-full sm:w-auto inline-flex justify-center items-center gap-2 bg-[#14161A] hover:bg-[#1C1F26] text-white font-bold px-8 py-4 rounded-xl transition-all duration-300 border border-[#22252D] hover:border-gray-600 text-base shadow-inner">
                <span>Ver Promoções</span>
              </a>
            </div>
          </div>

          <!-- Promo Card Side -->
          <div class="lg:col-span-5 relative w-full flex justify-center lg:justify-end mt-8 lg:mt-0">
            <!-- Glow background behind card -->
            <div class="absolute inset-0 bg-[#FF5A1F]/10 blur-[80px] rounded-full -z-10 transform scale-75" />
            
            <!-- Floating Offer Badge -->
            <div class="absolute -top-6 -left-6 z-20 bg-gradient-to-tr from-[#FF5A1F] to-[#FF8C00] text-white text-xs font-black px-4 py-2.5 rounded-xl shadow-lg border border-[#FF8C00] rotate-[-6deg] tracking-wider uppercase animate-bounce" style="font-family: 'Orbitron', sans-serif;">
              🔥 IMPERDÍVEL!
            </div>

            <!-- The Flyer Card -->
            <div class="bg-[#14161A] border-2 border-[#FF5A1F]/50 rounded-2xl p-6 sm:p-8 w-full max-w-sm shadow-[0_15px_40px_rgba(0,0,0,0.5)] relative overflow-hidden">
              <div class="absolute top-0 right-0 w-32 h-32 bg-[#FF5A1F]/5 rounded-full blur-[40px] pointer-events-none" />
              
              <h3 class="text-xl font-bold tracking-tight text-white mb-6 uppercase text-center border-b border-[#22252D] pb-4" style="font-family: 'Orbitron', sans-serif;">
                Ofertas da <span class="text-[#FF5A1F]">Semana</span>
              </h3>

              <div class="flex flex-col gap-4 mb-8">
                <!-- Promo Item 1 -->
                <div class="flex justify-between items-center p-3 rounded-lg bg-[#0A0B0D] border border-[#22252D] hover:border-[#FF5A1F]/30 transition-colors">
                  <div>
                    <h4 class="font-bold text-white text-sm">Alinhamento 3D</h4>
                    <p class="text-[10px] text-gray-500 font-bold uppercase tracking-wider">A partir de</p>
                  </div>
                  <div class="text-right">
                    <span class="text-xs font-bold text-[#FF5A1F] mr-1">R$</span>
                    <span class="text-2xl font-black text-white font-mono leading-none">9,99</span>
                  </div>
                </div>

                <!-- Promo Item 2 -->
                <div class="flex justify-between items-center p-3 rounded-lg bg-[#0A0B0D] border border-[#22252D] hover:border-[#FF5A1F]/30 transition-colors">
                  <div>
                    <h4 class="font-bold text-white text-sm">Balanceamento</h4>
                    <p class="text-[10px] text-gray-500 font-bold uppercase tracking-wider">Roda de Ferro</p>
                  </div>
                  <div class="text-right">
                    <span class="text-xs font-bold text-[#F59E0B] mr-1">R$</span>
                    <span class="text-2xl font-black text-white font-mono leading-none">15,99</span>
                  </div>
                </div>

                <!-- Promo Item 3 -->
                <div class="flex justify-between items-center p-3 rounded-lg bg-[#0A0B0D] border border-[#22252D] hover:border-[#FF5A1F]/30 transition-colors">
                  <div>
                    <h4 class="font-bold text-white text-sm">Balanceamento</h4>
                    <p class="text-[10px] text-gray-500 font-bold uppercase tracking-wider">Liga Leve</p>
                  </div>
                  <div class="text-right">
                    <span class="text-xs font-bold text-[#F59E0B] mr-1">R$</span>
                    <span class="text-2xl font-black text-white font-mono leading-none">17,99</span>
                  </div>
                </div>
              </div>

              <!-- Bonus Box -->
              <div class="bg-gradient-to-r from-[#FF5A1F]/20 to-[#F59E0B]/10 border border-[#FF5A1F]/30 rounded-xl p-4 text-center">
                <span class="text-[10px] font-bold text-[#FF5A1F] uppercase tracking-[0.15em] block mb-1">🎁 BÔNUS EXCLUSIVO</span>
                <p class="text-xs font-extrabold text-white leading-relaxed">
                  Realizando Alinhamento + Balanceamento você GANHA:
                </p>
                <p class="text-sm font-black text-[#F59E0B] mt-2 uppercase tracking-wide">
                  Rodízio de Pneus + Check-up da Suspensão!
                </p>
              </div>

              <div class="mt-6 text-center text-[10px] text-gray-500 font-bold uppercase tracking-wider">
                *Oferta válida por tempo limitado. Aproveite!
              </div>
            </div>
          </div>

        </div>
      </section>

      <!-- ROTATING BRANDS MARQUEE -->
      <section class="py-12 bg-[#0E1014] border-y border-[#22252D] overflow-hidden relative">
        <div class="absolute left-0 top-0 bottom-0 w-24 bg-gradient-to-r from-[#0E1014] to-transparent z-10 pointer-events-none" />
        <div class="absolute right-0 top-0 bottom-0 w-24 bg-gradient-to-l from-[#0E1014] to-transparent z-10 pointer-events-none" />
        
        <div class="flex select-none overflow-hidden gap-10">
          <div class="flex shrink-0 items-center justify-around gap-20 min-w-full animate-marquee">
            <span v-for="(brand, idx) in brands" :key="idx" class="text-xl sm:text-2xl font-black tracking-widest text-gray-700 hover:text-white transition-colors duration-300 uppercase" style="font-family: 'Orbitron', sans-serif;">
              {{ brand }}
            </span>
          </div>
          <div class="flex shrink-0 items-center justify-around gap-20 min-w-full animate-marquee" aria-hidden="true">
            <span v-for="(brand, idx) in brands" :key="'dup-'+idx" class="text-xl sm:text-2xl font-black tracking-widest text-gray-700 hover:text-white transition-colors duration-300 uppercase" style="font-family: 'Orbitron', sans-serif;">
              {{ brand }}
            </span>
          </div>
        </div>
      </section>

      <!-- PORTFOLIO / GALERIA -->
      <section id="portfolio" class="py-24 bg-[#0E1014] border-y border-[#22252D]">
        <div class="max-w-7xl mx-auto px-6">
          
          <div class="flex flex-col md:flex-row md:items-end justify-between mb-16 gap-6">
            <div>
              <span class="text-xs font-black tracking-[0.25em] text-[#FF5A1F] uppercase mb-3 block" style="font-family: 'Orbitron', sans-serif;">
                Portfólio
              </span>
              <h2 class="text-3xl sm:text-4xl font-extrabold text-white tracking-tight" style="font-family: 'Orbitron', sans-serif;">
                MÁQUINAS EM <span class="text-transparent bg-clip-text bg-gradient-to-r from-[#FF5A1F] to-[#F59E0B]">MOVIMENTO</span>
              </h2>
            </div>
            <p class="text-gray-400 text-sm max-w-sm leading-relaxed">
              Confira alguns dos veículos esportivos, SUVs e carros do dia a dia que passaram por nossos serviços de alinhamento, balanceamento e troca de pneus.
            </p>
          </div>

          <!-- Gallery Grid -->
          <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
            <div v-for="(photo, idx) in galleryPhotos" :key="idx" class="relative rounded-xl overflow-hidden border border-[#22252D] group shadow-lg aspect-square">
              <!-- Overlay hover -->
              <div class="absolute inset-0 bg-[#0A0B0D]/80 opacity-0 group-hover:opacity-100 transition-opacity duration-300 z-10 flex flex-col justify-end p-6" />
              
              <!-- Image -->
              <img :src="photo.src" :alt="photo.alt" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110 z-0" />
              
              <!-- Hover Content -->
              <div class="absolute inset-0 z-20 flex flex-col justify-end p-6 translate-y-4 group-hover:translate-y-0 opacity-0 group-hover:opacity-100 transition-all duration-300">
                <span class="text-[10px] font-black text-[#FF5A1F] tracking-widest uppercase block mb-1" style="font-family: 'Orbitron', sans-serif;">{{ photo.category }}</span>
                <h3 class="text-lg font-bold text-white mb-2">{{ photo.title }}</h3>
                <p class="text-xs text-gray-400">{{ photo.desc }}</p>
              </div>
            </div>
          </div>

        </div>
      </section>

      <!-- SERVIÇOS -->
      <section id="servicos" class="py-24 bg-[#0A0B0D] relative">
        <div class="absolute top-1/4 right-0 w-[400px] h-[400px] bg-[#FF5A1F]/3 rounded-full blur-[150px] pointer-events-none" />

        <div class="max-w-7xl mx-auto px-6">
          <div class="text-center max-w-3xl mx-auto mb-16">
            <span class="text-xs font-black tracking-[0.25em] text-[#FF5A1F] uppercase mb-3 block" style="font-family: 'Orbitron', sans-serif;">
              Nossos Serviços
            </span>
            <h2 class="text-3xl sm:text-5xl font-extrabold text-white mb-6 tracking-tight leading-tight" style="font-family: 'Orbitron', sans-serif;">
              CUIDADO COMPLETO COM <span class="text-transparent bg-clip-text bg-gradient-to-r from-[#FF5A1F] to-[#F59E0B]">EXCELÊNCIA</span>
            </h2>
            <p class="text-gray-400 text-base leading-relaxed">
              Equipamentos importados de última geração e equipe técnica capacitada para entregar serviços rápidos e de altíssima precisão.
            </p>
          </div>

          <!-- Services Grid -->
          <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <div v-for="(service, idx) in services" :key="idx" class="bg-[#14161A] border border-[#22252D] hover:border-[#FF5A1F]/30 p-8 rounded-2xl shadow-md hover:shadow-xl hover:-translate-y-1 transition-all duration-300 group flex flex-col justify-between">
              <div>
                <!-- Icon container -->
                <div class="w-14 h-14 bg-[#0A0B0D] border border-[#22252D] rounded-xl flex items-center justify-center text-[#FF5A1F] mb-6 group-hover:scale-110 transition-transform duration-300" v-html="service.icon">
                </div>
                <h3 class="text-xl font-bold text-white mb-4" style="font-family: 'Orbitron', sans-serif;">{{ service.title }}</h3>
                <p class="text-sm text-gray-400 leading-relaxed mb-6 font-medium">{{ service.desc }}</p>
              </div>

              <!-- Price Tag or CTA -->
              <div class="pt-6 border-t border-[#22252D] flex items-center justify-between">
                <span class="text-xs font-bold text-gray-500 uppercase tracking-wider">A partir de</span>
                <span class="text-xl font-black text-[#F59E0B] font-mono">{{ service.price }}</span>
              </div>
            </div>
          </div>

          <!-- Special Promo Banner -->
          <div class="mt-16 bg-gradient-to-r from-[#14161A] via-[#1C1E24] to-[#14161A] border-2 border-[#FF5A1F]/30 rounded-3xl p-8 sm:p-12 relative overflow-hidden shadow-2xl">
            <div class="absolute top-0 right-0 w-96 h-96 bg-[#FF5A1F]/5 rounded-full blur-[100px] pointer-events-none" />
            
            <div class="relative z-10 flex flex-col lg:flex-row items-center justify-between gap-8">
              <div class="max-w-2xl text-center lg:text-left">
                <span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-[#FF5A1F]/10 border border-[#FF5A1F]/30 text-xs font-bold text-[#FF5A1F] mb-4 uppercase tracking-wider">
                  🔥 Super Combo Especial
                </span>
                <h3 class="text-2xl sm:text-3xl font-extrabold text-white mb-4" style="font-family: 'Orbitron', sans-serif;">
                  FALE CONOSCO E GARANTA SEUS BÔNUS!
                </h3>
                <p class="text-gray-400 text-sm sm:text-base leading-relaxed">
                  Realizando os serviços de **Alinhamento** e **Balanceamento** no mesmo dia, você não paga nada a mais pelo **Rodízio de Pneus** e pelo **Check-up completo da suspensão**. Economize e dirija em total segurança!
                </p>
              </div>
              <a href="https://wa.me/message/IPGIT7ZRZSKQK1" target="_blank"
                class="bg-gradient-to-r from-[#FF5A1F] to-[#F59E0B] hover:from-[#FF4500] hover:to-[#D4AF37] text-white font-black px-10 py-5 rounded-2xl text-lg transition-all duration-300 shadow-[0_8px_30px_rgba(255,90,31,0.4)] shrink-0 hover:-translate-y-0.5">
                AGENDAR AGORA NO WHATSAPP
              </a>
            </div>
          </div>

        </div>
      </section>

      <!-- TESTEMUNHOS -->
      <section id="depoimentos" class="py-24 bg-[#0E1014] border-y border-[#22252D]">
        <div class="max-w-7xl mx-auto px-6">
          <div class="text-center max-w-3xl mx-auto mb-16">
            <span class="text-xs font-black tracking-[0.25em] text-[#FF5A1F] uppercase mb-3 block" style="font-family: 'Orbitron', sans-serif;">
              Depoimentos
            </span>
            <h2 class="text-3xl sm:text-4xl font-extrabold text-white mb-6 tracking-tight" style="font-family: 'Orbitron', sans-serif;">
              A CONFIANÇA DE QUEM <span class="text-transparent bg-clip-text bg-gradient-to-r from-[#FF5A1F] to-[#F59E0B]">COMPROVOU</span>
            </h2>
            <p class="text-gray-400 text-sm max-w-xl mx-auto">
              Veja a opinião de alguns dos nossos mais de 3.500 clientes atendidos em nossa trajetória.
            </p>
          </div>

          <!-- Testimonials Grid -->
          <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div v-for="(dep, idx) in testimonials" :key="idx" class="bg-[#14161A] border border-[#22252D] shadow-md p-8 rounded-2xl flex flex-col justify-between h-full hover:border-[#FF5A1F]/20 transition-all duration-300">
              <div>
                <!-- Stars -->
                <div class="flex items-center gap-1.5 mb-6 text-[#F59E0B]">
                  <span v-for="i in 5" :key="i" class="text-base">★</span>
                </div>
                <p class="text-gray-300 font-medium leading-relaxed mb-8 italic text-sm">
                  "{{ dep.text }}"
                </p>
              </div>
              <div class="flex items-center gap-4 pt-6 border-t border-[#22252D]">
                <div class="w-10 h-10 bg-[#FF5A1F]/10 text-[#FF5A1F] rounded-full flex items-center justify-center font-black border border-[#FF5A1F]/30 text-sm">
                  {{ dep.name.charAt(0) }}
                </div>
                <div>
                  <p class="text-white font-bold text-sm">{{ dep.name }}</p>
                  <p class="text-gray-500 text-xs font-semibold">{{ dep.role }}</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- CONTATO & HORÁRIOS -->
      <section id="contato" class="py-24 bg-[#0A0B0D] relative">
        <div class="max-w-7xl mx-auto px-6">
          <div class="grid grid-cols-1 lg:grid-cols-12 gap-16 items-start">
            
            <!-- Information Column -->
            <div class="lg:col-span-5 flex flex-col items-start">
              <span class="text-xs font-black tracking-[0.25em] text-[#FF5A1F] uppercase mb-3 block" style="font-family: 'Orbitron', sans-serif;">
                Contato
              </span>
              <h2 class="text-3xl sm:text-4xl font-extrabold text-white mb-6 tracking-tight" style="font-family: 'Orbitron', sans-serif;">
                VENHA NOS <span class="text-transparent bg-clip-text bg-gradient-to-r from-[#FF5A1F] to-[#F59E0B]">VISITAR</span>
              </h2>
              <p class="text-gray-400 font-medium leading-relaxed mb-10 text-sm sm:text-base">
                Estamos prontos para atender você e seu veículo no nosso novo endereço. Se preferir tirar dúvidas ou agendar antes, fale diretamente conosco pelos canais abaixo.
              </p>

              <!-- Contacts Cards -->
              <div class="flex flex-col gap-6 w-full">
                <!-- Address Card -->
                <div class="flex items-start gap-4 p-4 rounded-xl bg-[#14161A] border border-[#22252D] shadow-inner">
                  <div class="w-10 h-10 rounded-lg bg-[#FF5A1F]/10 flex items-center justify-center text-[#FF5A1F] shrink-0 mt-1">
                    <svg class="w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" /><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" /></svg>
                  </div>
                  <div>
                    <h4 class="text-white font-bold text-sm uppercase tracking-wide">Endereço</h4>
                    <p class="text-xs text-gray-400 mt-1 leading-relaxed">
                      Av. dos Pinheirais, 1043 — ao lado da antiga Maré Mansa<br/>Neópolis, Natal/Parnamirim - RN
                    </p>
                  </div>
                </div>

                <!-- Call Card -->
                <div class="flex items-start gap-4 p-4 rounded-xl bg-[#14161A] border border-[#22252D] shadow-inner">
                  <div class="w-10 h-10 rounded-lg bg-[#FF5A1F]/10 flex items-center justify-center text-[#FF5A1F] shrink-0 mt-1">
                    <svg class="w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.94.725l.548 2.2a1 1 0 01-.321.988l-1.305.98a10.582 10.582 0 004.872 4.872l.98-1.305a1 1 0 01.988-.321l2.2.548a1 1 0 01.725.94V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" /></svg>
                  </div>
                  <div>
                    <h4 class="text-white font-bold text-sm uppercase tracking-wide">Telefone & WhatsApp</h4>
                    <p class="text-xs text-gray-400 mt-1 leading-relaxed">
                      Ligue: <a href="tel:8422261283" class="text-[#F59E0B] font-bold">(84) 2226-1283</a><br/>
                      WhatsApp: <a href="https://wa.me/message/IPGIT7ZRZSKQK1" target="_blank" class="text-[#FF5A1F] font-bold">wa.me/campellopneus</a>
                    </p>
                  </div>
                </div>

                <!-- Hours Card -->
                <div class="flex items-start gap-4 p-4 rounded-xl bg-[#14161A] border border-[#22252D] shadow-inner">
                  <div class="w-10 h-10 rounded-lg bg-[#FF5A1F]/10 flex items-center justify-center text-[#FF5A1F] shrink-0 mt-1">
                    <svg class="w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                  </div>
                  <div class="w-full">
                    <h4 class="text-white font-bold text-sm uppercase tracking-wide">Horários de Atendimento</h4>
                    <div class="grid grid-cols-2 text-xs text-gray-400 mt-2 gap-y-1">
                      <span>Segunda - Sexta:</span>
                      <span class="text-white font-semibold text-right">08:00 às 18:00</span>
                      <span>Sábado:</span>
                      <span class="text-white font-semibold text-right">08:00 às 13:00</span>
                      <span>Domingos:</span>
                      <span class="text-red-500 font-semibold text-right">Fechado</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- Form Column -->
            <div class="lg:col-span-7 bg-[#14161A] border border-[#22252D] rounded-2xl p-8 shadow-xl w-full">
              <h3 class="text-xl font-bold text-white mb-6 uppercase" style="font-family: 'Orbitron', sans-serif;">Envie sua mensagem</h3>
              
              <form @submit.prevent="submitForm" class="flex flex-col gap-6">
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                  <!-- Name Input -->
                  <div class="flex flex-col gap-2">
                    <label class="text-xs font-bold uppercase tracking-wider text-gray-400" for="name">Seu Nome</label>
                    <input id="name" type="text" required v-model="formData.name" placeholder="Ex: João Silva" class="bg-[#0A0B0D] border border-[#22252D] rounded-xl px-4 py-3.5 text-sm text-white focus:outline-none focus:border-[#FF5A1F] transition-colors" />
                  </div>
                  <!-- Phone Input -->
                  <div class="flex flex-col gap-2">
                    <label class="text-xs font-bold uppercase tracking-wider text-gray-400" for="phone">Telefone / WhatsApp</label>
                    <input id="phone" type="tel" required v-model="formData.phone" placeholder="Ex: (84) 99999-9999" class="bg-[#0A0B0D] border border-[#22252D] rounded-xl px-4 py-3.5 text-sm text-white focus:outline-none focus:border-[#FF5A1F] transition-colors" />
                  </div>
                </div>

                <!-- Vehicle Info -->
                <div class="flex flex-col gap-2">
                  <label class="text-xs font-bold uppercase tracking-wider text-gray-400" for="vehicle">Carro (Modelo / Ano)</label>
                  <input id="vehicle" type="text" v-model="formData.vehicle" placeholder="Ex: Corolla 2021" class="bg-[#0A0B0D] border border-[#22252D] rounded-xl px-4 py-3.5 text-sm text-white focus:outline-none focus:border-[#FF5A1F] transition-colors" />
                </div>

                <!-- Message Input -->
                <div class="flex flex-col gap-2">
                  <label class="text-xs font-bold uppercase tracking-wider text-gray-400" for="message">Serviço desejado ou Dúvida</label>
                  <textarea id="message" required v-model="formData.message" rows="4" placeholder="Descreva o que seu veículo precisa (ex: alinhamento e balanceamento, troca de pneus, revisão de freios...)" class="bg-[#0A0B0D] border border-[#22252D] rounded-xl px-4 py-3.5 text-sm text-white focus:outline-none focus:border-[#FF5A1F] transition-colors resize-none"></textarea>
                </div>

                <!-- Submit Button -->
                <button type="submit" class="w-full bg-[#1C1F26] hover:bg-[#FF5A1F] text-white font-bold py-4 rounded-xl border border-[#22252D] hover:border-[#FF5A1F] shadow-md transition-all duration-300 tracking-wider uppercase text-sm" style="font-family: 'Orbitron', sans-serif;">
                  Enviar Solicitação via WhatsApp
                </button>
              </form>
            </div>

          </div>
        </div>
      </section>

      <!-- MAP SECTION -->
      <section class="h-[450px] w-full border-y border-[#22252D] relative overflow-hidden bg-[#0A0B0D]">
        <!-- Location Floating Card -->
        <div class="absolute top-6 left-6 z-10 bg-[#0A0B0D]/95 border border-[#22252D] p-5 rounded-xl shadow-2xl max-w-[280px] hidden sm:block backdrop-blur-md">
          <h4 class="text-white font-bold text-sm mb-2 uppercase" style="font-family: 'Orbitron', sans-serif;">Estacionamento Fácil</h4>
          <p class="text-xs text-gray-400 leading-relaxed mb-4">
            Estamos localizados na paralela da marginal, ao lado da antiga loja Maré Mansa. Fácil acesso e vagas na porta!
          </p>
          <a href="https://maps.app.goo.gl/wKqK6aG2L9c5n3Y8A" target="_blank" class="inline-flex items-center gap-1.5 text-xs text-[#FF5A1F] font-black uppercase hover:underline">
            <span>Abrir no Google Maps</span>
            <svg class="w-3.5 h-3.5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2.5"><path stroke-linecap="round" stroke-linejoin="round" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14" /></svg>
          </a>
        </div>

        <iframe 
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3968.9669527267156!2d-35.2166567241285!3d-5.860166294131238!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7b2f8a846c4f01f%3A0xc3b8398e090df4ad!2sAv.%20dos%20Pinheirais%2C%201043%20-%20Ne%C3%B3polis%2C%20Natal%20-%20RN%2C%2059080-250!5e0!3m2!1spt-BR!2sbr!4v1716320000000!5m2!1spt-BR!2sbr" 
          width="100%" 
          height="100%" 
          style="border:0; filter: grayscale(1) invert(0.9) contrast(1.2);" 
          allowfullscreen="true" 
          loading="lazy" 
          referrerpolicy="no-referrer-when-downgrade">
        </iframe>
      </section>
    </main>

    <!-- Footer component -->
    <CampellopneusFooter />
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

// Rotating Brands list
const brands = [
  'Michelin',
  'Pirelli',
  'Goodyear',
  'Bridgestone',
  'Continental',
  'Firestone',
  'Dunlop',
  'Yokohama',
  'Hankook',
  'Toyo Tires'
]

// Portfolio Photos list (using generic pics to avoid broken images)
const galleryPhotos = [
  { src: 'https://images.unsplash.com/photo-1598331668826-20cecb598cb8?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80', category: 'Manutenção', title: 'Revisão Premium', desc: 'Ajuste de suspensão e freios.' },
  { src: 'https://images.unsplash.com/photo-1580273916550-e323be2ae537?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80', category: 'Alinhamento', title: 'Alinhamento 3D', desc: 'Calibração milimétrica.' },
  { src: 'https://images.unsplash.com/photo-1579563294378-687f8f96409b?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80', category: 'Estrutura', title: 'Nova Oficina', desc: 'Espaço reformulado.' },
]

const services = [
  {
    icon: '<svg fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-7 h-7"><path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" /></svg>',
    title: 'Alinhamento 3D',
    desc: 'Alinhamento com sistema óptico computadorizado 3D de alta precisão.',
    price: 'R$ 9,99'
  },
  {
    icon: '<svg fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-7 h-7"><path stroke-linecap="round" stroke-linejoin="round" d="M12 21a9.004 9.004 0 008.716-6.747M12 21a9.004 9.004 0 01-8.716-6.747M12 21c2.485 0 4.5-4.03 4.5-9S14.485 3 12 3m0 18c-2.485 0-4.5-4.03-4.5-9S9.515 3 12 3m0 0a8.997 8.997 0 017.843 4.582" /></svg>',
    title: 'Balanceamento R.F.',
    desc: 'Balanceamento de rodas de ferro. Garante uma rodagem suave.',
    price: 'R$ 15,99'
  }
]

const testimonials = [
  {
    name: 'Roberto K.',
    role: 'Proprietário de Honda Civic',
    text: 'A estrutura está excelente! O atendimento foi transparente.'
  }
]

const formData = ref({
  name: '',
  phone: '',
  vehicle: '',
  message: ''
})

function submitForm() {
  const text = `Olá Campello Pneus!`
  const encodedText = encodeURIComponent(text)
  window.open(`https://wa.me/message/IPGIT7ZRZSKQK1?text=${encodedText}`, '_blank')
}
</script>

<style>
/* Smooth Scroll */
html {
  scroll-behavior: smooth;
}

@keyframes marquee {
  0% { transform: translateX(0%); }
  100% { transform: translateX(-50%); }
}
.animate-marquee {
  animation: marquee 22s linear infinite;
}
</style>
