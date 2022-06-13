<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 -5 100 100"
    :width="size"
    :height="size"
  >
    <circle
      cx="45"
      cy="60"
      r="30"
      stroke="black"
      stroke-width="2"
      fill="none"
    />
    <!-- center line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M10 60 l 70 0" />
      <path d="M45 25 l 0 70" />
    </g>
    <!-- Dimension -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M15 14 l0 28" />
      <path d="M75 14 l0 28" />
      <path d="M15 16 l 60 0" />
      <path d="M15 16 l6 -1.6" />
      <path d="M15 16 l6 1.6" />
      <path d="M75 16 l-6 -1.6" />
      <path d="M75 16 l-6 1.6" />
    </g>
    <g
      font-family="Arial"
      fill="black"
      stroke="none"
      text-anchor="middle"
    >
      <text x="45" y="11">{{ D }}</text>
    </g>
  </svg>
</template>


<script>
export default {
  props: {
    size: {
      default: '100%',
      type: String,
    },
    D: {
      default: 'D',
      type: String
    },
  },
};
</script>
