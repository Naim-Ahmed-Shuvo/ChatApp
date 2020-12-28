<template>
  <div class="main">
     {{message.name}} : {{message.message}}
  </div>
</template>

<script>
export default {
   props: ['message']
}
</script>

<style>

</style>
