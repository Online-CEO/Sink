<template>
  <div class="flex min-h-screen flex-col items-center justify-center bg-background p-4">
    <div class="w-full max-w-sm space-y-6 rounded-lg border bg-card p-8 text-center shadow-sm">
      <h1 class="text-2xl font-bold tracking-tight">Sink</h1>
      
      <NuxtLink
        to="/dashboard"
        class="inline-flex w-full items-center justify-center gap-2 rounded-md bg-primary px-4 py-2.5 text-sm font-medium text-primary-foreground shadow transition-colors hover:bg-primary/90 focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring"
      >
        🔐 进入管理后台
      </NuxtLink>
      
    </div>
  </div>
</template>
