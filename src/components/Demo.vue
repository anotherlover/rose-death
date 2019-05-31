<template>
  <div class="demo">
    {{msg}}
  </div>
</template>

<script>
export default {
  data() {
    return {

    }
  },
  props: {
    msg: {
      type: String,
      required: false
    }
  }
}
</script>

