<template>
  <el-row class="tac">
    <el-col>
      <el-menu
        default-active="1"
        class="el-menu-vertical-demo"
        background-color="#545c64"
        text-color="#fff"
        active-text-color="#ffd04b">
        <el-menu-item index="1" v-for="tic in tictype" :key="id">
          <i class="el-icon-menu"></i>
          <span slot="title">{{tic.ticname}}</span>
        </el-menu-item>
      </el-menu>
    </el-col>
  </el-row>
</template>

<script>
  export default{
    data(){
      return{
        tictype:[
          {id:1, ticname:'双色球'},
          {id:2, ticname:'大乐透'},
          {id:3, ticname:'快乐8'}
        ]
      }
    }
  }

</script>

<style>
</style>
