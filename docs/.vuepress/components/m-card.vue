<template>
  <div class="card">
    <div class="title">
      <h3>{{ title }}</h3>
    </div>
    <!-- <div> -->
      <slot />
    <!-- </div> -->
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
  },
};
</script>

<style lang="scss">

.card {
  position: relative;
  text-align: left;
  background: var(--c-bg);
  // border: 1px solid var(--c-text);
  // border-radius: 5px;
  padding: 5px 10px;
  margin: 0 0 5px 0;
}
.title {
  border-bottom: 1px solid var(--c-text);
  padding: 2px 5px;
}
.title h3 {
  margin-block: 0;
}


</style>
