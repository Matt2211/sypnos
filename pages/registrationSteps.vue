t
<template>
  <div class="flex min-h-screen">
    <div class="bg-hero-sky-login w-1/2 bg-cover"></div>

    <div class="flex w-1/2 items-center justify-center">
      <div class="flex w-4/12 flex-col gap-y-14">
        <div class="flex flex-col gap-y-2 text-center">
          <h2>Tell us a bit more about you</h2>
          <p>What's best describe yourself?</p>
        </div>

        <div class="flex flex-col gap-y-12">
          <div class="flex flex-col gap-y-3">
            <button
              @click="
                isDreamer = true
                isGiver = false
              "
              class="h-10 rounded-lg border-2 hover:border-[#9886BC]"
              :class="{ 'border-0 bg-[#d3b3d4]': isDreamer }"
            >
              I am a dreamer
            </button>
            <button
              @click="
                isGiver = true
                isDreamer = false
              "
              class="h-10 rounded-lg border-2 hover:border-[#9886BC]"
              :class="{ 'border-0 bg-[#d3b3d4]': isGiver }"
            >
              I am giver
            </button>
          </div>

          <div
            v-show="isDreamer || isGiver"
            class="flex items-center justify-center gap-x-2"
          >
            <h3 v-if="isDreamer" class="font-medium">
              You can still help others
            </h3>
            <p v-if="isGiver" class="font-medium">You can still dream</p>
          </div>

          <Nuxt-link to="registrationDone">
            <button
              class="h-10 w-full rounded-lg bg-slate-950 font-medium text-white hover:bg-[#9886BC]"
            >
              Next
            </button>
          </Nuxt-link>
        </div>
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
