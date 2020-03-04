<template>
  <section>
    <Hero/>
    <MainMessage/>
    <ProductFeature/>
    <ProductStats/>
    <Carousel/>
    <ContactForm/>
    <Footer/>
  </section>
</template>

<script>
import Hero from '@/components/Hero'
import MainMessage from '@/components/MainMessage'
import ProductFeature from '@/components/ProductFeature'
import ProductStats from '@/components/ProductStats'
import Carousel from '@/components/Carousel'
import ContactForm from '@/components/ContactForm'
import Footer from '@/components/Footer'

export default {
  components: {
    Hero, MainMessage, ProductFeature, ProductStats,
    Carousel, ContactForm, Footer
  }
}
</script>