<template>
  <div>
    HelloWorld 컴포넌트
    <div>
      <hello-default-layout></hello-default-layout>
    </div>
  </div>
</template>

<script>
import HelloDefaultLayout from "~/layouts/HelloDefaultLayout";
export default {
  name: "HelloWorldComponent",
  components: {HelloDefaultLayout}
}
</script>

<style scoped>

</style>
