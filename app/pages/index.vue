<template>
  <!-- Hero -->
  <section class="bg-gradient-to-br from-brand to-brand-dark text-white py-24 lg:py-32">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <p class="text-accent text-sm font-semibold uppercase tracking-widest mb-4">
        Gratis besigtigelse · Uforpligtende tilbud
      </p>
      <h1 class="text-4xl sm:text-5xl lg:text-6xl font-bold leading-tight mb-6 max-w-3xl">
        Specialister i omfangsdræn og facaderenovering
      </h1>
      <p class="text-blue-100 text-lg lg:text-xl mb-10 max-w-2xl leading-relaxed">
        Tør kælder, holdbar facade og dansk service. Få gratis tilbud og professionel hjælp fra Byggproffs Danmark.
      </p>
      <div class="flex flex-col sm:flex-row gap-4">
        <NuxtLink
          to="/kontakt/"
          class="bg-accent hover:bg-accent-dark text-white font-semibold px-8 py-4 rounded-full text-center transition-colors"
        >
          Få gratis tilbud
        </NuxtLink>
        <NuxtLink
          to="/kontakt/"
          class="border-2 border-white/40 hover:bg-white/10 text-white font-semibold px-8 py-4 rounded-full text-center transition-colors"
        >
          Book gratis besigtigelse
        </NuxtLink>
      </div>
    </div>
  </section>

  <!-- Trust badges -->
  <section class="bg-white py-16">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <div class="bg-brand text-white rounded-2xl p-6">
          <h3 class="font-semibold text-lg mb-2">Professionel rådgivning</h3>
          <p class="text-blue-200 text-sm leading-relaxed">Vi gennemgår dit projekt og anbefaler den mest sikre løsning uden omkostning.</p>
        </div>
        <div class="bg-brand text-white rounded-2xl p-6">
          <h3 class="font-semibold text-lg mb-2">Gratis besigtigelse</h3>
          <p class="text-blue-200 text-sm leading-relaxed">Vi kommer ud, vurderer fugt og facade og giver dig et klart, uforpligtende tilbud.</p>
        </div>
        <div class="bg-brand text-white rounded-2xl p-6">
          <h3 class="font-semibold text-lg mb-2">Dansk service</h3>
          <p class="text-blue-200 text-sm leading-relaxed">Lokalt fokus på Danmark med dansk kontakt, telefonnummer og serviceområde.</p>
        </div>
        <div class="bg-brand text-white rounded-2xl p-6">
          <h3 class="font-semibold text-lg mb-2">Tryg proces</h3>
          <p class="text-blue-200 text-sm leading-relaxed">Tydelig tidsplan, dokumentation og ansvarlig opfølgning fra start til slut.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Services -->
  <section class="bg-gray-50 py-20">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="max-w-2xl mb-12">
        <h2 class="text-3xl sm:text-4xl font-bold text-slate-900 mb-4">
          Vælg den rette løsning for dit hus
        </h2>
        <p class="text-slate-600 text-lg leading-relaxed">
          Vi koncentrerer os om to stærke tilbud: omfangsdræn, der holder kælderen tør, og facaderenovering, der skaber bedre isolation og et moderne udtryk.
        </p>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
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

  <!-- Process -->
  <section class="bg-white py-20">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl sm:text-4xl font-bold text-slate-900 mb-12">Sådan arbejder vi</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <div class="border border-gray-200 rounded-2xl p-6">
          <div class="text-accent font-bold text-2xl mb-3">1</div>
          <h3 class="font-semibold text-slate-900 mb-2">Gratis besigtigelse</h3>
          <p class="text-slate-500 text-sm leading-relaxed">Vi kommer ud, vurderer jord-, dræn- og facadeforhold, og giver dig et klart billede af behovet.</p>
        </div>
        <div class="border border-gray-200 rounded-2xl p-6">
          <div class="text-accent font-bold text-2xl mb-3">2</div>
          <h3 class="font-semibold text-slate-900 mb-2">Uforpligtende tilbud</h3>
          <p class="text-slate-500 text-sm leading-relaxed">Du får et skriftligt tilbud uden skjulte omkostninger og med tydelig tidsplan.</p>
        </div>
        <div class="border border-gray-200 rounded-2xl p-6">
          <div class="text-accent font-bold text-2xl mb-3">3</div>
          <h3 class="font-semibold text-slate-900 mb-2">Aftale og udførelse</h3>
          <p class="text-slate-500 text-sm leading-relaxed">Vi planlægger arbejdet professionelt og udfører det med ansvarlige håndværkere.</p>
        </div>
        <div class="border border-gray-200 rounded-2xl p-6">
          <div class="text-accent font-bold text-2xl mb-3">4</div>
          <h3 class="font-semibold text-slate-900 mb-2">Dokumentation</h3>
          <p class="text-slate-500 text-sm leading-relaxed">Efter afsluttet projekt får du dokumentation, kontaktperson og vejledning i vedligeholdelse.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="bg-gray-50 py-20">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl sm:text-4xl font-bold text-slate-900 mb-12">Ofte stillede spørgsmål</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
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

  <!-- Bottom CTA -->
  <section class="bg-brand py-20">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="max-w-2xl">
        <h2 class="text-3xl sm:text-4xl font-bold text-white mb-4">
          Vil du have hjælp til dit næste projekt?
        </h2>
        <p class="text-blue-200 text-lg mb-10 leading-relaxed">
          Kontakt os i dag for et gratis og uforpligtende tilbud på omfangsdræn eller facaderenovering.
        </p>
        <div class="flex flex-col sm:flex-row gap-4">
          <NuxtLink
            to="/kontakt/"
            class="bg-accent hover:bg-accent-dark text-white font-semibold px-8 py-4 rounded-full text-center transition-colors"
          >
            Få gratis tilbud
          </NuxtLink>
          <a
            href="tel:+4512345678"
            class="border-2 border-white/40 hover:bg-white/10 text-white font-semibold px-8 py-4 rounded-full text-center transition-colors"
          >
            Ring nu
          </a>
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
