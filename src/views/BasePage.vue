<template>
    <div id="basePage">
        <base-header></base-header>
        <slot></slot>
        <base-footer></base-footer>
    </div>
</template>

<script>
import BaseHeader from '@/components/BaseHeader.vue'
export default {
  components: {
    BaseHeader
  }
}
</script>
<style lang="scss">
</style>
