<template>
  <view class="index">
    <text>{{ msg }}</text>
    <nut-button type="primary">按钮测试</nut-button>
  </view>
</template>

<script>
import { ref } from 'vue';
import './index.scss';

export default {
  setup() {
    const msg = ref('Hello world');
    return {
      msg,
    };
  },
};
</script>
