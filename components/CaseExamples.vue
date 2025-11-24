<template>
  <section id="cases" class="py-20 md:py-28 bg-gray-50">
    <div class="section-container">
      <div class="max-w-3xl mx-auto mb-16">
        <h2 class="heading-md mb-4">Case Examples</h2>
        <p class="text-lg text-gray-600 leading-relaxed">
          ตัวอย่างโครงการที่เราสำเร็จ (ชื่อลูกค้าไม่ระบุ)
        </p>
      </div>

      <div class="grid md:grid-cols-3 gap-8">
        <!-- Case 1 -->
        <div class="bg-white rounded-lg overflow-hidden border border-gray-200 hover:shadow-lg transition-shadow">
          <div class="h-48 bg-gradient-to-br from-blue-400 to-blue-600 flex items-center justify-center">
            <svg class="w-24 h-24 text-white opacity-50" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
            </svg>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-bold text-gray-900 mb-2">IoT Monitoring System</h3>
            <p class="text-gray-600 mb-4">
              ระบบติดตามสถานะเครื่องจักรแบบ Real-time สำหรับโรงงานผลิตอุตสาหกรรมหนัก
            </p>
            <div class="space-y-2">
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-blue-600 rounded-full"></span>
                <span>ลดเวลาหยุดทำงาน 40%</span>
              </div>
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-blue-600 rounded-full"></span>
                <span>เพิ่มประสิทธิภาพ 25%</span>
              </div>
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-blue-600 rounded-full"></span>
                <span>ประหยัดต้นทุน 30%</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Case 2 -->
        <div class="bg-white rounded-lg overflow-hidden border border-gray-200 hover:shadow-lg transition-shadow">
          <div class="h-48 bg-gradient-to-br from-purple-400 to-purple-600 flex items-center justify-center">
            <svg class="w-24 h-24 text-white opacity-50" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
            </svg>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-bold text-gray-900 mb-2">Factory Dashboard Platform</h3>
            <p class="text-gray-600 mb-4">
              แดชบอร์ดข้อมูลการผลิตแบบ Real-time พร้อมการวิเคราะห์และรายงาน
            </p>
            <div class="space-y-2">
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-purple-600 rounded-full"></span>
                <span>ติดตามผลผลิตแบบ Live</span>
              </div>
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-purple-600 rounded-full"></span>
                <span>รายงานอัตโนมัติ</span>
              </div>
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-purple-600 rounded-full"></span>
                <span>ตัดสินใจได้เร็วขึ้น</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Case 3 -->
        <div class="bg-white rounded-lg overflow-hidden border border-gray-200 hover:shadow-lg transition-shadow">
          <div class="h-48 bg-gradient-to-br from-teal-400 to-teal-600 flex items-center justify-center">
            <svg class="w-24 h-24 text-white opacity-50" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
            </svg>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-bold text-gray-900 mb-2">PLC Integration & Automation</h3>
            <p class="text-gray-600 mb-4">
              ระบบควบคุมอัตโนมัติและการประสานงาน PLC สำหรับสายการผลิต
            </p>
            <div class="space-y-2">
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-teal-600 rounded-full"></span>
                <span>ควบคุมอัตโนมัติ 100%</span>
              </div>
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-teal-600 rounded-full"></span>
                <span>ลดข้อผิดพลาดของมนุษย์</span>
              </div>
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-teal-600 rounded-full"></span>
                <span>เพิ่มความปลอดภัย</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Case 4 -->
        <div class="bg-white rounded-lg overflow-hidden border border-gray-200 hover:shadow-lg transition-shadow">
          <div class="h-48 bg-gradient-to-br from-blue-400 to-blue-600 flex items-center justify-center">
            <svg class="w-24 h-24 text-white opacity-50" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" />
            </svg>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-bold text-gray-900 mb-2">Custom Software Solution</h3>
            <p class="text-gray-600 mb-4">
              แอปพลิเคชัน Web และ Mobile ที่ปรับแต่งเฉพาะสำหรับการจัดการการผลิต
            </p>
            <div class="space-y-2">
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-blue-600 rounded-full"></span>
                <span>ใช้งานง่าย</span>
              </div>
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-blue-600 rounded-full"></span>
                <span>เข้าถึงได้จากทุกที่</span>
              </div>
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-blue-600 rounded-full"></span>
                <span>ปลอดภัยและเสถียร</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Case 5 -->
        <div class="bg-white rounded-lg overflow-hidden border border-gray-200 hover:shadow-lg transition-shadow">
          <div class="h-48 bg-gradient-to-br from-purple-400 to-purple-600 flex items-center justify-center">
            <svg class="w-24 h-24 text-white opacity-50" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
            </svg>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-bold text-gray-900 mb-2">Network Infrastructure</h3>
            <p class="text-gray-600 mb-4">
              ออกแบบและติดตั้งโครงสร้างเครือข่ายที่ปลอดภัยและเสถียรสำหรับโรงงาน
            </p>
            <div class="space-y-2">
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-purple-600 rounded-full"></span>
                <span>ความเร็วสูง</span>
              </div>
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-purple-600 rounded-full"></span>
                <span>ปลอดภัยและเข้ารหัส</span>
              </div>
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-purple-600 rounded-full"></span>
                <span>ความเสถียร 99.9%</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Case 6 -->
        <div class="bg-white rounded-lg overflow-hidden border border-gray-200 hover:shadow-lg transition-shadow">
          <div class="h-48 bg-gradient-to-br from-teal-400 to-teal-600 flex items-center justify-center">
            <svg class="w-24 h-24 text-white opacity-50" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z" />
            </svg>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-bold text-gray-900 mb-2">Maintenance & Support</h3>
            <p class="text-gray-600 mb-4">
              บริการบำรุงรักษาและสนับสนุนระยะยาวสำหรับระบบอุตสาหกรรม
            </p>
            <div class="space-y-2">
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-teal-600 rounded-full"></span>
                <span>ตรวจสอบเป็นระยะ</span>
              </div>
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-teal-600 rounded-full"></span>
                <span>ซ่อมแซมฉุกเฉิน</span>
              </div>
              <div class="flex items-center gap-2 text-sm text-gray-700">
                <span class="w-2 h-2 bg-teal-600 rounded-full"></span>
                <span>ลดต้นทุนการดำเนินการ</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>
