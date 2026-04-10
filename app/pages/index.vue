<script setup>
// Nuxt 3 官方页面级重定向
// SSR 阶段返回 302 状态码，CSR 阶段使用 router.replace 避免浏览器历史循环
navigateTo('/dashboard', { replace: true })
</script>

<template>
  <!-- 仅作为 SSR 渲染占位，实际请求会被重定向拦截，用户几乎不可见 -->
  <div class="flex min-h-screen items-center justify-center bg-background">
    <span class="text-sm text-muted-foreground animate-pulse">正在跳转...</span>
  </div>
</template>
