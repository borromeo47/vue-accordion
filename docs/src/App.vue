<template>
  <div id="app">
    <h1>Hi this is app.</h1>
    <renderless-accordion />
  </div>
</template>

<script>
import { RenderlessAccordion } from "../../src/renderless";

export default {
  name: "App",
  components: {
    RenderlessAccordion
  }
};
</script>
