<template>
  <div class="container m-auto flex h-14 items-center justify-between">
    <Nuxt-link to="/">
    <img
      src="~/assets/img/sypnos-logo-black.svg"
      width="100"
      alt="Sypnos logo"
    />
    </Nuxt-link>

    <nav>
      <ul class="flex list-none gap-x-5 align-middle text-gray-600">
        <li>About</li>
        <li>How it works</li>
        <li>Contacts</li>
      </ul>
    </nav>

    <nav>
      <ul
        class="flex list-none gap-x-5 align-middle font-semibold text-gray-800"
      >
        <Nuxt-link to="/login"><li>Log in</li></Nuxt-link>
        <Nuxt-link to="/register"><li>Create account</li></Nuxt-link>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {}
</script>
