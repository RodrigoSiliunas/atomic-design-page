<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ad harum cum dolor necessitatibus ex sequi quo. Soluta adipisci corrupti officiis dolores facere repellendus iusto, aut saepe tenetur dicta excepturi blanditiis."
    />
    <Service
      title="Back End"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ad harum cum dolor necessitatibus ex sequi quo. Soluta adipisci corrupti officiis dolores facere repellendus iusto, aut saepe tenetur dicta excepturi blanditiis."
    />
    <Service
      title="Manutenção"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ad harum cum dolor necessitatibus ex sequi quo. Soluta adipisci corrupti officiis dolores facere repellendus iusto, aut saepe tenetur dicta excepturi blanditiis."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Service } from "@/components/molecules";

export default defineComponent({
  components: { Service },
});
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
