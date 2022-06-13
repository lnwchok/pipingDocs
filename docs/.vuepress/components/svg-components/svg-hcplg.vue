<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="-5 0 100 100"
    :width="size"
    :height="size"
  >
    <g stroke="black" stroke-width="2" fill="none">
      <path d="M33 30 l 0 45.7 l 45 0 l 0 -45.7 z" />
    </g>
    <!-- conn pipe -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M38.85 30 l 0 12.7 l 34 0 l 0 -12.7" />
    </g>
    <g stroke="black" stroke-width="1" fill="none">
      <path
        d="M38.85 30 l 0 -10 a 8.5 5, 0, 0 0, 17 0 a 8.5 5, 0, 0 1, 17 0 l 0 10"
      />
      <path d="M38.85 20 a 8.5 5, 0, 0 1, 17 0" />
    </g>
    <!-- center line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M55.85 13 l 0 70" />
    </g>
    <!-- Dimension -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M14.85 30 l 13.15 0" />
      <path d="M14.85 75 l 13.15 0" />
      <path d="M16.85 30 l 0 45" />
      <path d="M16.85 30 l -1.6 6" />
      <path d="M16.85 30 l 1.6 6" />
      <path d="M16.85 75 l -1.6 -6" />
      <path d="M16.85 75 l 1.6 -6" />
    </g>
    <g font-family="Arial" fill="black" stroke="none" text-anchor="end">
      <text x="12" y="58">{{ D }}</text>
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