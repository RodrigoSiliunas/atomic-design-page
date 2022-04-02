<template>
  <a class="nav-item" v-bind:href="to">{{ text }}</a>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  props: {
    text: { type: String, required: true, default: "TextRequired" },
    to: { type: String, required: true, default: "LinkTo" },
  },
});
</script>

<style lang="scss" scoped>
.nav-item {
  color: #293947;
  text-decoration: none;
  font-size: 1.3rem;
}
</style>
