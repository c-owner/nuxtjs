<template>
  <div>
      <HelloWorldComponent />
  </div>

</template>

<script>
import HelloWorldComponent from "~/components/hello/HelloWorldComponent";
export default {
  name: "HelloPage",
  components: {HelloWorldComponent},
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
