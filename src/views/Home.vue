<template>
  <div class="home">
    <el-row type="flex">
      <el-col :span="24" class="title">
        淘个券
      </el-col>
    </el-row>
    <el-row type="flex" justify="center">
      <el-col :sm="6">
      <el-input placeholder="请输入商品名称搜索" prefix-icon="el-icon-search" v-model="input">
      </el-input>
      </el-col>
    </el-row>
    <el-row type="flex" justify="center" class="button">
      <el-button>搜索</el-button>
    </el-row>
  </div>
</template>

<script>

export default {
  name: 'home',
  data() {
    return {
      input: ''
    }
  }
}
</script>

<style lang="scss" scoped>
.home {
  .title {
    font-size: 40px;
    line-height: 140px;
  }
  .button{
    margin-top: 30px;
  }
}
</style>
