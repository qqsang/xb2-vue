<template>
  <div>
    <ul>
      <li>首页{{ msg }}</li>
      <li>关于我们</li>
      <li>企业简介</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "menu",
  props: {
    msg: String,
  },
};
</script>
