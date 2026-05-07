<template>
  <div class="app-shell">
    <header class="site-header">
      <div class="container header-inner">
        <NuxtLink to="/" class="brand">Byggproffs Danmark</NuxtLink>
        <nav class="site-nav" aria-label="Hovednavigation">
          <NuxtLink to="/omfangsdraen/">Omfangsdræn</NuxtLink>
          <NuxtLink to="/facaderenovering/">Facaderenovering</NuxtLink>
          <NuxtLink to="/referencer/">Referencer</NuxtLink>
          <NuxtLink to="/kontakt/">Kontakt</NuxtLink>
        </nav>
        <a class="btn btn-tertiary" href="tel:+4512345678">Ring nu</a>
      </div>
    </header>

    <main>
      <NuxtPage />
    </main>

    <footer class="site-footer">
      <div class="container footer-grid">
        <div>
          <p class="footer-brand">Byggproffs Danmark</p>
          <p>Dansk filial av Byggproffs Skåne AB</p>
          <p>CVR: [DANSKT CVR]</p>
          <p>Adresse: [DANSK ADRESS]</p>
          <p>Telefon: +45 12 34 56 78</p>
        </div>
        <div>
          <h2>Snabb kontakt</h2>
          <p><a href="tel:+4512345678">+45 12 34 56 78</a></p>
          <p><a href="mailto:kontakt@byggproffs.dk">kontakt@byggproffs.dk</a></p>
        </div>
        <div>
          <h2>Virksomhed</h2>
          <NuxtLink to="/om-byggproffs-danmark/">Om os</NuxtLink>
          <NuxtLink to="/privatlivspolitik/">Privatlivspolitik</NuxtLink>
          <NuxtLink to="/cookies/">Cookiepolitik</NuxtLink>
          <NuxtLink to="/vilkaar/">Vilkår</NuxtLink>
        </div>
      </div>
      <div class="footer-bottom">
        <p>© 2026 Byggproffs Danmark. Alle rettigheder forbeholdes.</p>
      </div>
    </footer>
  </div>
</template>

<script setup>
</script>
