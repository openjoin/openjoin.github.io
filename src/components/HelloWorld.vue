<template>
  <h1>{{ msg }}</h1>
</template>

<script>
export default {
  //#5C1736
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>
