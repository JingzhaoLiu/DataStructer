<template>
  <div>
    <wrapper />
    <footer-bar />
  </div>
</template>
<script>
import FooterBar from "../components/FooterBar";
import Wrapper from "../components/Wrapper";
export default {
  name: "Home",
  components: {
    FooterBar,
    Wrapper,
  },
};
</script>

<style lang="scss"></style>
