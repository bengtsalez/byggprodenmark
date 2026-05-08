<template>
  <div class="min-h-screen flex flex-col bg-gray-50">
    <header class="sticky top-0 z-50 bg-white border-b border-gray-200 shadow-sm">
      <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex items-center justify-between h-16 gap-4">
          <NuxtLink to="/" class="navbar-brand" aria-label="Gå till startsidan">
            <NuxtImg
    src="/BYGGPRO-LOGO.png"
    alt="Min sajt"
    width="140"
    height="40"
    class="navbar-logo"
  />
          </NuxtLink>
          <nav class="hidden md:flex items-center gap-6">
            <NuxtLink to="/omfangsdraen/" class="text-slate-600 hover:text-brand text-sm font-medium transition-colors">Omfangsdræn</NuxtLink>
            <NuxtLink to="/facaderenovering/" class="text-slate-600 hover:text-brand text-sm font-medium transition-colors">Facaderenovering</NuxtLink>
            <NuxtLink to="/referencer/" class="text-slate-600 hover:text-brand text-sm font-medium transition-colors">Referencer</NuxtLink>
            <NuxtLink to="/kontakt/" class="text-slate-600 hover:text-brand text-sm font-medium transition-colors">Kontakt</NuxtLink>
          </nav>
          <a href="tel:+4512345678" class="shrink-0 bg-accent hover:bg-accent-dark text-white text-sm font-semibold px-5 py-2.5 rounded-full transition-colors">
            Ring nu
          </a>
        </div>
      </div>
    </header>

    <main class="flex-1">
      <slot />
    </main>

    <footer class="bg-brand text-white">
      <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="space-y-1.5">
            <p class="font-bold text-lg">Byggproffs Danmark</p>
            <p class="text-sm text-blue-200">Dansk filial av Byggproffs Skåne AB</p>
            <p class="text-sm text-blue-200">CVR: [DANSKT CVR]</p>
            <p class="text-sm text-blue-200">Adresse: [DANSK ADRESS]</p>
            <p class="text-sm text-blue-200">Telefon: +45 12 34 56 78</p>
          </div>
          <div>
            <h2 class="font-semibold mb-3">Kontakt</h2>
            <div class="space-y-1.5">
              <p class="text-sm text-blue-200">
                <a href="tel:+4512345678" class="hover:text-white transition-colors">+45 12 34 56 78</a>
              </p>
              <p class="text-sm text-blue-200">
                <a href="mailto:kontakt@byggproffs.dk" class="hover:text-white transition-colors">kontakt@byggproffs.dk</a>
              </p>
            </div>
          </div>
          <div>
            <h2 class="font-semibold mb-3">Virksomhed</h2>
            <div class="flex flex-col gap-1.5">
              <NuxtLink to="/om-byggproffs-danmark/" class="text-sm text-blue-200 hover:text-white transition-colors">Om os</NuxtLink>
              <NuxtLink to="/privatlivspolitik/" class="text-sm text-blue-200 hover:text-white transition-colors">Privatlivspolitik</NuxtLink>
              <NuxtLink to="/cookies/" class="text-sm text-blue-200 hover:text-white transition-colors">Cookiepolitik</NuxtLink>
              <NuxtLink to="/vilkaar/" class="text-sm text-blue-200 hover:text-white transition-colors">Vilkår</NuxtLink>
            </div>
          </div>
        </div>
        <div class="mt-10 pt-8 border-t border-white/20 text-center text-sm text-blue-300">
          <p>© 2026 Byggproffs Danmark. Alle rettigheder forbeholdes.</p>
        </div>
      </div>
    </footer>
  </div>
</template>
