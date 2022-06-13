<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="40 -3 100 100"
    :width="size1"
    :height="size2"
  >
    <g stroke="black" stroke-width="2" fill="none">
      <path d="M19 57 l 35 0 l 0 26 l -35 0 z" />
      <path d="M58 53 l 28.3 0" />
      <path d="M58 53 l 0 34" />
      <path d="M58 87 l 28.3 0" />
      <path d="M54 57 l 4 -4 " />
      <path d="M54 83 l 4 4 " />
      <path d="M86.3 47.15 l 0 45.7 l 17 0 l 0 -40.85 l -4.85 -4.85 z" />
      <path d="M98.45 47.15 l 0 -12.15 l 45.7 0 l 0 17 l -40.85 0 " />
      <path d="M138.3 52 l 0 18 a 17 17, 0, 0 1, -17 17 l -18 0" />
      <path d="M146.8 47.15 l 9.5 0 l 0 45.7 l -17 0 l 0 -10" />
    </g>
    <!-- center line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M12 70 l 149.3 0" />
      <path d="M121.3 30 l 0 60" />
    </g>
    <!-- hidden line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M86.3 53 l 12.7 0 l 0 34 l -12.7 0" />
    </g>
    <!-- Dimension -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d='M19 11.85 l 0 40.15' />
      <path d='M121.3 11.85 l 0 13.15'/>
      <path d='M19 13.85 l 102.3 0' />
      <path d='M19 13.85 l6 -1.6' />
      <path d='M19 13.85 l6 1.6' />
      <path d='M121.3 13.85 l-6 -1.6' />
      <path d='M121.3 13.85 l-6 1.6' />  
    </g>
    <g font-family="Arial" fill="black" stroke="none" text-anchor="middle">
      <text x="70" y="11">{{ D }}</text>
    </g>
  </svg>
</template>


<script>

export default {
  props: {
    size1: {
      default: "300",
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