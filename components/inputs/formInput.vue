<template>
  <input
    :type="type"
    class="h-10 rounded-lg border border-slate-400 px-2 placeholder-slate-400"
    :placeholder="placeholder"
  />
</template>
<script>
export default {
  name: 'FormInput',
  props: {
    type: {
      type: String,
      required: false,
      default: 'text',
    },
    placeholder: {
      type: String,
      required: false,
    },
  },
}
</script>
