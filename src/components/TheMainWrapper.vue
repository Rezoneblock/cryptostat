<template>
  <div class="main">
    <h1>{{ title }}</h1>
    <TheCatalog />
    <TheCatalogItem />
    <TheCart />
  </div>
</template>

<script>


import TheCatalog from './TheCatalog.vue';
import TheCatalogItem from './Catalog-item.vue';
import TheCart from './TheCart.vue';


export default {
  name: 'TheMain',
  components: {
    TheCatalog,
    TheCatalogItem,
    TheCart,
  },
  props: {},
  data () { 
    return {
      title: 'Main',
    };
  }, 
  computed: {},
  watch: {},
  mounted() {
    console.log("Hello, World!");
  },
}
</script>
<style>
  .main-wrapper {
    display: flex;
  }
</style>