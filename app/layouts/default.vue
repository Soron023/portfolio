<template>
  <div class="min-h-screen bg-slate-950 text-slate-100">
    <div
      class="pointer-events-none fixed inset-0 -z-10 bg-gradient-to-b from-sky-950/60 via-slate-950 to-slate-950"
    >
      <div
        class="absolute inset-0 bg-[radial-gradient(circle_at_top,_rgba(56,189,248,0.18),_transparent_55%)]"
      />
      <div
        class="absolute inset-0 bg-[radial-gradient(circle_at_bottom,_rgba(129,140,248,0.14),_transparent_55%)]"
      />
    </div>

    <Navigation />

    <main class="pt-20 pb-10">
      <div class="container-section">
        <slot />
      </div>
    </main>

    <Footer />
  </div>
</template>

<script setup lang="ts">
</script>
