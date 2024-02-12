<template>
  <button class="btn">
    {{ btnText }}
  </button>
</template>

<script>
export default {
  props: {
    btnText: {
      type: String,
      required: true,
    },
  },
}
</script>
