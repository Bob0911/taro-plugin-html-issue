<template>
  <view class="flex">
    <button>Hello world</button>
    <input type="text" />
  </view>
</template>

<script>
import { ref } from "vue";
import "./index.css";

export default {
  setup() {
    const msg = ref("Hello world");
    return {
      msg,
    };
  },
};
</script>
<style>
.flex {
  display: flex;
}
</style>
