<script setup lang="ts">
// @ts-ignore
import zhCn from 'element-plus/dist/locale/zh-cn.mjs'
import { ElConfigProvider } from 'element-plus'
</script>

<template>
  <!-- 项目里面配置了这个中文的就不用倒入这个了 -->
  <ElConfigProvider :locale="zhCn">Hello world!</ElConfigProvider>
</template>
