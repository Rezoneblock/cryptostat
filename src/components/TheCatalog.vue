<template>
  <div class="catalog">
    catalog
    <TheCatalogItem />
  </div>
</template>

<script>

import TheCatalogItem from './Catalog-item.vue';


export default {
  name: 'TheCatalog',  
  props: {},
  components: {
    TheCatalogItem,
  },
  data() {
    return {};
  },
}
</script>

<style>
  
</style>