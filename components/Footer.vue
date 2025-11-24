<template>
  <footer class="bg-gray-900 text-gray-400 py-12">
    <div class="section-container">
      <div class="grid md:grid-cols-4 gap-8 mb-8">
        <!-- About -->
        <div>
          <div class="flex items-center gap-2 mb-4">
            <div class="w-8 h-8 bg-gradient-to-br from-blue-600 to-teal-600 rounded-lg flex items-center justify-center">
              <span class="text-white font-bold text-sm">3N</span>
            </div>
            <span class="font-bold text-white">3N Engineering</span>
          </div>
          <p class="text-sm leading-relaxed">
            ทีมวิศวกรมืออาชีพที่เชี่ยวชาญในการออกแบบและพัฒนาระบบอุตสาหกรรมแบบบูรณาการ
          </p>
        </div>

        <!-- Services -->
        <div>
          <h4 class="font-bold text-white mb-4">บริการ</h4>
          <ul class="space-y-2 text-sm">
            <li><a href="#what-we-do" class="hover:text-white transition-colors">IoT & Monitoring</a></li>
            <li><a href="#what-we-do" class="hover:text-white transition-colors">Factory Dashboard</a></li>
            <li><a href="#what-we-do" class="hover:text-white transition-colors">SCADA Integration</a></li>
            <li><a href="#what-we-do" class="hover:text-white transition-colors">Software Development</a></li>
          </ul>
        </div>

        <!-- Company -->
        <div>
          <h4 class="font-bold text-white mb-4">บริษัท</h4>
          <ul class="space-y-2 text-sm">
            <li><a href="#who-we-are" class="hover:text-white transition-colors">เกี่ยวกับเรา</a></li>
            <li><a href="#team" class="hover:text-white transition-colors">ทีมของเรา</a></li>
            <li><a href="#cases" class="hover:text-white transition-colors">ตัวอย่างงาน</a></li>
            <li><a href="#contact" class="hover:text-white transition-colors">ติดต่อเรา</a></li>
          </ul>
        </div>

        <!-- Legal -->
        <div>
          <h4 class="font-bold text-white mb-4">อื่นๆ</h4>
          <ul class="space-y-2 text-sm">
            <li><a href="#" class="hover:text-white transition-colors">นโยบายความเป็นส่วนตัว</a></li>
            <li><a href="#" class="hover:text-white transition-colors">เงื่อนไขการใช้งาน</a></li>
            <li><a href="#" class="hover:text-white transition-colors">นโยบายคุกกี้</a></li>
          </ul>
        </div>
      </div>

      <!-- Divider -->
      <div class="border-t border-gray-800 pt-8">
        <div class="flex flex-col md:flex-row justify-between items-center">
          <p class="text-sm text-gray-500">
            &copy; 2024 3N Engineering & Digital Solutions. All rights reserved.
          </p>
          <div class="flex gap-4 mt-4 md:mt-0">
            <a href="#" class="text-gray-500 hover:text-white transition-colors">
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                <path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z" />
              </svg>
            </a>
            <a href="#" class="text-gray-500 hover:text-white transition-colors">
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                <path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2s9 5 20 5a9.5 9.5 0 00-9-5.5c4.75 2.25 7-7 7-7a10.6 10.6 0 01-9.5 5" />
              </svg>
            </a>
            <a href="#" class="text-gray-500 hover:text-white transition-colors">
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.225 0z" />
              </svg>
            </a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup lang="ts">
</script>
