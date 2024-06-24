<template>
  <el-input v-bind="attrs" v-on="$listeners"></el-input>
</template>

<script>
export default {
  computed: {
    attrs() {
      return {
        ...this.$attrs,
      };
    },
  },
  created() {},
};
</script>

<style lang="scss" scoped></style>
