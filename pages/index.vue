<template>
  <div>
    <!-- Hero Section -->
    <section id="home" class="min-h-screen flex items-center justify-center pt-20 px-6">
      <div class="container mx-auto">
        <div class="flex flex-col md:flex-row items-center gap-12">
          <div class="flex-1 text-center md:text-left">
            <h1 class="text-5xl md:text-7xl font-bold mb-6 bg-gradient-to-r from-blue-400 to-purple-500 bg-clip-text text-transparent">
              Full Stack Developer
            </h1>
            <p class="text-xl md:text-2xl text-gray-300 mb-8">
              Building scalable web applications with modern technologies
            </p>
            <div class="flex flex-wrap gap-4 justify-center md:justify-start">
              <NuxtLink 
                to="#contact"
                class="px-8 py-3 bg-blue-500 hover:bg-blue-600 text-white rounded-lg transition-colors font-semibold"
              >
                Get In Touch
              </NuxtLink>
              <NuxtLink 
                to="#projects"
                class="px-8 py-3 border-2 border-blue-500 text-blue-400 hover:bg-blue-500 hover:text-white rounded-lg transition-colors font-semibold"
              >
                View Projects
              </NuxtLink>
            </div>
          </div>
          <div class="flex-1 flex justify-center">
            <div class="relative">
              <div class="absolute inset-0 bg-gradient-to-r from-blue-500 to-purple-500 rounded-full blur-3xl opacity-30"></div>
              <img 
                src="/profile.png" 
                alt="Profile Picture" 
                class="relative w-64 h-80 md:w-80 md:h-96 object-cover rounded-lg shadow-2xl border-4 border-gray-700"
              />
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 px-6 bg-gray-800/50">
      <div class="container mx-auto">
        <h2 class="text-4xl font-bold text-center mb-12 text-blue-400">About Me</h2>
        <div class="max-w-3xl mx-auto">
          <p class="text-lg text-gray-300 leading-relaxed mb-6">
            I'm a passionate Full Stack Developer with expertise in building robust, scalable web applications. 
            I specialize in both frontend and backend development, working with a wide range of technologies 
            to deliver high-quality solutions.
          </p>
          <p class="text-lg text-gray-300 leading-relaxed">
            My experience spans across multiple programming languages and frameworks, allowing me to choose 
            the right tool for each project. I'm passionate about clean code, best practices, and creating 
            user-friendly applications that solve real-world problems.
          </p>
        </div>
      </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-20 px-6">
      <div class="container mx-auto">
        <h2 class="text-4xl font-bold text-center mb-12 text-blue-400">Experience & Skills</h2>
        
        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
          <!-- Backend Technologies -->
          <div class="bg-gray-800 p-6 rounded-lg border border-gray-700">
            <h3 class="text-2xl font-semibold mb-4 text-blue-400">Backend</h3>
            <ul class="space-y-2">
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-blue-400 rounded-full mr-3"></span>
                Spring Boot (Java)
              </li>
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-blue-400 rounded-full mr-3"></span>
                Go (Golang)
              </li>
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-blue-400 rounded-full mr-3"></span>
                Express.js (Node.js)
              </li>
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-blue-400 rounded-full mr-3"></span>
                PHP Laravel
              </li>
            </ul>
          </div>

          <!-- Frontend Technologies -->
          <div class="bg-gray-800 p-6 rounded-lg border border-gray-700">
            <h3 class="text-2xl font-semibold mb-4 text-blue-400">Frontend</h3>
            <ul class="space-y-2">
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-purple-400 rounded-full mr-3"></span>
                Vue.js
              </li>
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-purple-400 rounded-full mr-3"></span>
                Nuxt.js
              </li>
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-purple-400 rounded-full mr-3"></span>
                TypeScript
              </li>
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-purple-400 rounded-full mr-3"></span>
                JavaScript
              </li>
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-purple-400 rounded-full mr-3"></span>
                Tailwind CSS
              </li>
            </ul>
          </div>

          <!-- Database & DevOps -->
          <div class="bg-gray-800 p-6 rounded-lg border border-gray-700">
            <h3 class="text-2xl font-semibold mb-4 text-blue-400">Database & DevOps</h3>
            <ul class="space-y-2">
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-green-400 rounded-full mr-3"></span>
                MySQL
              </li>
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-green-400 rounded-full mr-3"></span>
                PostgreSQL
              </li>
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-green-400 rounded-full mr-3"></span>
                Docker
              </li>
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-green-400 rounded-full mr-3"></span>
                Nginx
              </li>
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-green-400 rounded-full mr-3"></span>
                Digital Ocean
              </li>
              <li class="flex items-center text-gray-300">
                <span class="w-2 h-2 bg-green-400 rounded-full mr-3"></span>
                GitHub
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 px-6 bg-gray-800/50">
      <div class="container mx-auto">
        <h2 class="text-4xl font-bold text-center mb-12 text-blue-400">Projects</h2>
        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div 
            v-for="project in projects" 
            :key="project.id"
            class="bg-gray-800 p-6 rounded-lg border border-gray-700 hover:border-blue-500 transition-colors"
          >
            <h3 class="text-xl font-semibold mb-2 text-blue-400">{{ project.title }}</h3>
            <p class="text-gray-300 mb-4">{{ project.description }}</p>
            <div class="flex flex-wrap gap-2 mb-4">
              <span 
                v-for="tech in project.technologies" 
                :key="tech"
                class="px-3 py-1 bg-gray-700 text-sm text-gray-300 rounded-full"
              >
                {{ tech }}
              </span>
            </div>
            <a 
              :href="project.github" 
              target="_blank"
              class="text-blue-400 hover:text-blue-300 transition-colors"
            >
              View on GitHub →
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 px-6">
      <div class="container mx-auto max-w-2xl">
        <h2 class="text-4xl font-bold text-center mb-12 text-blue-400">Get In Touch</h2>
        <form @submit.prevent="handleSubmit" class="bg-gray-800 p-8 rounded-lg border border-gray-700">
          <div class="mb-6">
            <label for="name" class="block text-gray-300 mb-2">Name</label>
            <input 
              id="name"
              v-model="form.name"
              type="text" 
              required
              class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg text-gray-100 focus:outline-none focus:border-blue-500"
            />
          </div>
          <div class="mb-6">
            <label for="email" class="block text-gray-300 mb-2">Email</label>
            <input 
              id="email"
              v-model="form.email"
              type="email" 
              required
              class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg text-gray-100 focus:outline-none focus:border-blue-500"
            />
          </div>
          <div class="mb-6">
            <label for="message" class="block text-gray-300 mb-2">Message</label>
            <textarea 
              id="message"
              v-model="form.message"
              rows="5" 
              required
              class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg text-gray-100 focus:outline-none focus:border-blue-500"
            ></textarea>
          </div>
          <button 
            type="submit"
            class="w-full px-8 py-3 bg-blue-500 hover:bg-blue-600 text-white rounded-lg transition-colors font-semibold"
          >
            Send Message
          </button>
        </form>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: 'default'
})

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
