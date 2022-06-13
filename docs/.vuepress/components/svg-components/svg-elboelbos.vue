<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 50 260 60"
    :width="size1"
    :height="size2"
  >
    <g stroke="black" stroke-width="2" fill="none">
      <path d="M7.15 55 l 0 17 l 40.85 0 l 4.85 -4.85 l 0 -12.15 z" />
      <path d="M48 72 l 0 40.85 l 17 0 l 0 -45.7 l -12.15 0" />
      <path d="M13 72 l 0 18 a 17 17, 0, 0 0, 17 17 l 18 0" />
      <path d="M65 73 l 45 0" />
      <path d="M65 107 l 45 0" />
      <path d="M110 67.15 l 0 45.7 l 12.15 0 l 4.85 -4.85 l 0 -40.85 z" />
      <path d="M127 108 l -4.85 4.85 l 0 12.15 l 45.7 0 l 0 -17 z" />
      <path d="M127 73 l 18 0 a 17 17, 0, 0 1, 17 17 l 0 18" />
      <path d="M163 77 l 0 -9.85 l 17 0 l 0 45.7 l -9.5 0" />
    </g>
    <!-- center line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M30 38 l 0 72" />
      <path d="M10 90 l 187 0" />
      <path d="M145 70 l 0 72" />
    </g>
    <g stroke="black" stroke-width="1" fill="none">
      <path
        d="M13 55 l 0 -10 a 8.5 5, 0, 0 1, 17 0 a 8.5 5, 0, 0 1, 17 0 l 0 10 M13 45 a 8.5 5, 0, 0 0, 17 0"
      />
      <path
        d="M128 125 l 0 10 a 8.5 5, 0, 0 1, 17 0 a 8.5 5, 0, 0 0, 17 0 l 0 -10 M128 135 a 8.5 5, 0, 0 0, 17 0"
      />
      <path
        d="M180 73 l 10 0 a 5 8.5, 0, 0 0, 0 17 a 5 8.5, 0, 0 1, 0 17 l -10 0 M190 73 a 5 8.5, 0, 0 1, 0 17"
      />
    </g>
    <!-- hidden line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M13 55 l 0 12.7 l 34 0 l 0 -12.7" />
      <path d="M128 125 l 0 -12.7 l 34 0 l 0 12.7" />
      <path d="M180 73 l -12.7 0 l 0 34 l 12.7 0" />
    </g>
    <!-- Dimension -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M30 19.85 l 0 13.15" />
      <path d="M145 19.85 l 0 45.15" />
      <path d="M30 21.85 l 115 0" />
      <path d="M30 21.85 l6 -1.6" />
      <path d="M30 21.85 l6 1.6" />
      <path d="M145 21.85 l-6 -1.6" />
      <path d="M145 21.85 l-6 1.6" />
    </g>
    <g font-family="Arial" fill="black" stroke="none" text-anchor="middle">
      <text x="87" y="15">{{ D }}</text>
    </g>
  </svg>
</template>


<script>
export default {
  props: {
    size1: {
      default: "400",
      type: String,
    },
    size2: {
      default: "150",
      type: String,
    },
    D: {
      default: "D",
      type: String,
    },
  },
};
</script>