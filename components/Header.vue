<template>
  <header class="sticky top-0 z-50 bg-white border-b border-gray-200">
    <nav class="section-container py-4 flex items-center justify-between">
      <div class="flex items-center gap-2">
        <div class="w-10 h-10 bg-gradient-to-br from-blue-600 to-teal-600 rounded-lg flex items-center justify-center">
          <span class="text-white font-bold text-lg">3N</span>
        </div>
        <div class="hidden sm:block">
          <h1 class="text-lg font-bold text-gray-900">3N Engineering</h1>
          <p class="text-xs text-gray-500">Digital Solutions</p>
        </div>
      </div>

      <div class="hidden md:flex items-center gap-8">
        <a href="#who-we-are" class="text-gray-600 hover:text-blue-600 transition-colors">Who We Are</a>
        <a href="#what-we-do" class="text-gray-600 hover:text-blue-600 transition-colors">Services</a>
        <a href="#approach" class="text-gray-600 hover:text-blue-600 transition-colors">Approach</a>
        <a href="#cases" class="text-gray-600 hover:text-blue-600 transition-colors">Cases</a>
        <a href="#team" class="text-gray-600 hover:text-blue-600 transition-colors">Team</a>
        <a href="#contact" class="btn-primary text-sm">Contact Us</a>
      </div>

      <button class="md:hidden p-2 hover:bg-gray-100 rounded-lg">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
      </button>
    </nav>
  </header>
</template>

<script setup lang="ts">
</script>
