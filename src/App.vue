<template>
  <div id="app">
    <Sidebar />
    <Fees />
    <Performance />
    <Absent />
  </div>
</template>

<script>

import Sidebar from '@/components/Sidebar.vue'
import Fees from '@/components/Fees.vue'
import Performance from '@/components/Performance.vue'
import Absent from '@/components/Absent.vue'

export default {
  name: 'app',
  components: {
   Sidebar,
   Fees,
   Performance,
   Absent
  }
}

</script>

<style>
body {
  margin: 0;
  background: #F8F8F8;
}

</style>
