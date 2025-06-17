<template>
  <div class="c">
    <div class="container">
      <div class="title">空调产品-营收及占比趋势（示例数据）</div>
        <div id="chart"></div>
        <div class="tooltip"></div>
      </div>
      <button class="btn" id="dispose">销毁</button>
      <button class="btn" id="restore">恢复默认视图</button>
      <button class="btn" id="update">更新视图</button>
      <button class="btn" id="zoomIn">放大(2x)</button>
      <button class="btn" id="zoomOut">缩小(0.5x)</button>
      <button class="btn" id="zoomCustom">自定义缩放(3x,[-100,-50])</button>
      <button class="btn" id="switchData1">切换到常规数据</button>
      <button class="btn" id="switchData2">切换到无分组数据</button>
      <button class="btn" id="toggleZoom">切换缩放开关</button>
    </div>
</template>

<script setup lang="ts">
</script>