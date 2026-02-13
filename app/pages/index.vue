<template>
  <div class="space-y-24">
    <!-- Hero Section -->
    <section
      id="home"
      class="grid gap-10 pt-8 md:grid-cols-[minmax(0,1.4fr)_minmax(0,1fr)] md:items-center"
    >
      <div class="space-y-6">
        <p class="section-subtitle">Full Stack Engineer</p>
        <h1 class="text-4xl sm:text-5xl md:text-6xl font-semibold tracking-tight text-slate-50">
          I build end‑to‑end
          <span
            class="bg-gradient-to-r from-sky-400 via-cyan-300 to-indigo-400 bg-clip-text text-transparent"
          >
            web platforms
          </span>
          that scale.
        </h1>
        <p class="max-w-xl text-base sm:text-lg leading-relaxed text-slate-300">
          Experienced in designing, developing, and deploying backend APIs and modern frontends
          using Spring Boot, Go, Express.js, Laravel, Vue/Nuxt, and cloud‑native tooling.
        </p>

        <div class="flex flex-wrap items-center gap-3">
          <NuxtLink
            to="#contact"
            class="inline-flex items-center justify-center gap-2 rounded-full bg-sky-500 px-6 py-2.5 text-sm font-medium text-slate-950 shadow-lg shadow-sky-500/40 transition hover:bg-sky-400"
          >
            <span>Contact me</span>
          </NuxtLink>
          <NuxtLink
            to="#projects"
            class="inline-flex items-center justify-center gap-2 rounded-full border border-slate-700 bg-slate-900/60 px-6 py-2.5 text-sm font-medium text-slate-100 shadow-sm transition hover:border-sky-500 hover:text-sky-300"
          >
            <span>View projects</span>
          </NuxtLink>
          <div
            class="inline-flex items-center gap-2 rounded-full border border-emerald-500/40 bg-emerald-500/10 px-3 py-1 text-xs font-medium text-emerald-300"
          >
            <span class="h-1.5 w-1.5 animate-pulse rounded-full bg-emerald-400"></span>
            Available for freelance & full‑time
          </div>
        </div>

        <div class="flex flex-wrap gap-2 pt-3 text-xs text-slate-300">
          <span class="rounded-full bg-slate-900/70 px-3 py-1">
            Spring Boot · Go · Express.js · Laravel
          </span>
          <span class="rounded-full bg-slate-900/70 px-3 py-1">
            Vue · Nuxt · TypeScript · Tailwind CSS
          </span>
          <span class="rounded-full bg-slate-900/70 px-3 py-1">
            MySQL · PostgreSQL · Docker · Nginx · DigitalOcean
          </span>
        </div>
      </div>

      <div class="flex justify-center md:justify-end">
        <div
          class="relative inline-flex items-center justify-center rounded-3xl border border-slate-800 bg-slate-900/70 p-2 shadow-2xl shadow-sky-500/20"
        >
          <div
            class="pointer-events-none absolute inset-0 -z-10 rounded-[1.6rem] bg-[conic-gradient(from_180deg_at_50%_0%,#22d3ee_0deg,#4f46e5_140deg,#22c55e_220deg,#22d3ee_360deg)] opacity-40 blur-xl"
          ></div>
          <img
            src="/profile.png"
            alt="Profile Picture"
            class="h-72 w-56 rounded-2xl object-cover sm:h-80 sm:w-64 md:h-[22rem] md:w-[18rem]"
          />
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="space-y-8">
      <div class="space-y-3">
        <p class="section-subtitle">About</p>
        <h2 class="section-title">Who I am</h2>
      </div>

      <div class="grid gap-8 md:grid-cols-[minmax(0,1.4fr)_minmax(0,1fr)]">
        <div class="space-y-4 text-sm sm:text-base leading-relaxed text-slate-300">
          <p>
            I'm a full stack developer focused on shipping clean, maintainable code and
            user‑friendly experiences. I enjoy taking products from idea to production: designing
            APIs, modeling data, implementing frontends, and setting up DevOps pipelines.
          </p>
          <p>
            My background spans RESTful services, SSR/SPA apps, and infrastructure automation. I
            care about performance, observability, and building systems that are easy to operate and
            extend over time.
          </p>
        </div>

        <div class="card-surface p-5 space-y-4">
          <h3 class="text-sm font-semibold text-slate-50">
            Current focus
          </h3>
          <ul class="space-y-2 text-sm text-slate-300">
            <li>• Building scalable APIs with Spring Boot, Go, and Express.js</li>
            <li>• Creating fast frontends with Nuxt 4, Vue 3, and Tailwind CSS</li>
            <li>• Shipping to production using Docker, Nginx, and DigitalOcean</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="space-y-8">
      <div class="space-y-3">
        <p class="section-subtitle">Stack</p>
        <h2 class="section-title">Experience & skills</h2>
      </div>

      <div class="grid gap-6 lg:grid-cols-3">
        <!-- Backend Technologies -->
        <div class="card-surface p-6">
          <h3 class="mb-3 text-base font-semibold text-sky-300">
            Backend
          </h3>
          <ul class="space-y-2">
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-sky-400"></span>
              Spring Boot (Java)
            </li>
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-sky-400"></span>
              Go (Golang)
            </li>
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-sky-400"></span>
              Express.js (Node.js)
            </li>
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-sky-400"></span>
              PHP Laravel
            </li>
          </ul>
        </div>

        <!-- Frontend Technologies -->
        <div class="card-surface p-6">
          <h3 class="mb-3 text-base font-semibold text-sky-300">
            Frontend
          </h3>
          <ul class="space-y-2">
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-indigo-400"></span>
              Vue.js
            </li>
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-indigo-400"></span>
              Nuxt.js
            </li>
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-indigo-400"></span>
              TypeScript
            </li>
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-indigo-400"></span>
              JavaScript
            </li>
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-indigo-400"></span>
              Tailwind CSS
            </li>
          </ul>
        </div>

        <!-- Database & DevOps -->
        <div class="card-surface p-6">
          <h3 class="mb-3 text-base font-semibold text-sky-300">
            Database & DevOps
          </h3>
          <ul class="space-y-2">
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-emerald-400"></span>
              MySQL
            </li>
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-emerald-400"></span>
              PostgreSQL
            </li>
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-emerald-400"></span>
              Docker
            </li>
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-emerald-400"></span>
              Nginx
            </li>
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-emerald-400"></span>
              Digital Ocean
            </li>
            <li class="flex items-center text-slate-300">
              <span class="mr-3 h-2 w-2 rounded-full bg-emerald-400"></span>
              GitHub
            </li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="space-y-8">
      <div class="space-y-3">
        <p class="section-subtitle">Selected work</p>
        <h2 class="section-title">Highlighted projects</h2>
      </div>

      <div class="grid gap-6 md:grid-cols-2 lg:grid-cols-3">
        <div
          v-for="project in projects"
          :key="project.id"
          class="card-surface flex h-full flex-col p-6 transition hover:border-sky-500/80 hover:shadow-sky-500/20"
        >
          <h3 class="mb-1 text-base font-semibold text-slate-50">
            {{ project.title }}
          </h3>
          <p class="mb-4 text-sm text-slate-300">
            {{ project.description }}
          </p>
          <div class="mb-4 flex flex-wrap gap-2">
            <span
              v-for="tech in project.technologies"
              :key="tech"
              class="rounded-full bg-slate-900/80 px-3 py-1 text-xs font-medium text-slate-200"
            >
              {{ tech }}
            </span>
          </div>
          <div class="mt-auto pt-3">
            <a
              :href="project.github"
              target="_blank"
              class="inline-flex items-center gap-1 text-xs font-medium text-sky-400 hover:text-sky-300"
            >
              <span>View on GitHub</span>
              <span aria-hidden="true">→</span>
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="space-y-8">
      <div class="space-y-3">
        <p class="section-subtitle">Contact</p>
        <h2 class="section-title">Let’s work together</h2>
      </div>

      <div class="grid gap-8 md:grid-cols-[minmax(0,1.2fr)_minmax(0,1fr)]">
        <form
          @submit.prevent="handleSubmit"
          class="card-surface space-y-5 p-6 sm:p-7"
        >
          <div class="mb-6">
            <label
              for="name"
              class="block text-xs font-medium uppercase tracking-[0.2em] text-slate-400"
            >
              Name
            </label>
            <input
              id="name"
              v-model="form.name"
              type="text"
              required
              class="mt-1 w-full rounded-xl border border-slate-700 bg-slate-900/70 px-4 py-2.5 text-sm text-slate-100 outline-none ring-0 transition placeholder:text-slate-500 focus:border-sky-500"
            />
          </div>
          <div class="mb-6">
            <label
              for="email"
              class="block text-xs font-medium uppercase tracking-[0.2em] text-slate-400"
            >
              Email
            </label>
            <input
              id="email"
              v-model="form.email"
              type="email"
              required
              class="mt-1 w-full rounded-xl border border-slate-700 bg-slate-900/70 px-4 py-2.5 text-sm text-slate-100 outline-none ring-0 transition placeholder:text-slate-500 focus:border-sky-500"
            />
          </div>
          <div class="mb-6">
            <label
              for="message"
              class="block text-xs font-medium uppercase tracking-[0.2em] text-slate-400"
            >
              Message
            </label>
            <textarea
              id="message"
              v-model="form.message"
              rows="5"
              required
              class="mt-1 w-full rounded-xl border border-slate-700 bg-slate-900/70 px-4 py-2.5 text-sm text-slate-100 outline-none ring-0 transition placeholder:text-slate-500 focus:border-sky-500"
            ></textarea>
          </div>
          <button
            type="submit"
            class="inline-flex w-full items-center justify-center gap-2 rounded-full bg-sky-500 px-6 py-2.5 text-sm font-semibold text-slate-950 shadow-lg shadow-sky-500/40 transition hover:bg-sky-400"
          >
            Send message
          </button>
        </form>

        <div class="space-y-4 text-sm text-slate-300">
          <p>
            Share a bit about your project, timeline, and preferred stack. I’ll review it and
            respond with concrete next steps and how I can help.
          </p>
          <div class="space-y-2">
            <p class="font-medium text-slate-100">Quick links</p>
            <ul class="space-y-1 text-sm">
              <li>• GitHub – code samples & experiments</li>
              <li>• LinkedIn – experience & background</li>
              <li>• Email – long‑form collaboration ideas</li>
            </ul>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
import { reactive } from 'vue'

const form = reactive({
  name: '',
  email: '',
  message: ''
})

const projects = [
  {
    id: 1,
    title: 'E-Commerce Platform',
    description: 'Full-stack e-commerce solution with payment integration and admin dashboard.',
    technologies: ['Vue.js', 'Nuxt.js', 'Spring Boot', 'PostgreSQL'],
    github: 'https://github.com'
  },
  {
    id: 2,
    title: 'API Gateway Service',
    description: 'Microservices architecture with API gateway using Go and Docker.',
    technologies: ['Go', 'Docker', 'Nginx', 'MySQL'],
    github: 'https://github.com'
  },
  {
    id: 3,
    title: 'Task Management App',
    description: 'Real-time collaborative task management application with Laravel backend.',
    technologies: ['Vue.js', 'Laravel', 'MySQL', 'WebSockets'],
    github: 'https://github.com'
  },
  {
    id: 4,
    title: 'Social Media Dashboard',
    description: 'Analytics dashboard for social media metrics with Express.js backend.',
    technologies: ['Nuxt.js', 'Express.js', 'PostgreSQL', 'Chart.js'],
    github: 'https://github.com'
  },
  {
    id: 5,
    title: 'Blog Platform',
    description: 'Content management system with markdown support and SEO optimization.',
    technologies: ['Nuxt.js', 'TypeScript', 'PostgreSQL', 'Tailwind CSS'],
    github: 'https://github.com'
  },
  {
    id: 6,
    title: 'DevOps Pipeline',
    description: 'CI/CD pipeline setup with Docker, Digital Ocean, and automated deployments.',
    technologies: ['Docker', 'Nginx', 'GitHub Actions', 'Digital Ocean'],
    github: 'https://github.com'
  }
]

const handleSubmit = () => {
  // In a real application, you would send this to a backend API
  alert('Thank you for your message! I will get back to you soon.')
  form.name = ''
  form.email = ''
  form.message = ''
}
</script>
