<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 -5 100 100"
    :width="size"
    :height="size"
  >
    <g stroke="black" stroke-width="2" fill="none">
      <path d='M10 32.15 l 17 0 l 0 40.85 l -4.85 4.85 l -12.5 0 z' />
      <path d='M22.15 90 l 0 -12.5 l 4.85 -4.85 l 36 0 l 4.85 4.85 l 0 12.5 z' />
      <path d='M63 32.15 l 17 0 l 0 45.7 l -12.5 0 l -4.85 -4.85 z' />
      <path d='M27 38 l 36 0' />
    </g>
    <!-- conn pipe -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d='M80 38 l -12.7 0 l 0 34 l 12.7 0' />    
    </g>
    <g stroke="black" stroke-width="1" fill="none">
      <path d='M80 38 l 10 0 a 5 8.5, 0, 0 1, 0 17 a 5 8.5, 0, 0 1, 0 17 l -10 0' />
      <path d='M90 38 a 5 8.5, 0, 0 0, 0 17' />
    </g>
    <!-- center line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d='M5 55 l 92 0' />
      <path d='M45 55 l 0 40' />
    </g>
    <!-- Dimension -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d='M45 14 l 0 36' />
      <path d='M80 14 l 0 13.15'/>
      <path d='M45 16 l 35 0' />
      <path d='M45 16 l6 -1.6' />
      <path d='M45 16 l6 1.6' />
      <path d='M80 16 l-6 -1.6' />
      <path d='M80 16 l-6 1.6' />
    </g>
    <g font-family="Arial" fill="black" stroke="none" text-anchor="middle">
      <text x="62" y="11">{{ D }}</text>
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