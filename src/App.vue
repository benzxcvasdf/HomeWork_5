<script setup>
import Logo from './components/Logo.vue'
import Middle from "@/components/middle.vue";
import Bottom from "@/components/bottom.vue";
</script>

<template>
  <div style="position: relative;">
    <div id="centerContent" class="wide125" style="opacity: 1; padding-top: 32px; position: absolute; top: 50%; left: 50%; transform: translate(-50%,0%);">
      <Logo/>
      <Middle/>
      <Bottom/>
    </div>


  </div>

</template>

<script>

</script>

<style scoped>
:root{
  --bg-color:#323437;
  --main-color:#e2b714;
  --caret-color:#e2b714;
  --sub-color:#646669;
  --sub-alt-color:#2c2e31;
  --text-color:#d1d0c5;
  --error-color:#ca4754;
  --error-extra-color:#7e2a33;
  --colorful-error-color:#ca4754;
  --colorful-error-extra-color:#7e2a33
}
</style>