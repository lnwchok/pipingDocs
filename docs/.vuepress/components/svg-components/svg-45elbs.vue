<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 -5 100 100"
    :width="size"
    :height="size"
  >
    <g stroke="black" stroke-width="2" fill="none">
      <path d="M22.13 45.56 l -12.02 12.02 l 32.31 32.31 l 12.02 -12.02 z" />
      <path d="M54.5 32.15 l 17 0 l 0 45.17 l -17 0 z" />
      <path d="M54.5 38 l -9.5 0 a 17 17, 0, 0 0, -12.02 4.98 l -6.72 6.72" />
    </g>
    <!-- conn pipe -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M71.5 38 l -12.7 0 l 0 34 l 12.7 0" />
    </g>
    <g stroke="black" stroke-width="1" fill="none">
      <path
        d="M71.5 38 l 10 0 a 5 8.5, 0, 0 1, 0 17 a 5 8.5, 0, 0 1, 0 17 l -10 0"
      />
      <path d="M81.5 38 a 5 8.5, 0, 0 0, 0 17" />
    </g>
    <!-- center line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M22.73 77.27 l 22.27 -22.27 l 43.5 0" />
    </g>
    <!-- Dimension -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M45 14 l 0 36" />
      <path d="M71.5 14 l 0 13.15" />
      <path d="M45 16 l 26.5 0" />
      <path d="M45 16 l6 -1.6" />
      <path d="M45 16 l6 1.6" />
      <path d="M71.5 16 l-6 -1.6" />
      <path d="M71.5 16 l-6 1.6" />
    </g>
    <g font-family="Arial" fill="black" stroke="none" text-anchor="middle">
      <text x="58" y="11">{{ D }}</text>
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