<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 -5 100 100"
    :width="size"
    :height="size"
  >
    <g stroke="black" stroke-width="2" fill="none">
      <path d="M7 73 l 0 17 l 45.17 0 l 0 -12.15 l -4.85 -4.85 z" />
      <path d="M48 32 l 17 0 l 0 45.17 l -12.15 0 l -4.85 -4.85 z" />
      <path d="M47.85 38 l -18 0 a 17 17, 0, 0 0, -17 17 l 0 18" />
    </g>
    <!-- conn pipe -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M64.85 38 l -12.7 0 l 0 34 l 12.7 0" />
    </g>
    <g stroke="black" stroke-width="1" fill="none">
      <path
        d="M64.85 38 l 10 0 a 5 8.5, 0, 0 1, 0 17 a 5 8.5, 0, 0 1, 0 17 l -10 0"
      />
      <path d="M73.85 38 a 5 8.5, 0, 0 0, 0 17" />
    </g>
    <!-- center line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d='M9.85 55 l 72 0' />
      <path d='M29.85 35 l 0 60' />
    </g>
    <!-- Dimension -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d='M29.85 14 l 0 16' />
      <path d='M64.85 14 l 0 13.15'/>
      <path d='M29.85 16 l 35 0' />
      <path d='M29.85 16 l6 -1.6' />
      <path d='M29.85 16 l6 1.6' />
      <path d='M64.85 16 l-6 -1.6' />
      <path d='M64.85 16 l-6 1.6' />
    </g>
    <g font-family="Arial" fill="black" stroke="none" text-anchor="middle">
      <text x="47" y="11">{{ D }}</text>
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