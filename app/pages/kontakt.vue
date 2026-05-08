<template>
  <section class="section">
    <div class="container">
      <div class="section-intro">
        <h1>Kontakt os</h1>
        <p>Få en gratis og uforpligtende samtale om dit byggprojekt. Vi hjælper med fast pris eller tilbud på målt arbejde.</p>
      </div>

      <div class="grid-2" style="gap: 2rem; margin-top: 2rem;">
        <div>
          <div class="card section-light">
            <h2>Kontaktinformation</h2>
            <p><strong>Telefon:</strong> <a href="tel:+4512345678">+45 12 34 56 78</a></p>
            <p><strong>Email:</strong> <a href="mailto:kontakt@byggproffs.dk">kontakt@byggproffs.dk</a></p>
            <p><strong>Adresse:</strong> [DANSK ADRESSE]</p>
            <p><strong>CVR:</strong> [DANSKT CVR]</p>
          </div>

          <div class="card" style="margin-top: 1.5rem;">
            <h2>Hurtig rådgivning</h2>
            <p>Vi svarer typisk inden for 24 timer og kan aftale besigtigelse, prisoverslag eller opstart på renovering.</p>
          </div>
        </div>

        <div class="card">
          <h2>Send din forespørgsel</h2>
          <ContactForm />
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import ContactForm from '~/components/ContactForm.vue'

useHead({
  title: 'Kontakt | Byggproffs Danmark',
  meta: [
    { name: 'description', content: 'Kontakt Byggproffs Danmark for gratis besigtigelse, prisoverslag og rådgivning om renovering og ombygning.' }
  ]
})
</script>
