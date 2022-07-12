<script>
export default {
  name: 'Test',

  data: () => ({
    test: 'value',
  }),
}
</script>

<template>
  <div>
    <span>123</span>
    <span>{{ test }}</span>
  </div>
</template>

<style>
</style>
