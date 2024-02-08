<template>
  <div class="flex min-h-screen">
    <div class="bg-hero-sky w-1/2 bg-cover"></div>

    <div class="flex w-1/2 items-center justify-center">
      <div class="flex flex-col gap-y-14">
        <div class="flex flex-col">
          <h2>Welcome back!</h2>
          <p>Believe in your dreams...</p>
        </div>

        <div class="flex flex-col gap-y-3">
          <InputsFormInput type="email" placeholder="Email" />
          <InputsFormInput type="password" placeholder="Password" />

          <div class="flex justify-between">
            <div class="flex gap-x-2">
              <input type="checkbox" id="" name="" value="" />
              <label for="" class="text-sm"> Remember me</label>
            </div>

            <p class="text-sm font-semibold">Forgot password</p>
          </div>

          <button class="h-10 rounded-lg bg-slate-950 font-medium text-white">
            Sign in
          </button>
          <button class="h-10 rounded-lg border-2 font-medium border-slate-950">
            Sign in with Google
          </button>
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
