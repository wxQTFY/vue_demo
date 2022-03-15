
<template>
    <el-container>
      <el-header>模拟彩票自选系统</el-header>
      <el-container>
        <el-aside width="200px">
          <TicAside></TicAside>
        </el-aside>
        <el-container>
          <el-main>Main</el-main>
        </el-container>
      </el-container>
      <el-footer>Design ©2022 Created by wang</el-footer>
    </el-container>
</template>

<script>
import TicAside from './components/TicAside.vue'
 export default{
   components:{
     TicAside
   }
 }

</script>

<style>
  .el-header, .el-footer {
    background-color: #B3C0D1;
    color: #333;
    text-align: center;
    line-height: 60px;
  }
  .el-main {
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
    line-height: 160px;
  }
</style>
