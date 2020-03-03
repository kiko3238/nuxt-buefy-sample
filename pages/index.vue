<template>
  <section>
    <Hero/>
    <MainMessage/>
    <Footer/>
  </section>
</template>

<script>
import Hero from '@/components/Hero'
import MainMessage from '@/components/MainMessage'
import Footer from '@/components/Footer'

export default {
  components: {
    Hero, MainMessage, Footer
  }
}
</script>