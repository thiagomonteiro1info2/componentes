<script>
import MenuLateral from "@/components/MenuLateral.vue";
import CabecalhoCima from "@/components/CabecalhoCima.vue";
import PrincipalContent from "@/components/PrincipalContent.vue";
import RodapeFooter from "@/components/RodapeFooter.vue";

export default {
  components: { MenuLateral, CabecalhoCima, PrincipalContent, RodapeFooter },
};
</script>
<template>
  <MenuLateral />
  <CabecalhoCima />
  <PrincipalContent />
  <RodapeFooter />
</template>
<style></style>
