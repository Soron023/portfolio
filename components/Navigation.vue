<template>
  <header
    class="fixed inset-x-0 top-0 z-40 border-b border-slate-800/70 bg-slate-950/80 backdrop-blur-xl"
  >
    <nav class="container-section flex h-16 items-center justify-between">
      <NuxtLink
        to="/"
        class="flex items-center gap-3 text-sm font-semibold tracking-tight text-slate-50"
      >
        <div
          class="flex h-8 w-8 items-center justify-center rounded-xl bg-gradient-to-br from-sky-500 to-indigo-500 text-xs font-bold text-white shadow-lg shadow-sky-500/40"
        >
          FD
        </div>
        <div class="hidden sm:block">
          <p class="text-xs uppercase tracking-[0.22em] text-slate-400">
            Full Stack Developer
          </p>
          <p class="text-sm font-semibold text-slate-50">
            Your Portfolio
          </p>
        </div>
      </NuxtLink>

      <div class="hidden md:flex items-center gap-6 text-sm">
        <NuxtLink
          v-for="link in navLinks"
          :key="link.href"
          :to="link.href"
          class="text-slate-300 transition-colors hover:text-sky-400"
        >
          {{ link.label }}
        </NuxtLink>
        <a
          href="https://github.com"
          target="_blank"
          rel="noopener noreferrer"
          class="inline-flex items-center gap-2 rounded-full border border-slate-700 bg-slate-900/60 px-3 py-1.5 text-xs font-medium text-slate-100 shadow-sm hover:border-sky-500 hover:text-sky-300"
        >
          <span class="h-2 w-2 rounded-full bg-emerald-400"></span>
          Open to work
        </a>
      </div>

      <button
        type="button"
        class="inline-flex h-9 w-9 items-center justify-center rounded-lg border border-slate-700 bg-slate-900/80 text-slate-200 shadow-sm hover:border-sky-500 md:hidden"
        @click="toggleMobileMenu"
      >
        <span class="sr-only">Toggle navigation</span>
        <svg
          v-if="!mobileMenuOpen"
          class="h-5 w-5"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path d="M4 6h16M4 12h16M4 18h16" />
        </svg>
        <svg
          v-else
          class="h-5 w-5"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path d="M6 18L18 6M6 6l12 12" />
        </svg>
      </button>
    </nav>

    <div v-if="mobileMenuOpen" class="border-t border-slate-800/80 bg-slate-950/95 md:hidden">
      <div class="container-section flex flex-col gap-1 py-3 text-sm">
        <NuxtLink
          v-for="link in navLinks"
          :key="link.href"
          :to="link.href"
          class="rounded-md px-2 py-2 text-slate-200 hover:bg-slate-900 hover:text-sky-400"
          @click="mobileMenuOpen = false"
        >
          {{ link.label }}
        </NuxtLink>
      </div>
    </div>
  </header>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const navLinks = [
  { href: '/', label: 'Home' },
  { href: '/#about', label: 'About' },
  { href: '/#experience', label: 'Experience' },
  { href: '/#projects', label: 'Projects' },
  { href: '/#contact', label: 'Contact' }
]

const mobileMenuOpen = ref(false)

const toggleMobileMenu = () => {
  mobileMenuOpen.value = !mobileMenuOpen.value
}
</script>
