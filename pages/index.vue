<template>
  <main>
    <ActionsButton btnText="test me" class="btn-primary" />

    <ActionsButton btnText="test me" class="btn-secondary" />

    <ActionsButton btnText="test me" class="btn-tertiary" />

    <ActionsButton btnText="test me" class="btn-primary btn-outline" />

    <ActionsButton btnText="test me" class="btn-secondary btn-outline" />

    <ActionsButton btnText="test me" class="btn-tertiary btn-outline" />

    <section class="h-screen">
      <div
        class="container m-auto flex h-full columns-3 justify-center gap-y-4 px-4 align-middle"
      >
        <div class="flex w-8/12 flex-col justify-center gap-y-6 align-middle">
          <h1>A unique dream-sharing platform igniting global generosity</h1>
          <p class="text-2xl">
            Welcome to Sypnos, a website where individuals from around the world
            can share their dreams, and compassionate strangers can transform
            those dreams into reality through spontaneous acts of financial.
          </p>
        </div>
      </div>
    </section>

    <section class="min-h-min bg-gray-950 py-80">
      <div
        class="container m-auto flex w-8/12 justify-center gap-y-4 px-4 align-middle"
      >
        <div class="flex flex-col justify-center gap-y-6 px-4 align-middle">
          <h2 class="text-white">
            What sets Sypnos apart is the element of surprise and generosity.
            Embrace the excitement of making a difference in a stranger's life,
            as your donations are entirely random. You never know when your act
            of kindness might transform a dream into reality.
          </h2>
          <p class="text-2xl text-green-400">
            Discovering dreams on Sypnos is easy and impactful. Dreamers craft
            profiles detailing their aspirations, which are then showcased for
            the Sypnos community. Users can randomly select dreams, making
            financial contributions to support dreamers in achieving their
            goals.
          </p>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
