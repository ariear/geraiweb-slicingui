<template>
  <Nav />
  <Home />
  <Pricing />
  <Services />
  <Contact />
  <Footer />
</template>

<script>
import Nav from './components/Nav.vue'
import Home from './views/Home.vue'
import Pricing from './views/Pricing.vue'
import Services from './views/Services.vue'
import Contact from './views/Contact.vue'
import Footer from './components/Footer.vue'
export default {
  components: { Nav, Home, Pricing, Services, Contact, Footer },

}
</script>