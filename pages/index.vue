<template>
  <section>
    <Hero/>
    <MainMessage/>
    <ProductFeature/>
    <Footer/>
  </section>
</template>

<script>
import Hero from '@/components/Hero'
import MainMessage from '@/components/MainMessage'
import ProductFeature from '@/components/ProductFeature'
import Footer from '@/components/Footer'

export default {
  components: {
    Hero, MainMessage, ProductFeature, Footer
  }
}
</script>