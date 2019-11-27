<template>
  <div id="app">
    <div class="header">
      <div class="header-left">
          <div class="iconfont">&#xe610;</div>
      </div>
      <div class="header-input">
        <span class="iconfont">&#xe647;</span> 输入城市/景点/游玩主题
      </div>
      <div class="header-righe">城市
      <span class="iconfont">&#xe736;</span>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
body{
  margin: 0;
  padding: 0;
}
.header{
  background:#00afc7;
  display:flex;
  line-height:2rem;
  font-size: .2rem;
}
.header-left{
  float: left;
  color:#fff;
  line-height: 3rem;
  margin-left: 1rem;
  margin-right: 0.5rem;
}
.header-input{
  color:#ccc;
  flex:1;
  background:#fff;
  margin:0.5rem ; 
  border-radius:.2rem;

}
.header-righe{
  margin: 0.5rem 0.5rem 0.5rem 0rem;
  color: #fff;
}

</style>