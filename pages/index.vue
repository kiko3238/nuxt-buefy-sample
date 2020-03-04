<template>
  <section>
    <Hero/>
    <MainMessage/>
    <ProductFeature/>
    <ProductStats/>
    <ContactForm/>
    <Footer/>
  </section>
</template>

<script>
import Hero from '@/components/Hero'
import MainMessage from '@/components/MainMessage'
import ProductFeature from '@/components/ProductFeature'
import ProductStats from '@/components/ProductStats'
import ContactForm from '@/components/ContactForm'
import Footer from '@/components/Footer'

export default {
  components: {
    Hero, MainMessage, ProductFeature, ProductStats, ContactForm, Footer
  }
}
</script>