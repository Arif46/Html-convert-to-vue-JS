<template>
   <header-section></header-section>
    <router-view></router-view>
   <news-letter></news-letter>
   <footer-section></footer-section>
</template>
<script>
import HeaderSection from '@/components/frontend/Header'
import NewsLetter from '@/components/frontend/NewsLetter.vue';
import FooterSection from '@/components/frontend/Footer.vue';
export default {
  name: 'Master',
    components: {
      HeaderSection,
      NewsLetter,
      FooterSection
    }
};
</script>
