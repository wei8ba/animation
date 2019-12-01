<template>
  <div id="app">
    <a-row>
      <a-col :span="8">
        <a-card class="curd" title="素材1">
          <!-- <img src="./assets/logo.png" alt=""> -->
          <video style="width:100%" autoplay="autoplay" loop controls>
            <source src="./assets/circle.webm" type="video/webm" />
          </video>
        </a-card>
      </a-col>
      <a-col :span="8">
        <a-card title="素材2">
          <video style="width:100%" controls autoplay="autoplay" loop>
            <source src="./assets/global.webm" type="video/webm" />
          </video>
        </a-card>
      </a-col>
      <a-col :span="8">
        <a-card title="柱子"></a-card>
      </a-col>
    </a-row>
    <a-row>
      <a-col :span="8">
        <a-card title="线"></a-card>
        <a-card title="框"></a-card>
      </a-col>
      <a-col :span="16">
        <a-card title="预览"></a-card>
      </a-col>
    </a-row>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class App extends Vue {}
</script>

<style lang="scss">
.curd {
  width: 100%;
}
</style>
