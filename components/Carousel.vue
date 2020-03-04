<template>
  <b-carousel
    :autoplay="true"
    :repeat="true"
    :pause-hover="true"
    :pause-info="true"
    with-carousel-list
    :indicator="false">
    <b-carousel-item v-for="(item, i) in items" :key="i">
      <figure class="image">
        <img :src="item.image">
      </figure>
    </b-carousel-item>
    <template slot="list" slot-scope="props">
      <b-carousel-list
        v-model="props.active"
        :data="items"
        :config="al"
        @switch="props.switch($event, false)"
        as-indicator />
    </template>
  </b-carousel>
</template>

<script>
export default {
  data() {
    return {
      al: {
        hasOpacity: true,
        itemsToShow: 2,
        breakpoints: {
          768: {
            hasOpacity: true,
            itemsToShow: 4
          },
          960: {
            hasOpacity: true,
            itemsToShow: 6
          }
        }
      },
      items: [
        {
          title: 'Slide 1',
          image: 'https://picsum.photos/id/0/1230/500'
        },
        {
          title: 'Slide 2',
          image: 'https://picsum.photos/id/1/1230/500'
        },
        {
          title: 'Slide 3',
          image: 'https://picsum.photos/id/2/1230/500'
        },
        {
          title: 'Slide 4',
          image: 'https://picsum.photos/id/3/1230/500'
        },
        {
          title: 'Slide 5',
          image: 'https://picsum.photos/id/4/1230/500'
        },
        {
          title: 'Slide 6',
          image: 'https://picsum.photos/id/5/1230/500'
        },
        {
          title: 'Slide 7',
          image: 'https://picsum.photos/id/6/1230/500'
        },
        {
          title: 'Slide 8',
          image: 'https://picsum.photos/id/7/1230/500'
        }
      ]
    }
  }
}
</script>

<style lang="scss">

</style>