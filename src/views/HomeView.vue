<template>
  <Banner />
  <div class="main-container">
    <h1>Mount your precious:</h1>
    <BurgerForm />
  </div>
</template>

<script lang="ts">
import Banner from '@/components/Banner.vue';
import BurgerForm from '@/components/BurgerForm.vue';
import { defineComponent } from 'vue';

export default defineComponent({
  components: { Banner, BurgerForm },
  name: 'HomeView',
});
</script>
