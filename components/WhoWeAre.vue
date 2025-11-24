<template>
  <section id="who-we-are" class="py-20 md:py-28 bg-white">
    <div class="section-container">
      <div class="max-w-3xl mx-auto mb-16">
        <h2 class="heading-md mb-4">Who We Are</h2>
        <p class="text-lg text-gray-600 leading-relaxed">
          เราคือทีมวิศวกรมืออาชีพที่เชี่ยวชาญในการออกแบบและพัฒนาระบบอุตสาหกรรมแบบบูรณาการ ด้วยความรู้ลึกในสามสายงาน เราสามารถแก้ไขปัญหาที่ซับซ้อนและสร้างโซลูชันที่ยั่งยืน
        </p>
      </div>

      <div class="grid md:grid-cols-3 gap-8">
        <!-- Network Engineering -->
        <div class="p-8 bg-gradient-to-br from-blue-50 to-blue-100 rounded-xl border border-blue-200 hover:shadow-lg transition-shadow">
          <div class="w-14 h-14 bg-blue-600 rounded-lg flex items-center justify-center mb-4">
            <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
            </svg>
          </div>
          <h3 class="text-xl font-bold text-gray-900 mb-3">Network Engineering</h3>
          <p class="text-gray-700 leading-relaxed">
            ออกแบบและบำรุงรักษาโครงสร้างเครือข่ายอุตสาหกรรมที่เสถียร ปลอดภัย และสามารถขยายได้ รองรับการสื่อสารแบบ Real-time ระหว่างอุปกรณ์
          </p>
        </div>

        <!-- Software Engineering -->
        <div class="p-8 bg-gradient-to-br from-purple-50 to-purple-100 rounded-xl border border-purple-200 hover:shadow-lg transition-shadow">
          <div class="w-14 h-14 bg-purple-600 rounded-lg flex items-center justify-center mb-4">
            <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4m0 0l-4 4m4-4H3" />
            </svg>
          </div>
          <h3 class="text-xl font-bold text-gray-900 mb-3">Software Engineering</h3>
          <p class="text-gray-700 leading-relaxed">
            พัฒนาแอปพลิเคชัน Web, Mobile และ Cloud ที่ปลอดภัย มีประสิทธิภาพ และใช้งานง่าย เพื่อให้คุณควบคุมและวิเคราะห์ข้อมูลอุตสาหกรรมได้อย่างมีประสิทธิผล
          </p>
        </div>

        <!-- Industrial Engineering -->
        <div class="p-8 bg-gradient-to-br from-teal-50 to-teal-100 rounded-xl border border-teal-200 hover:shadow-lg transition-shadow">
          <div class="w-14 h-14 bg-teal-600 rounded-lg flex items-center justify-center mb-4">
            <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
            </svg>
          </div>
          <h3 class="text-xl font-bold text-gray-900 mb-3">Industrial Engineering</h3>
          <p class="text-gray-700 leading-relaxed">
            ติดตั้ง บำรุงรักษา และปรับปรุงระบบเครื่องจักร PLC และอุปกรณ์อุตสาหกรรม เพื่อให้ได้ประสิทธิภาพสูงสุดและลดต้นทุนการดำเนินการ
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>
