<template>
  <section id="contact" class="py-20 md:py-28 bg-gradient-to-br from-blue-600 to-teal-600">
    <div class="section-container">
      <div class="max-w-3xl mx-auto">
        <div class="text-center mb-12">
          <h2 class="text-4xl md:text-5xl font-bold text-white mb-4">เริ่มต้นโครงการของคุณ</h2>
          <p class="text-xl text-blue-100">
            ติดต่อเราวันนี้เพื่อปรึกษาเกี่ยวกับวิธีที่เราสามารถช่วยให้ธุรกิจของคุณเติบโต
          </p>
        </div>

        <div class="grid md:grid-cols-2 gap-8 mb-12">
          <!-- Contact Info -->
          <div class="space-y-6">
            <div class="flex items-start gap-4">
              <div class="w-12 h-12 bg-white bg-opacity-20 rounded-lg flex items-center justify-center flex-shrink-0 mt-1">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                </svg>
              </div>
              <div>
                <h3 class="text-lg font-bold text-white mb-1">Email</h3>
                <p class="text-blue-100">info@3nengineering.com</p>
              </div>
            </div>

            <div class="flex items-start gap-4">
              <div class="w-12 h-12 bg-white bg-opacity-20 rounded-lg flex items-center justify-center flex-shrink-0 mt-1">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 00.948.684l1.498 4.493a1 1 0 00.502.756l2.048 1.029a2 2 0 002.063-.063l3.034-2.024a1 1 0 00.97.004l2.49 1.245a1 1 0 00.502.756l1.498 4.493a1 1 0 00.948.684H21a2 2 0 012 2v2.75a.75.75 0 01-1.5 0V19H4.75v2.25a.75.75 0 01-1.5 0V5z" />
                </svg>
              </div>
              <div>
                <h3 class="text-lg font-bold text-white mb-1">Phone</h3>
                <p class="text-blue-100">+66 (0) XX-XXX-XXXX</p>
              </div>
            </div>

            <div class="flex items-start gap-4">
              <div class="w-12 h-12 bg-white bg-opacity-20 rounded-lg flex items-center justify-center flex-shrink-0 mt-1">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                </svg>
              </div>
              <div>
                <h3 class="text-lg font-bold text-white mb-1">Address</h3>
                <p class="text-blue-100">Bangkok, Thailand</p>
              </div>
            </div>

            <div class="flex items-start gap-4">
              <div class="w-12 h-12 bg-white bg-opacity-20 rounded-lg flex items-center justify-center flex-shrink-0 mt-1">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </div>
              <div>
                <h3 class="text-lg font-bold text-white mb-1">Business Hours</h3>
                <p class="text-blue-100">Monday - Friday: 9:00 AM - 6:00 PM</p>
                <p class="text-blue-100">Saturday - Sunday: Closed</p>
              </div>
            </div>
          </div>

          <!-- Contact Form -->
          <form @submit.prevent="handleSubmit" class="space-y-4">
            <div>
              <label for="name" class="block text-white font-semibold mb-2">ชื่อ</label>
              <input
                id="name"
                v-model="form.name"
                type="text"
                placeholder="ชื่อของคุณ"
                class="w-full px-4 py-3 rounded-lg bg-white bg-opacity-10 border border-white border-opacity-20 text-white placeholder-blue-200 focus:outline-none focus:border-white focus:bg-opacity-20 transition-all"
                required
              />
            </div>

            <div>
              <label for="email" class="block text-white font-semibold mb-2">Email</label>
              <input
                id="email"
                v-model="form.email"
                type="email"
                placeholder="อีเมลของคุณ"
                class="w-full px-4 py-3 rounded-lg bg-white bg-opacity-10 border border-white border-opacity-20 text-white placeholder-blue-200 focus:outline-none focus:border-white focus:bg-opacity-20 transition-all"
                required
              />
            </div>

            <div>
              <label for="subject" class="block text-white font-semibold mb-2">เรื่อง</label>
              <input
                id="subject"
                v-model="form.subject"
                type="text"
                placeholder="เรื่องของข้อความ"
                class="w-full px-4 py-3 rounded-lg bg-white bg-opacity-10 border border-white border-opacity-20 text-white placeholder-blue-200 focus:outline-none focus:border-white focus:bg-opacity-20 transition-all"
                required
              />
            </div>

            <div>
              <label for="message" class="block text-white font-semibold mb-2">ข้อความ</label>
              <textarea
                id="message"
                v-model="form.message"
                placeholder="บอกเราเกี่ยวกับโครงการของคุณ"
                rows="4"
                class="w-full px-4 py-3 rounded-lg bg-white bg-opacity-10 border border-white border-opacity-20 text-white placeholder-blue-200 focus:outline-none focus:border-white focus:bg-opacity-20 transition-all resize-none"
                required
              ></textarea>
            </div>

            <button
              type="submit"
              class="w-full px-6 py-3 bg-white text-blue-600 rounded-lg font-bold hover:bg-blue-50 transition-colors"
            >
              ส่งข้อความ
            </button>

            <p v-if="submitMessage" class="text-center text-white text-sm">
              {{ submitMessage }}
            </p>
          </form>
        </div>

        <!-- Social Links -->
        <div class="text-center pt-8 border-t border-white border-opacity-20">
          <p class="text-blue-100 mb-4">ติดตามเราบนโซเชียลมีเดีย</p>
          <div class="flex justify-center gap-4">
            <a href="#" class="w-10 h-10 bg-white bg-opacity-10 rounded-full flex items-center justify-center hover:bg-opacity-20 transition-all">
              <svg class="w-5 h-5 text-white" fill="currentColor" viewBox="0 0 24 24">
                <path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z" />
              </svg>
            </a>
            <a href="#" class="w-10 h-10 bg-white bg-opacity-10 rounded-full flex items-center justify-center hover:bg-opacity-20 transition-all">
              <svg class="w-5 h-5 text-white" fill="currentColor" viewBox="0 0 24 24">
                <path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2s9 5 20 5a9.5 9.5 0 00-9-5.5c4.75 2.25 7-7 7-7a10.6 10.6 0 01-9.5 5" />
              </svg>
            </a>
            <a href="#" class="w-10 h-10 bg-white bg-opacity-10 rounded-full flex items-center justify-center hover:bg-opacity-20 transition-all">
              <svg class="w-5 h-5 text-white" fill="currentColor" viewBox="0 0 24 24">
                <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.225 0z" />
              </svg>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const form = ref({
  name: '',
  email: '',
  subject: '',
  message: '',
})

const submitMessage = ref('')

const handleSubmit = () => {
  // In a real application, you would send this data to a server
  submitMessage.value = 'ขอบคุณที่ติดต่อเรา! เราจะตอบกลับในเร็วๆ นี้'
  form.value = { name: '', email: '', subject: '', message: '' }
  setTimeout(() => {
    submitMessage.value = ''
  }, 5000)
}
</script>
