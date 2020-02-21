<template>
  <div>
    <svg-icon icon-class="download" @click="handleDownload"/>
  </div>
</template>

<script>
export default {
  name: 'pactera',
  data() {
    return {
      url: 'https://gitee.com/y_project/pactera-Vue'
    }
  },
  methods: {
    handleDownload() {
      window.open(this.url)
    }
  }
}
</script>
