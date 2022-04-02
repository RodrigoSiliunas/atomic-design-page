<template>
  <div class="component">
    <Logo />
    <NavBar />
    <SearchForm />
    <SocialNetworks />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Logo } from "@/components/atoms";
import { NavBar, SearchForm, SocialNetworks } from "@/components/molecules";

export default defineComponent({
  components: { Logo, NavBar, SearchForm, SocialNetworks },
});
</script>

<style lang="scss" scoped>
.component {
  margin: 2.5rem;
}
</style>
