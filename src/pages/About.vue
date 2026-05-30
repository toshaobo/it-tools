<script setup lang="ts">
import { useHead } from '@vueuse/head';

// 1. 设置关于页面的浏览器标签标题
useHead({ title: 'About - SOS Zero Tools' });
</script>

<template>
  <div class="about-container" mx-auto mt-50px max-w-600px px-4>
    <h1 style="font-size: 28px; font-weight: bold; margin-bottom: 20px; color: var(--primary-color, #18a058);">
      About SOS Zero Tools
    </h1>
    
    <p style="font-size: 16px; line-height: 1.6; margin-bottom: 15px; color: #555;">
      Welcome to <strong>SOS Zero Tools</strong>! We provide a free, fast, and secure collection of handy online web tools designed to supercharge daily technical workflows for developers, designers, and IT professionals with zero delay.
    </p>

    <p style="font-size: 16px; line-height: 1.6; margin-bottom: 30px; color: #555;">
      Our mission is to offer the ultimate all-in-one toolbox that is lightweight, respects your privacy, and requires no registration.
    </p>

    <hr style="border: 0; border-top: 1px solid #eee; margin-bottom: 25px;" />

    <h2 style="font-size: 20px; font-weight: bold; margin-bottom: 15px;">
      Contact & Business
    </h2>
    
    <p style="font-size: 15px; line-height: 1.6; color: #666;">
      For business inquiries, advertising cooperation, or custom tool development, please visit our official home page:
    </p>
    
    <p style="margin-top: 15px;">
      <a href="https://sos0.com" target="_blank" style="font-size: 16px; color: #18a058; font-weight: bold; text-decoration: none; border-bottom: 2px solid #18a058;">
        👉 Back to sos0.com
      </a>
    </p>
  </div>
</template>

<style scoped>
/* 保证在暗黑模式和亮色模式下都有良好的自适应阅读体验 */
.about-container {
  font-family: sans-serif;
}
</style>
