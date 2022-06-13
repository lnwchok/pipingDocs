<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 -5 100 100"
    :width="size"
    :height="size"
  >
    <g stroke="black" stroke-width="2" fill="none">
    <path d='M24.6 29.5 l 4 0 l 0 51 l -4 0 z' />
    <path d='M28.6 38 l 46.8 0 l 0 34 l -46.8 0' />
    </g>
    <!-- center line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d='M17.6 55 l 64.8 0' />
    </g>
    <!-- Dimension -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d='M24.6 12.35 l 0 12.15' />
      <path d='M75.4 12.35 l 0 20.65'/>
      <path d='M24.6 14.35 l 50.8 0' />
      <path d='M24.6 14.35 l6 -1.6' />
      <path d='M24.6 14.35 l6 1.6' />
      <path d='M75.4 14.35 l-6 -1.6' />
      <path d='M75.4 14.35 l-6 1.6' />   
    </g>
    <g font-family="Arial" fill="black" stroke="none" text-anchor="middle">
      <text x="50" y="11">{{ D }}</text>
    </g>
  </svg>
</template>


<script>
export default {
  props: {
    size: {
      default: "100%",
      type: String,
    },
    D: {
      default: "D",
      type: String,
    },
  },
};
</script>