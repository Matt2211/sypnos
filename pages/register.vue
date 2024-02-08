<template>
  <div class="flex min-h-screen">
    <div class="bg-hero-sky-register w-1/2 bg-cover"></div>

    <div class="flex w-1/2 items-center justify-center">
      <div class="flex w-6/12 flex-col gap-y-14">
        <div class="flex flex-col text-center gap-y-2">
          <h2>Create an account</h2>
          <p>Dreams are not only for dreamers</p>
        </div>

        <div class="flex flex-col gap-y-12">
          <div class="flex flex-col gap-y-3">
            <InputsFormInput type="text" placeholder="Name" />
            <InputsFormInput type="email" placeholder="Email" />
            <InputsFormInput type="password" placeholder="Password" />
          </div>

          <div class="flex flex-col gap-y-3">
            <Nuxt-link to="/registrationSteps" >
              <button
                class="h-10 rounded-lg w-full bg-slate-950 font-medium text-white hover:bg-[#9886BC]"
              >
                Create account
              </button>
            </Nuxt-link>
            <button
              class="h-10 rounded-lg border-2 border-slate-950 font-medium"
            >
              Register with Google
            </button>
          </div>
        </div>

        <div class="flex items-center justify-center gap-x-2">
          <p class="text-sm">Been here before?</p>
          <Nuxt-link to="/login">
            <p
              class="cursor-pointer text-sm font-semibold hover:text-[#9886BC]"
            >
              Log in
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
