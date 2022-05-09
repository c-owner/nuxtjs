<template>
  <div>
    <h1> Hello Page. </h1>
    <div>
      <HelloWorldComponent />
    </div>
  </div>

</template>

<script>
import HelloWorldComponent from "~/components/hello/HelloWorldComponent";
export default {
  name: "HelloPage",
  components: {HelloWorldComponent}
}
</script>

<style scoped>

</style>
