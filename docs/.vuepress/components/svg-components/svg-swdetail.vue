<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 -10 120 120"
    :width="size"
    :height="size"
  >
    <g stroke="black" stroke-width="2" fill="none">
      <path d="M33 70 l 0 -25 l 45.7 0 l 0 25" />
    </g>
    <!-- conn pipe -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M38.85 45 l 0 12.7 l 34 0 l 0 -12.7" />
      <path d="M42.35 57.7 l 0 12.3" />
      <path d="M69.35 57.7 l 0 12.3" />
    </g>
    <!-- center line -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M55.85 40 l 0 35" />
    </g>
    <!-- Dimension -->
    <g stroke="black" stroke-width="1" fill="none">
      <path d="M33 13.85 l 0 26.15" />
      <path d="M78.7 13.85 l 0 26.15" />
      <path d="M33 15.85 l 45.7 0" />
      <path d="M33 15.85 l6 -1.6" />
      <path d="M33 15.85 l6 1.6" />
      <path d="M78.7 15.85 l-6 -1.6" />
      <path d="M78.7 15.85 l-6 1.6" />

      <path d="M38.85 31 l 0 11.15" />
      <path d="M72.85 31 l 0 11.15" />
      <path d="M38.85 33 l 34 0" />
      <path d="M38.85 33 l6 -1.6" />
      <path d="M38.85 33 l6 1.6" />
      <path d="M72.85 33 l-6 -1.6" />
      <path d="M72.85 33 l-6 1.6" />

      <path d="M42.35 85 l 0 -11.15" />
      <path d="M69.35 85 l 0 -11.15" />
      <path d="M42.35 83 l 27 0" />
      <path d="M42.35 83 l6 -1.6" />
      <path d="M42.35 83 l6 1.6" />
      <path d="M69.35 83 l-6 -1.6" />
      <path d="M69.35 83 l-6 1.6" />

      <path d="M14.85 45 l 13.15 0" />
      <path d="M14.85 57.7 l 13.15 0" />
      <path d="M16.85 35 l 0 32.7" />
      <path d="M16.85 57.7 l -1.6 6" />
      <path d="M16.85 57.7 l 1.6 6" />
      <path d="M16.85 45 l -1.6 -6" />
      <path d="M16.85 45 l 1.6 -6" />
    </g>
    <g font-family="Arial" fill="black" stroke="none" text-anchor="middle">
      <text x="56" y="12">{{ D }}</text>
      <text x="56" y="30">{{ B }}</text>
      <text x="56" y="100">{{ ID }}</text>
      <text x="8" y="57">{{ J }}</text>
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
    B: {
      default: "B",
      type: String,
    },
    ID: {
      default: "id",
      type: String,
    },
    J: {
      default: "J",
      type: String,
    },
  },
};
</script>