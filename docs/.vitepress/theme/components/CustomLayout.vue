<script setup lang="ts">
import DefaultTheme from 'vitepress/theme';
import Feedback from './Feedback/Feedback.vue';
import ViteConfBanner from './ViteConfBanner.vue';

const { Layout } = DefaultTheme;
</script>

<template>
  <Layout>
   <template #layout-top>
      <ViteConfBanner />
    </template>
    <template #doc-footer-before>
      <Feedback />
    </template>
  </Layout>
</template>
