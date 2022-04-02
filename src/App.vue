<template>
  <div class="component">
    <Header />
    <Service
      title="Lorem Ipsum"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ad harum cum dolor necessitatibus ex sequi quo. Soluta adipisci corrupti officiis dolores facere repellendus iusto, aut saepe tenetur dicta excepturi blanditiis."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Header } from "@/components/organisms";
import { Service } from "@/components/atoms";

export default defineComponent({
  components: { Service, Header },
});
</script>

<style lang="scss" scoped>
.component {
  margin: 2.5rem;
}
</style>
