<template>
  <div class="example">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
import props from '@/utils/props.js'

export default {
  name: 'Example',

  components: {},

  props: {
    msg: props.msg
  },

  data() {
    return {}
  },

  computed: {},

  mounted() {},

  methods: {}
}
</script>

<style src="@/styles/components/example.scss" lang="scss" scoped></style>
