<script setup>
import { onMounted } from 'vue'
import { navigateTo } from '#app'

onMounted(() => {
  // 客户端加载后立即跳转，保留 SSR 兼容性
  navigateTo('/dashboard', { replace: true })
})
</script>

<template>
  <!-- 占位布局，跳转瞬间不可见 -->
  <div class="flex min-h-screen items-center justify-center bg-background">
    <div class="animate-pulse text-sm text-muted-foreground">Loading...</div>
  </div>
</template>
