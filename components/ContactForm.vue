<template>
  <div class="card">
    <p class="section-intro">Udfyld formularen, så kontakter vi dig inden for 24 timer.</p>
    <form class="form-grid" @submit.prevent="handleSubmit">
      <div class="form-row">
        <label for="name">Navn*</label>
        <input id="name" v-model="form.name" type="text" required placeholder="Dit fulde navn" />
      </div>
      <div class="form-row">
        <label for="phone">Telefon*</label>
        <input id="phone" v-model="form.phone" type="tel" required placeholder="+45 XX XX XX XX" />
      </div>
      <div class="form-row">
        <label for="email">E-mail*</label>
        <input id="email" v-model="form.email" type="email" required placeholder="kontakt@eksempel.dk" />
      </div>
      <div class="form-row">
        <label for="postcode">Postnummer*</label>
        <input id="postcode" v-model="form.postcode" type="text" required placeholder="2400" />
      </div>
      <div class="form-row" style="grid-column: span 2;">
        <label for="address">Adresse</label>
        <input id="address" v-model="form.address" type="text" placeholder="Vejnavn og husnummer" />
      </div>
      <div class="form-row" style="grid-column: span 2;">
        <label for="service">Valgt tjeneste*</label>
        <select id="service" v-model="form.service" required>
          <option value="Omfangsdræn">Omfangsdræn</option>
          <option value="Facaderenovering">Facaderenovering</option>
          <option value="Begge">Begge</option>
          <option value="Øvrigt">Øvrigt</option>
        </select>
      </div>
      <div class="form-row" style="grid-column: span 2;">
        <label for="message">Kort beskrivelse*</label>
        <textarea id="message" v-model="form.message" required placeholder="Beskriv kort dit behov"></textarea>
      </div>
      <div class="form-row" style="grid-column: span 2;">
        <label class="input-note"><input type="checkbox" v-model="form.accepted" required /> Jeg accepterer, at mine oplysninger behandles i henhold til <NuxtLink to="/privatlivspolitik/">privatlivspolitikken</NuxtLink>.</label>
      </div>
      <div class="form-footer" style="grid-column: span 2;">
        <button class="btn btn-primary" type="submit">Send ansøgning</button>
      </div>
    </form>
    <p class="input-note">Når du sender formularen, bliver du kontaktet med et gratis og uforpligtende tilbud.</p>
    <div v-if="submitted" class="form-success">
      Tak! Vi har modtaget din henvendelse og kontakter dig inden for 24 timer.
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue'
const submitted = ref(false)
const form = ref({
  name: '',
  phone: '',
  email: '',
  postcode: '',
  address: '',
  service: 'Omfangsdræn',
  message: '',
  accepted: false
})

function handleSubmit() {
  submitted.value = true
  form.value = {
    name: '',
    phone: '',
    email: '',
    postcode: '',
    address: '',
    service: 'Omfangsdræn',
    message: '',
    accepted: false
  }
}
</script>
