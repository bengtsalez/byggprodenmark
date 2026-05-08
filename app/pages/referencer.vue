<template>
  <section class="section section-light">
    <div class="container">
      <div class="section-intro">
        <h1>Referencer</h1>
        <p>Se eksempler på vores tidligere renoverings- og byggeprojekter. Vi leverer kvalitet og god håndværk til private boligejere.</p>
      </div>

      <div class="grid-3" style="margin-top: 2rem; gap: 1.5rem;">
        <div class="card">
          <h2>Renoveret sommerhus</h2>
          <p>Facaderenovering og isolering af sommerhus, der forbedrede indeklima og udtryk.</p>
        </div>
        <div class="card">
          <h2>Kælderdøre & omfangsdræn</h2>
          <p>Komplet fugtbeskyttelse med nyt dræn og tætning af kældervægge.</p>
        </div>
        <div class="card">
          <h2>Tag og facade på villa</h2>
          <p>Udskiftning af tag og ny facade opnåede både holdbarhed og lavere varmeudgifter.</p>
        </div>
      </div>

      <div class="section-divider"></div>

      <div class="card">
        <h2>Hvad vores kunder siger</h2>
        <p>"Byggproffs Danmark gennemførte vores facaderenovering til aftalt tid og pris. Vi er glade for både service og resultat."</p>
      </div>

      <div class="section-divider"></div>

      <div class="card section-light">
        <h2>Vil du høre mere?</h2>
        <p>Kontakt os for at få konkrete referencer og et gratis tilbud, der matcher dit byggeri og budget.</p>
        <NuxtLink to="/kontakt/" class="btn btn-primary">Kontakt os</NuxtLink>
      </div>
    </div>
  </section>
</template>

<script setup>
useHead({
  title: 'Referencer | Byggproffs Danmark',
  meta: [
    { name: 'description', content: 'Se tidligere renoveringsprojekter og kundeudtalelser fra Byggproffs Danmark.' }
  ]
})
</script>
