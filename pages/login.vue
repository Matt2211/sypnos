<template>
  <div class="flex min-h-screen">
    <div class="bg-hero-sky-login w-1/2 bg-cover"></div>

    <div class="flex w-1/2 items-center justify-center">
      <div class="flex w-4/12 flex-col gap-y-14">
        <div class="flex flex-col text-center gap-y-2">
          <h2>Welcome back!</h2>
          <p>Believe in your dreams...</p>
        </div>

        <div class="flex flex-col gap-y-12">
          <div class="flex flex-col gap-y-3">
            <InputsFormInput type="email" placeholder="Email" />
            <InputsFormInput type="password" placeholder="Password" />

            <div class="flex justify-between">
              <div class="flex gap-x-2">
                <input type="checkbox" id="" name="" value="" />
                <label for="" class="text-sm"> Remember me</label>
              </div>

              <p
                class="cursor-pointer text-sm font-semibold hover:text-[#9886BC]"
              >
                Forgot password
              </p>
            </div>
          </div>
          <div class="flex flex-col gap-y-3">
            <button
              class="h-10 rounded-lg bg-slate-950 font-medium text-white hover:bg-[#9886BC]"
            >
              Sign in
            </button>
            <button
              class="h-10 rounded-lg border-2 border-slate-950 font-medium"
            >
              Sign in with Google
            </button>
          </div>
        </div>

        <div class="flex items-center justify-center gap-x-2">
          <p class="text-sm">Don't have an account?</p>
          <Nuxt-link to="/register">
            <p
              class="cursor-pointer text-sm font-semibold hover:text-[#9886BC]"
            >
              Sign up
            </p>
          </Nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<!--  <div class="h-full bg-red-500">hello</div>
    <div class="h-full">
      <div class="flex  w-3/12 flex-col gap-y-3 bg-green-400">
        <InputsFormInput placeholder="Name" />
        <InputsFormInput type="email" placeholder="Email" />
        <InputsFormInput type="password" placeholder="Password" />
      </div>
    </div> -->
