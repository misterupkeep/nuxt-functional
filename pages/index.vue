<template>
  <div class="container">
    <dummy/>
  </div>
</template>

<script>
import Dummy from "~/components/Dummy";
export default {
  components: {Dummy}
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
