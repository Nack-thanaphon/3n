<template>
  <section id="what-we-do" class="py-20 md:py-28 bg-gray-50">
    <div class="section-container">
      <div class="max-w-3xl mx-auto mb-16">
        <h2 class="heading-md mb-4">What We Do</h2>
        <p class="text-lg text-gray-600 leading-relaxed">
          บริการหลักของเราครอบคลุมทั้งการออกแบบ การพัฒนา การติดตั้ง และการบำรุงรักษาระบบอุตสาหกรรมแบบครบวงจร
        </p>
      </div>

      <div class="grid md:grid-cols-2 gap-6">
        <!-- Service 1 -->
        <div class="p-6 bg-white rounded-lg border border-gray-200 hover:border-blue-300 hover:shadow-md transition-all">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 bg-blue-100 rounded-lg flex items-center justify-center flex-shrink-0">
              <svg class="w-6 h-6 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
              </svg>
            </div>
            <div>
              <h3 class="text-lg font-bold text-gray-900 mb-2">IoT & Machine Monitoring</h3>
              <p class="text-gray-600">ติดตั้งเซ็นเซอร์และระบบ IoT เพื่อติดตามสถานะเครื่องจักรแบบ Real-time ลดเวลาหยุดทำงานและเพิ่มประสิทธิภาพ</p>
            </div>
          </div>
        </div>

        <!-- Service 2 -->
        <div class="p-6 bg-white rounded-lg border border-gray-200 hover:border-blue-300 hover:shadow-md transition-all">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 bg-blue-100 rounded-lg flex items-center justify-center flex-shrink-0">
              <svg class="w-6 h-6 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
              </svg>
            </div>
            <div>
              <h3 class="text-lg font-bold text-gray-900 mb-2">Factory Dashboard & Data Platform</h3>
              <p class="text-gray-600">สร้างแดชบอร์ดที่แสดงข้อมูลการผลิตแบบ Real-time พร้อมการวิเคราะห์และรายงานสำหรับการตัดสินใจ</p>
            </div>
          </div>
        </div>

        <!-- Service 3 -->
        <div class="p-6 bg-white rounded-lg border border-gray-200 hover:border-blue-300 hover:shadow-md transition-all">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 bg-blue-100 rounded-lg flex items-center justify-center flex-shrink-0">
              <svg class="w-6 h-6 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
              </svg>
            </div>
            <div>
              <h3 class="text-lg font-bold text-gray-900 mb-2">SCADA-Lite / PLC Integration</h3>
              <p class="text-gray-600">พัฒนาระบบควบคุมเบาและประสานงาน PLC เพื่อให้ระบบเครื่องจักรทำงานอย่างอัตโนมัติและปลอดภัย</p>
            </div>
          </div>
        </div>

        <!-- Service 4 -->
        <div class="p-6 bg-white rounded-lg border border-gray-200 hover:border-blue-300 hover:shadow-md transition-all">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 bg-blue-100 rounded-lg flex items-center justify-center flex-shrink-0">
              <svg class="w-6 h-6 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" />
              </svg>
            </div>
            <div>
              <h3 class="text-lg font-bold text-gray-900 mb-2">Software Development</h3>
              <p class="text-gray-600">พัฒนาแอปพลิเคชัน Web, Mobile และ Cloud ที่เหมาะกับความต้องการเฉพาะของธุรกิจคุณ</p>
            </div>
          </div>
        </div>

        <!-- Service 5 -->
        <div class="p-6 bg-white rounded-lg border border-gray-200 hover:border-blue-300 hover:shadow-md transition-all">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 bg-blue-100 rounded-lg flex items-center justify-center flex-shrink-0">
              <svg class="w-6 h-6 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
              </svg>
            </div>
            <div>
              <h3 class="text-lg font-bold text-gray-900 mb-2">Network & Infrastructure</h3>
              <p class="text-gray-600">ออกแบบและบำรุงรักษาโครงสร้างเครือข่ายที่ปลอดภัย เสถียร และสามารถรองรับการขยายตัวของธุรกิจ</p>
            </div>
          </div>
        </div>

        <!-- Service 6 -->
        <div class="p-6 bg-white rounded-lg border border-gray-200 hover:border-blue-300 hover:shadow-md transition-all">
          <div class="flex items-start gap-4">
            <div class="w-12 h-12 bg-blue-100 rounded-lg flex items-center justify-center flex-shrink-0">
              <svg class="w-6 h-6 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z" />
              </svg>
            </div>
            <div>
              <h3 class="text-lg font-bold text-gray-900 mb-2">Machine Installation & Maintenance</h3>
              <p class="text-gray-600">ติดตั้ง ปรับแต่ง และบำรุงรักษาเครื่องจักรและอุปกรณ์อุตสาหกรรมเพื่อให้ทำงานได้อย่างเหมาะสม</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>
