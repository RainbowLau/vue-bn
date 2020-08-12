<template>
  <el-container>
    <el-aside style="width: 200px;margin-top: 20px">
      <switch></switch>
      <SideMenu></SideMenu>
    </el-aside>
    <el-main>
      <Books></Books>
    </el-main>
  </el-container>
</template>

<script>
    import SideMenu from "./SideMenu";
    import Books from "../common/Books";
    export default {
      name: "LibraryIndex",
      components: {Books, SideMenu}
    }
</script>

<style scoped>
  .books-area {
    width: 990px;
    margin-left: auto;
    margin-right: auto;
  }
</style>
