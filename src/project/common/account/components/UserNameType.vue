<template>
  <ul class="user-name-type">
    <li>
      <i class="icon icon-size-18 icon-mb--4 icon-email"></i>
      手机
    </li>
    <li>
      <i class="icon icon-size-18 icon-mb--4 icon-email"></i>
      邮箱
    </li>
  </ul>
</template>

<script>
export default {
  name: "UserNameType",
  components: {},
  data() {
    return {};
  },
  created() {},
  methods: {}
};
</script>

<style lang="scss" scoped>
.user-name-type {
  text-align: right;
  li {
    display: inline-block;
    margin-left: 15px;
    padding: 7px 14px;
    border-radius: 100px;
    background-color: #fff;
    font-size: 14px;
    line-height: 18px;
    color: #ccc;
  }
}
</style>
