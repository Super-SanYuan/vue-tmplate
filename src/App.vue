<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
import '@/styles/normalize.css'
import '@/styles/border.css'
import fastclick from 'fastclick'
fastclick.attach(document.bod) // 解决移动端点击事件300毫秒延迟问题

export default {
  name: 'App'
}
</script>
