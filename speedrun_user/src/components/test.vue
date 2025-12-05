<template>
  <div class="hello">
    <span>{{ msg }}.</span>
  </div>
  <div class="hello">{{ rawHTML }}</div>
  <div v-html="rawHTML"></div>
    <div>{{ num + 20 }}</div>
    <div>{{ f ? 1222 : 2 }}</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      msg: 'HelloWorld.vue',
      rawHTML: '<span>This is raw HTML</span>',
      num:10,
      f: true
    }
  }
}
</script>