<template>
  <section class="section">
    <div class="container">
      <div class="section-intro">
        <h1>Om Byggproffs Danmark</h1>
        <p>Vi er et dansk håndværkerfirma med fokus på kvalitet, tryghed og hurtig service inden for renovering og isolering.</p>
      </div>

      <div class="grid-2" style="margin-top: 2rem; gap: 1.5rem;">
        <div class="card">
          <h2>Vores mission</h2>
          <p>At gøre renovering og isolering enkelt, økonomisk og holdbart for danske boligejere. Vi prioriterer fagligt håndværk og god kommunikation.</p>
        </div>
        <div class="card">
          <h2>Vores team</h2>
          <p>Erfarne håndværkere og projektledere sikrer ordentlig udførelse, materialer i høj kvalitet og fleksible løsninger med fast pris.</p>
        </div>
      </div>

      <div class="section-divider"></div>

      <div class="card">
        <h2>Vores tilgang</h2>
        <ul>
          <li>Gratis besigtigelse og rådgivning</li>
          <li>Fokus på fugtsikring og energieffektivitet</li>
          <li>Fast pris eller klart tilbud</li>
          <li>Ordentlig opfølgning og dokumentation</li>
        </ul>
      </div>

      <div class="section-divider"></div>

      <div class="grid-2" style="margin-top: 2rem; gap: 1.5rem;">
        <div class="card section-light">
          <h2>For private boligejere</h2>
          <p>Vi arbejder primært for villa- og rækkehusejere, der ønsker en holdbar løsning på fugt, isolering og facadeproblemer.</p>
        </div>
        <div class="card section-light">
          <h2>Fokus på tryghed</h2>
          <p>Al kommunikation sker på dansk, og du får en klar tidsplan, garanti og en dedikeret kontaktperson til dit projekt.</p>
        </div>
      </div>

      <div class="section-light card" style="margin-top: 2rem;">
        <h2>Kontakt os i dag</h2>
        <p>Få en gratis vurdering og tilbud på dit renoveringsprojekt. Vi er klar til at hjælpe med både små og større opgaver.</p>
        <NuxtLink to="/kontakt/" class="btn btn-primary">Kontakt os</NuxtLink>
      </div>
    </div>
  </section>
</template>

<script setup>
useHead({
  title: 'Om Byggproffs Danmark',
  meta: [
    { name: 'description', content: 'Læs om Byggproffs Danmark, vores mission og vores tilgang til facaderenovering, isolering og fugtsikring.' }
  ]
})
</script>
