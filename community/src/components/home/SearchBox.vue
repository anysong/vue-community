<template>
  <div class="search-box">
      <i></i>
      <input type="text">
      <button>搜索</button>
  </div>
</template>

<style lang="less" scoped>
    .search-box {
        width: 100%;
        height: 42px;
        padding-left: 200px;
        box-sizing: border-box;
        position: relative;
        i {
            width: 200px;
            height: 100%;
            position: absolute;
            top: 0;
            left: 0;
        }
        input {
            width: 100%;
            height: 100%;
            box-sizing: border-box;
        }
        button {
            width: 100px;
            height: 100%;
            position: absolute;
            top: 0;
            right: 0;
        }
    }
</style>

