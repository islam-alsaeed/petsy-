<template>
  <div>
    <VmHero></VmHero>
    <VmProductsList></VmProductsList>
    <p>jjjjjjjjjjjjjjjjjjjjjjjjjjjjjj</p>
    <p>hello menna</p>
    <p>hello 2</p>
    <p>test</p>
  </div>
</template>

<script>
import VmProductsList from '@/components/products_list/ProductsListContainer';
import VmHero from '@/components/hero/Hero';

export default {
  name: 'index',
  components: {
    VmProductsList,
    VmHero
  }
};
</script>
