<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 -5 100 100"
    :width="size"
    :height="size"
  >
    <g stroke="black" stroke-width="2" fill="none">
      <path d="M22.5 32.15 l 0 45.7 l 45 0 l 0 -45.7 z" />
    </g>
    <!-- conn pipe -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M22.5 38 l 12.7 0 l 0 34 l -12.7 0" />
      <path d="M67.5 38 l -12.7 0 l 0 34 l 12.7 0" />
    </g>
    <g stroke="black" stroke-width="1" fill="none">
      <path
        d="M22.5 38 l -10 0 a 5 8.5, 0, 0 0, 0 17 a 5 8.5, 0, 0 1, 0 17 l 10 0"
      />
      <path d="M12.5 55 a 5 8.5, 0, 0 0, 0 17" />
      <path
        d="M67.5 38 l 10 0 a 5 8.5, 0, 0 0, 0 17 a 5 8.5, 0, 0 1, 0 17 l -10 0"
      />
      <path d="M77.5 38 a 5 8.5, 0, 0 1, 0 17" />
    </g>
    <!-- center line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M5.5 55 l 78 0" />
    </g>
    <!-- Dimension -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M22.5 14 l 0 13.15" />
      <path d="M67.5 14 l 0 13.15" />
      <path d="M22.5 16 l 45 0" />
      <path d="M22.5 16 l6 -1.6" />
      <path d="M22.5 16 l6 1.6" />
      <path d="M67.5 16 l-6 -1.6" />
      <path d="M67.5 16 l-6 1.6" />
    </g>
    <g font-family="Arial" fill="black" stroke="none" text-anchor="middle">
      <text x="45" y="11">{{ D }}</text>
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