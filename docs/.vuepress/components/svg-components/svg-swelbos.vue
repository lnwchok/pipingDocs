<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="-30 50 260 60"
    :width="size1"
    :height="size2"
  >
    <g stroke="black" stroke-width="2" fill="none">
      <path d="M15 35 l 0 110 l 13 0 l 0 -110 z" />
      <path d="M15 64.5 l -2 0 l 0 51 l 2 0" />
      <path d="M28 65 l 5 0 l 0 50 l -5 0" />
      <path d="M33 73 l 77 0" />
      <path d="M33 107 l 77 0" />
      <path d="M110 67.15 l 0 45.7 l 12.15 0 l 4.85 -4.85 l 0 -40.85 z" />
      <path d="M127 108 l -4.85 4.85 l 0 12.15 l 45.7 0 l 0 -17 z" />
      <path d="M127 73 l 18 0 a 17 17, 0, 0 1, 17 17 l 0 18" />
      <path d="M163 77 l 0 -9.85 l 17 0 l 0 45.7 l -9.5 0" />
    </g>
    <!-- center line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M10 90 l 187 0" />
      <path d="M145 70 l 0 72" />
    </g>
    <g stroke="black" stroke-width="1" fill="none">
      <path
        d="M128 125 l 0 10 a 8.5 5, 0, 0 1, 17 0 a 8.5 5, 0, 0 0, 17 0 l 0 -10 M128 135 a 8.5 5, 0, 0 0, 17 0"
      />
      <path
        d="M180 73 l 10 0 a 5 8.5, 0, 0 0, 0 17 a 5 8.5, 0, 0 1, 0 17 l -10 0 M190 73 a 5 8.5, 0, 0 1, 0 17"
      />
    </g>
    <!-- hidden line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M128 125 l 0 -12.7 l 34 0 l 0 12.7" />
      <path d="M180 73 l -12.7 0 l 0 34 l 12.7 0" />
    </g>
    <!-- Dimension -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M13 19.85 l 0 13.15" />
      <path d="M145 19.85 l 0 45.15" />
      <path d="M13 21.85 l 132 0" />
      <path d="M13 21.85 l6 -1.6" />
      <path d="M13 21.85 l6 1.6" />
      <path d="M145 21.85 l-6 -1.6" />
      <path d="M145 21.85 l-6 1.6" />
    </g>
    <g font-family="Arial" fill="black" stroke="none" text-anchor="middle">
      <text x="80" y="15">{{ D }}</text>
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