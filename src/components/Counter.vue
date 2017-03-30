<template>
  <div>
    <p>the counter {{ counter }} </p>
    <button @click="counter += 1">Increment</button>
  </div>
</template>
<script>
  export default {
    data () {
      return {
        counter: 0
      }
    }
  }
</script>