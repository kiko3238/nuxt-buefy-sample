<template>
  <section>
    <Hero/>
    <MainMessage/>
    <ProductFeature/>
    <ProductStats/>
    <Footer/>
  </section>
</template>

<script>
import Hero from '@/components/Hero'
import MainMessage from '@/components/MainMessage'
import ProductFeature from '@/components/ProductFeature'
import ProductStats from '@/components/ProductStats'
import Footer from '@/components/Footer'

export default {
  components: {
    Hero, MainMessage, ProductFeature, ProductStats, Footer
  }
}
</script>