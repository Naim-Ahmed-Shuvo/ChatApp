<template>
  <div class="main">
      {{message.user.name}} : {{message.message}}
  </div>
</template>

<script>
export default {
   props: ['message']
}
</script>

<style>

</style>
