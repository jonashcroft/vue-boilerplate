<template>
  <div id="app">
    <Example :msg="test" />
  </div>
</template>

<script>
import Example from '@/components/Example'

export default {
  name: 'App',

  components: {
    Example
  },

  props: {},

  data() {
    return {
      test: 'Hello, World'
    }
  },

  computed: {},

  mounted() {},

  methods: {}
}
</script>

<style src="@/styles/global/reset.scss" lang="scss" scoped></style>
<style src="@/styles/global/app.scss" lang="scss" scoped></style>
