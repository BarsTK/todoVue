<template>
  <div>
  <div>{{obj.id}}</div>
  <div>{{caption}}</div>
  <router-link :to="{name: 'notes'}" tag="button" class="btn">Back to list without saving</router-link>
  </div>
</template>


<script>
  export default {
    name: "test",
    props: {obj: Object}
  }
</script>

<style scoped>
</style>
