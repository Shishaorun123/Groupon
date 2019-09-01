<template>
    <div class="header-v2">
      <div class="header1">
        <div class="user-wrapper">
          <div class="ser-wrapper">
          <a href="#">Sell</a>
          <a href="#">Help</a>
          <a href="#">Sign Up</a>
          </div>
        </div>
      </div>
      <!-- 商品搜索 -->
      <div class="header2">
        <!-- logo -->
        <div class="ls-eeader-top">
          <a href="#" id="ls-groupon-logo">
            <img src="../assets/logo2.png" alt="">
          </a>
        <!-- 索引，导航 -->
          <div class="redesign-buttons">
            Categories
            <img src="../assets/jiantou.png" alt="">
          </div>
            <!-- 搜索form表单 -->
          <div class="ls-search-wrapper">
            <!-- 搜索框 -->
            <form class="rch-bar-v2" action="">
              <div class="icon-magnifying-glass">
                <img class="icon" src="../assets/sou.png" alt="">
                <input id="ls-search" type="search" placeholder="Search Groupon">
              </div>
            <!-- 定位框 -->
              <div class="search-box">
                <img class="icon" src="../assets/dinwei.png" alt="">
                <input type="text" placeholder="Chicago">
              </div>
            <!-- 提交按钮 -->
              <button class="ls-header-search-button">
                <img src="../assets/sousuo.png" alt="">
              </button>
            </form>
          </div>
          <!-- 购物车 -->
            <a href="#" class="cart-link">
              <img src="../assets/gouwu.png" alt=""> 
            </a>
          <!-- 提示消息 -->
            <a href="#" class="cart-link">
              <img id="mail" src="../assets/ld.png" alt=""> 
            </a>
            <!-- 登录 -->
          <div class="redesign-buttons sign-ln">
            Sign ln
            <img src="../assets/jiantou.png" alt="">
          </div>
        </div>
        <div class="nav">
        <div class="page-container">
          <ul class="primary-nav">
            <li class="primary-nav-tab">
              <a href="javascript">Featured</a>
            </li>
            <li class="primary-nav-tab">
              <a href="javascript">Things To Do</a>
            </li>
            <li class="primary-nav-tab">
              <a href="javascript">Beauty & Spas</a>
              </li>
            <li class="primary-nav-tab">
              <a href="javascript">Goods</a>
            </li>
            <li class="primary-nav-tab">
              <a href="javascript">Travel</a>
            </li>
            <li>
              <el-dropdown>
                <span class="el-dropdown-link ls-eeader-top">
                  Coupons<i class="el-icon-arrow-down el-icon--right"></i>
                </span>
                <el-dropdown-menu slot="dropdown">
                  <el-dropdown-item>1</el-dropdown-item>
                  <el-dropdown-item>2</el-dropdown-item>
                  <el-dropdown-item>3</el-dropdown-item>
                  <el-dropdown-item disabled>4</el-dropdown-item>
                  <el-dropdown-item divided>5</el-dropdown-item>
                </el-dropdown-menu>
              </el-dropdown>
            </li>
          </ul>
        </div>
      </div>
      </div>
      <!-- 商品导航 -->
      
    </div>
    
</template>

<script>
export default {
  name: '',
  props: {
    
  }
}
</script>
  

<style scoped>
  *{
    margin: 0;
    padding: 0;
  }
/* 公共样式 */
/* a去下划线 */
a{text-decoration: none;}

  .header1{
    height: 30px;
    position: relative;
    background:#348700;
    width: 100%;
    opacity: 1;
    top: 0;
    min-width: 1150px
  }
  /* input点击去边框 */
  :focus{outline:none}

  .user-wrapper {
    margin: 0 auto;
    max-width: 1080px;
    z-index: 11;
}
/* sell help sign UP样式 */
  .ser-wrapper{
    text-align: right;
    padding: 8px 7px 0;
  }
  .ser-wrapper>a{
    margin: 0 0 0 24px;
    border: 0;
    vertical-align: top;
    display: inline-block;
    line-height: 15px;
    font-size: 12px;
    color: #fff;
    text-decoration: blink;
    
  }
  
/* 搜索区样式 */
  .header2{
    background: #53a318;
    position: relative;
    z-index: 20;
    min-height: 59px;
    min-width: 1150px
    
  }
  .ls-eeader-top{
    max-width: 1080px;
    width: 100%;
    position: relative;
    z-index: 20;
    margin: 0 auto;
    padding: 12px 7px;
    align-items: center;
    height: 39px;
    display: flex;
  }
  /* logo样式 */
  #ls-groupon-logo{
    width: 126px;
    position: relative;
    outline: 0;
    margin: 2px 24px 0 0;
    height: 23px;
    line-height: 23px;
  }
  #ls-groupon-logo>img{
    width: 125px;
    height: 20.46px; 
  }
  /* 下拉按钮 */
  .redesign-buttons{
    background: #348700;
    cursor: pointer;
    border-radius: 4px;
    font-size: 0.8rem;
    line-height: 1.8rem;
    position: relative;
    white-space: nowrap;
    padding: 5px 32px 5px 12px;
    margin: 0 24px 0 0;
    min-width: 61px;
    background-color: #348700;
    color: #fff;
    border-color: #348700;
  }
  .redesign-buttons>img{
    width: 12px;
    height: 12px;
        position: absolute;
    right: 12px;
    top: 50%;
    font-size: 8px;
    margin-top: -5px;
    font-weight: 600;
  }
  /* 搜素form表单 */
  .rch-bar-v2{
    position: relative;
    margin: 0 24px 0 0;
    display: flex;
    flex: 1 0;
    max-width: 700px;
  }
  .ls-search-wrapper{
    position: relative;
    margin: 0 24px 0 0;
    display: flex;
    flex: 1 0;
    max-width: 589px;
  }
  .icon-magnifying-glass{
    flex: 1 0;
    width: 100%;
    padding-left: 35px;
    border-radius: 4px;
    display: inline-block;
    vertical-align: middle;
    position: relative;
    z-index: 0;
    background: #fff;
    height: 35px;
    border: 0;
    padding: 0 0 0 30px;
    margin: 0 7px 0 0;
    font-weight: 400;
    width: 307px;
  }
  /* 放大镜图标 */
  .icon-magnifying-glass>img,.icon{
    position: absolute;
    font-size: 18px;
    top: 50%;
    left: 9px;
    width: 20px;
    height: 20px;
    margin: -9px 0 0;
    text-align: center;
  }
  /* 搜索框 */
  #ls-search{
    font-weight: 400;
    font-size: 14px;
    z-index: 2;
    margin: 0;
    padding: 0 10px 0 0;
    background: transparent;
    border: 0;
    height: 35px;
    width: 100%;
    box-sizing: border-box;
    position: relative;
    transition: none;
  }
  /* 定位框 */
  .search-box{
    border-radius: 4px;
    width: 171px;
    display: inline-block;
    vertical-align: middle;
    position: relative;
    z-index: 0;
    background: #fff;
    height: 35px;
    border: 0;
    padding: 0 0 0 30px;
    margin: 0 7px 0 0;
    font-weight: 400;
  }
  .search-box>input{
    font-weight: 400;
    font-size: 14px;
    z-index: 2;
    margin: 0;
    padding: 0 10px 0 0;
    background: transparent;
    border: 0;
    height: 35px;
    width: 100%;
    box-sizing: border-box;
    position: relative;
    transition: none;
  }
  /* 提交按钮 */
  .ls-header-search-button{
    background: #348700;
    border: 1px solid #348700;
    border-radius: 4px;
    height: 35px;
    width: 35px;
    min-width: 35px;
    text-align: center;
    padding: 0;
    font-size: 16px;
    vertical-align: middle;
    font-weight: 600;
  }
  .ls-header-search-button>img{
    height: 20px;
    line-height: 1.5;
  }
  /* 购物车 */
  .cart-link{
    margin: -2px 10px 0 0;
  }
  .cart-link>img{
    height: 29px;
    width: 34px;
    display: inline-block;
    margin-top: -2px;
  }
  /* 提示消息 */
  #mail{
    height: 31px;
    width: 28px;
    margin-top: 0px;
  }
  /* 登录按钮 */
  .sign-ln{
    min-width: 40px;
  }
  /* 商品导航 */
  .nav{
    background: #fff;
    border-bottom: 1px solid #d5d8db;
    padding: 0;
    margin: 0;
    z-index: 10;
    min-height: 46px;
  }
  .page-container{
    margin: 0 auto;
    max-width: 1080px;
    width: 100%;
  }
  .primary-nav{
    justify-content: flex-start;
    align-items: flex-start;
    display: flex;
    cursor: default;
    margin: 0;
    padding: 0;
    list-style: none;
    font-weight: 300;
    
  }
  .primary-nav-tab{
    margin-right: 32px;
    text-align: left;
  }
  .primary-nav-tab>a{
    line-height: 45px;
    margin: 0;
    padding: 0;
    display: inline-block;
    position: relative;
    z-index: 110;
    text-align: center;
    white-space: nowrap;
    cursor: pointer;
    font-size: 14px;
    font-weight: 400;
    color: #707174;
    font-size: 13px;
  }
  /* element ui 导航样式 */
  .el-dropdown-link {
    cursor: pointer;
    color: #707174;
    line-height: 45px;
    padding: 0;
    height: 45px;
  }
  .el-icon-arrow-down {
    font-size: 12px;
  }
</style>
