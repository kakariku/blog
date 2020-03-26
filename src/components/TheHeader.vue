<template>
  <div class="header">
    <div class="title">
      Roo
    </div>
    <div class="category">
      <div>AAAAA</div>
      <div>AAAAA</div>
      <div>AAAAA</div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
// import Logo from '~/components/Logo.vue'
// import Header from '~/componets/Header.vue'

// interface User {
//   name: string
// }

// export type DataType = {
//   name: string
//   cost: number
// }

export default Vue.extend({
  data() {
    return {}
  }
})
</script>

<style lang="scss" scoped>
.header {
  .title {
    display: inline-block;
    height: 20%;
    width: 100%;
  }

  .category {
    display: flex;
  }
}
</style>
