<!-- eslint-disable max-len -->
<!-- eslint-disable no-tabs -->
<template>
  <!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
  <svg :class="className" :width="width" :height="height" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px"
    y="0px" viewBox="0 0 91 91" enable-background="new 0 0 91 91" xml:space="preserve">
    <g>
      <path d="M45.5,1.9c-24,0-43.6,19.6-43.6,43.6s19.6,43.6,43.6,43.6s43.6-19.6,43.6-43.6S69.5,1.9,45.5,1.9z M45.5,81.1
		c-19.6,0-35.6-16-35.6-35.6s16-35.6,35.6-35.6s35.6,16,35.6,35.6S65.1,81.1,45.5,81.1z" />
      <path d="M48.3,23.5c-0.4-1.2-1.6-1.9-2.8-1.9c-1.2,0-2.4,0.8-2.8,1.9L28.3,61.4c-0.5,1.3-0.1,2.7,1,3.5c0.5,0.4,1.1,0.6,1.8,0.6
		c0.7,0,1.3-0.2,1.9-0.7l12.5-10.2L58,64.8c1.1,0.9,2.6,0.9,3.7,0.1c1.1-0.8,1.5-2.2,1-3.5L48.3,23.5z M47.4,48.4
		c-1.1-0.9-2.7-0.9-3.8,0L37.9,53l7.6-20l7.6,20L47.4,48.4z" />
    </g>
  </svg>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'SettingsIcon',
  props: {
    width: {
      type: String,
      default: '30',
    },
    height: {
      type: String,
      default: '30',
    },
    className: {
      type: String,
    },
  },
});
</script>
