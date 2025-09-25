<script setup>
// Component logic goes here
</script>

<template>
  <div class="space-y-8">
    <div class="text-center">
      <h1 class="text-4xl font-bold text-gray-900 mb-4">Welcome to Your Vue 3 App</h1>
      <p class="text-xl text-gray-600">Built with Vue 3, Vue Router, Pinia, and Tailwind CSS</p>
    </div>

    <div class="bg-white rounded-lg shadow-md p-6">
      <h2 class="text-2xl font-semibold text-gray-800 mb-4">Getting Started</h2>
      <p class="text-gray-600 mb-4">
        This is a starter template with Tailwind CSS already configured. You can start building your application by editing the components in the <code class="bg-gray-100 px-2 py-1 rounded">src/views</code> directory.
      </p>
      
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 mt-8">
        <div class="border rounded-lg p-4 hover:shadow-lg transition-shadow">
          <div class="text-blue-500 mb-2">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
            </svg>
          </div>
          <h3 class="font-semibold text-lg mb-2">Vue 3</h3>
          <p class="text-gray-600 text-sm">The Progressive JavaScript Framework</p>
        </div>
        
        <div class="border rounded-lg p-4 hover:shadow-lg transition-shadow">
          <div class="text-green-500 mb-2">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13.828 10.172a4 4 0 00-5.656 0l-4 4a4 4 0 105.656 5.656l1.102-1.101m-.758-4.899a4 4 0 005.656 0l4-4a4 4 0 00-5.656-5.656l-1.1 1.1" />
            </svg>
          </div>
          <h3 class="font-semibold text-lg mb-2">Vue Router</h3>
          <p class="text-gray-600 text-sm">Single Page Application routing</p>
        </div>
        
        <div class="border rounded-lg p-4 hover:shadow-lg transition-shadow">
          <div class="text-yellow-500 mb-2">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10" />
            </svg>
          </div>
          <h3 class="font-semibold text-lg mb-2">Pinia</h3>
          <p class="text-gray-600 text-sm">State management for Vue</p>
        </div>
      </div>
      
      <div class="mt-8">
        <h3 class="text-xl font-semibold mb-4">Quick Links</h3>
        <div class="flex flex-wrap gap-4">
          <a href="https://vuejs.org/" target="_blank" class="px-4 py-2 bg-blue-500 text-white rounded hover:bg-blue-600 transition-colors">
            Vue 3 Docs
          </a>
          <a href="https://router.vuejs.org/" target="_blank" class="px-4 py-2 bg-green-500 text-white rounded hover:bg-green-600 transition-colors">
            Vue Router Docs
          </a>
          <a href="https://pinia.vuejs.org/" target="_blank" class="px-4 py-2 bg-yellow-500 text-white rounded hover:bg-yellow-600 transition-colors">
            Pinia Docs
          </a>
          <a href="https://tailwindcss.com/" target="_blank" class="px-4 py-2 bg-cyan-500 text-white rounded hover:bg-cyan-600 transition-colors">
            Tailwind CSS Docs
          </a>
        </div>
      </div>
    </div>
  </div>
</template>
