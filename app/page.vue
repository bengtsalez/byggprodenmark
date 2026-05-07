<template>
  <section class="hero">
    <div class="container hero-content">
      <p class="eyebrow">Gratis besigtigelse · Uforpligtende tilbud</p>
      <h1>Specialister i omfangsdræn og facaderenovering</h1>
      <p class="hero-subtitle">Tør kælder, holdbar facade og dansk service. Få gratis tilbud og professionel hjælp fra Byggproffs Danmark.</p>
      <div class="hero-actions">
        <NuxtLink to="/kontakt/" class="btn btn-primary">Få gratis tilbud</NuxtLink>
        <NuxtLink to="/kontakt/" class="btn btn-secondary">Book gratis besigtigelse</NuxtLink>
      </div>
    </div>
  </section>

  <section class="section section-light">
    <div class="container feature-grid">
      <div class="card card-strong">
        <h3>Professionel rådgivning</h3>
        <p>Vi gennemgår dit projekt og anbefaler den mest sikre løsning uden omkostning.</p>
      </div>
      <div class="card card-strong">
        <h3>Gratis besigtigelse</h3>
        <p>Vi kommer ud, vurderer fugt og facade og giver dig et klart, uforpligtende tilbud.</p>
      </div>
      <div class="card card-strong">
        <h3>Dansk service</h3>
        <p>Lokalt fokus på Danmark med dansk kontakt, telefonnummer og serviceområde.</p>
      </div>
      <div class="card card-strong">
        <h3>Tryg proces</h3>
        <p>Tydelig tidsplan, dokumentation og ansvarlig opfølgning fra start til slut.</p>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <div class="section-intro">
        <h2>Vælg den rette løsning for dit hus</h2>
        <p>Vi koncentrerer os om to stærke tilbud: omfangsdræn, der holder kælderen tør, og facaderenovering, der skaber bedre isolation og et moderne udtryk.</p>
      </div>
      <div class="grid-2" style="margin-top: 2rem;">
        <ServiceCard
          title="Omfangsdræn"
          description="Beskyt dit fundament og din kælder mod fugt, skimmel og vandskader."
          :items="['Effektiv vandafledning', 'Beskyttelse af sokkel og fundament', 'Langtidsholdbar løsning']"
          link="/omfangsdraen/"
        />
        <ServiceCard
          title="Facaderenovering"
          description="Forny facaden, øg isoleringen og forbedr husets energiprofil."
          :items="['Pudsning og efterisolering', 'Omfangsdræn og facade i helhed', 'Holdbar finish med dokumenteret kvalitet']"
          link="/facaderenovering/"
        />
      </div>
    </div>
  </section>

  <section class="section section-light">
    <div class="container">
      <h2>Sådan arbejder vi</h2>
      <div class="grid-2" style="margin-top: 2rem;">
        <div class="card">
          <h3>1. Gratis besigtigelse</h3>
          <p>Vi kommer ud, vurderer jord-, dræn- og facadeforhold, og giver dig et klart billede af behovet.</p>
        </div>
        <div class="card">
          <h3>2. Uforpligtende tilbud</h3>
          <p>Du får et skriftligt tilbud uden skjulte omkostninger og med tydelig tidsplan.</p>
        </div>
        <div class="card">
          <h3>3. Aftale og udførelse</h3>
          <p>Vi planlægger arbejdet professionelt og udfører det med ansvarlige håndværkere.</p>
        </div>
        <div class="card">
          <h3>4. Dokumentation</h3>
          <p>Efter afsluttet projekt får du dokumentation, kontaktperson og vejledning i vedligeholdelse.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <h2>Ofte stillede spørgsmål</h2>
      <div class="grid-2" style="margin-top: 1.5rem; gap: 1rem;">
        <FaqItem question="Hvornår skal jeg overveje omfangsdræn?">
          Hvis du oplever fugtskjolder på væggene, skimmelsvamp eller vand i kælderen, er et omfangsdræn ofte løsningen.
        </FaqItem>
        <FaqItem question="Hvad koster facaderenovering?">
          Prisen afhænger af facadeareal, materialer og isoleringsniveau. Vi giver et konkret tilbud efter gratis besigtigelse.
        </FaqItem>
        <FaqItem question="Er I operationelle i hele Danmark?">
          Vi dækker primært Sjælland og Storkøbenhavn. Kontakt os, så besvarer vi din forespørgsel hurtigt.
        </FaqItem>
        <FaqItem question="Hvordan fungerer gratis besigtigelse?">
          Vi booker en tid, gennemgår dit projekt, og du får et uforpligtende tilbud uden ekstra omkostninger.
        </FaqItem>
      </div>
    </div>
  </section>

  <section class="section section-light">
    <div class="container">
      <div class="card">
        <h2>Vil du have hjælp til dit næste projekt?</h2>
        <p>Kontakt os i dag for et gratis og uforpligtende tilbud på omfangsdræn eller facaderenovering.</p>
        <div class="hero-actions" style="margin-top: 1.5rem;">
          <NuxtLink to="/kontakt/" class="btn btn-primary">Få gratis tilbud</NuxtLink>
          <a class="btn btn-secondary" href="tel:+4512345678">Ring nu</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
useHead({
  title: 'Omfangsdræn & Facaderenovering | Byggproffs Danmark',
  meta: [
    {
      name: 'description',
      content: 'Specialister i omfangsdræn og facaderenovering. Gratis besigtigelse, uforpligtende tilbud og dansk service fra Byggproffs Danmark.'
    }
  ]
})
</script>
