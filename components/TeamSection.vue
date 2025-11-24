<template>
  <section id="team" class="py-20 md:py-28 bg-white">
    <div class="section-container">
      <div class="max-w-3xl mx-auto mb-16">
        <h2 class="heading-md mb-4">Our Team</h2>
        <p class="text-lg text-gray-600 leading-relaxed">
          ทีมวิศวกรมืออาชีพที่มีความเชี่ยวชาญและประสบการณ์ยาวนานในสามสายงาน
        </p>
      </div>

      <div class="grid md:grid-cols-3 gap-8">
        <!-- Team Member 1 -->
        <div class="text-center">
          <div class="mb-6 relative">
            <div class="w-32 h-32 mx-auto bg-gradient-to-br from-blue-400 to-blue-600 rounded-full flex items-center justify-center">
              <svg class="w-16 h-16 text-white" fill="currentColor" viewBox="0 0 24 24">
                <path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z" />
              </svg>
            </div>
            <div class="absolute bottom-0 right-0 w-8 h-8 bg-blue-600 rounded-full border-4 border-white flex items-center justify-center">
              <svg class="w-4 h-4 text-white" fill="currentColor" viewBox="0 0 24 24">
                <path d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
              </svg>
            </div>
          </div>
          <h3 class="text-xl font-bold text-gray-900 mb-1">Network Lead</h3>
          <p class="text-gray-600 mb-4">วิศวกรเครือข่าย</p>
          <p class="text-gray-600 text-sm leading-relaxed">
            ผู้นำทีมเครือข่ายที่มีประสบการณ์ในการออกแบบและบำรุงรักษาโครงสร้างเครือข่ายอุตสาหกรรมขนาดใหญ่ ความเชี่ยวชาญในด้าน Industrial IoT, Cybersecurity และ Network Optimization
          </p>
        </div>

        <!-- Team Member 2 -->
        <div class="text-center">
          <div class="mb-6 relative">
            <div class="w-32 h-32 mx-auto bg-gradient-to-br from-purple-400 to-purple-600 rounded-full flex items-center justify-center">
              <svg class="w-16 h-16 text-white" fill="currentColor" viewBox="0 0 24 24">
                <path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z" />
              </svg>
            </div>
            <div class="absolute bottom-0 right-0 w-8 h-8 bg-purple-600 rounded-full border-4 border-white flex items-center justify-center">
              <svg class="w-4 h-4 text-white" fill="currentColor" viewBox="0 0 24 24">
                <path d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" />
              </svg>
            </div>
          </div>
          <h3 class="text-xl font-bold text-gray-900 mb-1">Software Lead</h3>
          <p class="text-gray-600 mb-4">วิศวกรซอฟต์แวร์</p>
          <p class="text-gray-600 text-sm leading-relaxed">
            ผู้นำทีมซอฟต์แวร์ที่เชี่ยวชาญในการพัฒนาแอปพลิเคชัน Web, Mobile และ Cloud สำหรับอุตสาหกรรม ความเชี่ยวชาญในด้าน Full-stack Development, Database Design และ Cloud Architecture
          </p>
        </div>

        <!-- Team Member 3 -->
        <div class="text-center">
          <div class="mb-6 relative">
            <div class="w-32 h-32 mx-auto bg-gradient-to-br from-teal-400 to-teal-600 rounded-full flex items-center justify-center">
              <svg class="w-16 h-16 text-white" fill="currentColor" viewBox="0 0 24 24">
                <path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z" />
              </svg>
            </div>
            <div class="absolute bottom-0 right-0 w-8 h-8 bg-teal-600 rounded-full border-4 border-white flex items-center justify-center">
              <svg class="w-4 h-4 text-white" fill="currentColor" viewBox="0 0 24 24">
                <path d="M13 10V3L4 14h7v7l9-11h-7z" />
              </svg>
            </div>
          </div>
          <h3 class="text-xl font-bold text-gray-900 mb-1">Industrial Lead</h3>
          <p class="text-gray-600 mb-4">วิศวกรอุตสาหกรรม</p>
          <p class="text-gray-600 text-sm leading-relaxed">
            ผู้นำทีมอุตสาหกรรมที่มีประสบการณ์ในการติดตั้ง ปรับแต่ง และบำรุงรักษาเครื่องจักร PLC และอุปกรณ์อุตสาหกรรม ความเชี่ยวชาญในด้าน Automation, SCADA Systems และ Preventive Maintenance
          </p>
        </div>
      </div>

      <!-- Team Stats -->
      <div class="mt-16 pt-16 border-t border-gray-200">
        <div class="grid md:grid-cols-4 gap-8">
          <div class="text-center">
            <div class="text-4xl font-bold text-blue-600 mb-2">50+</div>
            <p class="text-gray-600">โครงการสำเร็จ</p>
          </div>
          <div class="text-center">
            <div class="text-4xl font-bold text-purple-600 mb-2">15+</div>
            <p class="text-gray-600">ปีประสบการณ์</p>
          </div>
          <div class="text-center">
            <div class="text-4xl font-bold text-teal-600 mb-2">100%</div>
            <p class="text-gray-600">ความพึงพอใจลูกค้า</p>
          </div>
          <div class="text-center">
            <div class="text-4xl font-bold text-blue-600 mb-2">24/7</div>
            <p class="text-gray-600">การสนับสนุน</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>
