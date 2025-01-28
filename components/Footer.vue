<template>
  <footer class="py-6 text-muted-foreground md:px-8 md:py-0">
    <div class="container flex flex-col items-center justify-between gap-2 md:h-24 md:flex-row">
      My footer
      <span class="flex-1" />
      {{ footer.credits }}
    </div>
  </footer>
</template>

<script setup lang="ts">
const { footer } = useConfig().value;
</script>
