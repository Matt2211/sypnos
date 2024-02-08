t
<template>
  <div class="flex min-h-screen">
    <div class="bg-hero-sky-login w-1/2 bg-cover"></div>

    <div class="flex w-1/2 items-center justify-center">
      <div class="flex w-4/12 flex-col gap-y-14">
        <div class="flex flex-col gap-y-2 text-center">
          <h2>You are all set</h2>
          <p>Let's add your first dream</p>
        </div>

        <button
            class="h-10 rounded-lg bg-slate-950 font-medium text-white hover:bg-[#9886BC]"
          >
            Next
          </button>

        
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isDreamer: false,
      isGiver: false,
    }
  },
}
</script>
