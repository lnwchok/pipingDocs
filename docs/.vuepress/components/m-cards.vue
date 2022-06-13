<template>
  <div class="container">
    <!-- <m-card-pipe />
    <m-card title="Elbow">Elbow Description</m-card>
    <m-card title="Flange">Flange Description</m-card> -->

    <pipe />
  </div>
</template>

<script>
// import mCardVue from './m-card.vue';
// import mCardPipeVue from './m-card-pipe.vue';

export default {
  // components: {
  //   mCard: mCardVue,
  //   mCardPipe: mCardPipeVue,
  // },
};
</script>

<style lang="scss">
@import '@vuepress/theme-default/lib/client/styles';

.container {
  display: flex;
  flex-direction: column;
}
</style>
