<template>
  <div class="main">
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
  components: {HelloDefaultLayout},
  mixins: [],
  inject: [],
  provide() {
    return {}
  },
  props: {},
  data() {
    return {}
  },
  beforeRouterEnter() {
  },
  created() {
  },
  mounted() {
  },
  beforeDestroy() {
  },
  destroyed() {
  },
  computed: {},
  methods: {},
  watch: {},
}
</script>

<style scoped>

</style>
