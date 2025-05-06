<script setup lang="ts">
import Card from '@/components/Card.vue';
import Table from '@/components/Table.vue';
</script>

<template>
  <nav class="flex items-center justify-between h-16 px-6 border-b bg-muted/40">
    <form class="w-full max-w-96">
      <Input type="text" value="Search..." class="w-full pl-8 bg-background" />
    
    </form>
    <div class="w-8 h-8 bg-white rounded-full"></div>

  </nav>
  <main>
    <div class="relative">
        <Card class="relative mt-10"></Card>
      </div>
      <Table></Table>
  </main>
</template>

<style scoped>

</style>
