<template>
  <div id="Details">
      <slot name="ba"></slot>
      <p>{{country}}</p>
      <slot name="ap"></slot>
  </div>
</template>

<script>
export default {
    data() {
        return{
            country: 'bangladesh'
        }
    }
}
</script>

<style>

</style>