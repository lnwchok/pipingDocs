<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 0 100 100"
    :width="size"
    :height="size"
  >
    <g stroke="black" stroke-width="2" fill="none">
      <path d="M10 42 l 35 0 l 0 26 l -35 0 z" />
      <path d="M49 38 l 41 0 l 0 34 l -41 0 z" />
      <path d="M45 42 l 4 -4 " />
      <path d="M45 68 l 4 4 " />
    </g>
    <!-- center line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M3 55 l 94 0" />
    </g>
    <!-- Dimension -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M10 19.85 l 0 17.15" />
      <path d="M90 19.85 l 0 13.15" />
      <path d="M10 21.85 l 80 0" />
      <path d="M10 21.85 l6 -1.6" />
      <path d="M10 21.85 l6 1.6" />
      <path d="M90 21.85 l-6 -1.6" />
      <path d="M90 21.85 l-6 1.6" />
    </g>
    <g font-family="Arial" fill="black" stroke="none" text-anchor="middle">
      <text x="50" y="18">{{ D }}</text>
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