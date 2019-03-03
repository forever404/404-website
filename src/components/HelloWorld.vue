<template>
  <div class="hello">
    <div>
    <h1>{{ msg }}</h1>
    <div style="margin-bottom:50px;"></div>
      <div class="container">
        <div id="demo" class="carousel slide" data-ride="carousel">
          <!-- 指示符 -->
          <ul class="carousel-indicators">
            <li data-target="#demo" data-slide-to="0" class="active"></li>
            <li data-target="#demo" data-slide-to="1"></li>
            <li data-target="#demo" data-slide-to="2"></li>
          </ul>
          <!-- 轮播图片-->
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="http://static.runoob.com/images/mix/img_fjords_wide.jpg">
            </div>
            <div class="carousel-item">
              <img src="http://static.runoob.com/images/mix/img_nature_wide.jpg">
            </div>
            <div class="carousel-item">
              <img src="http://static.runoob.com/images/mix/img_mountains_wide.jpg">
            </div>
          </div>
          <!--左右切换按钮-->
          <a class="carousel-control-prev" href="#demo" data-slide="prev">
            <span class="carousel-control-prev-icon"></span>
          </a>
          <a class="carousel-control-next" href="#demo" data-slide="next">
            <span class="carousel-control-next-icon"></span>
          </a>
        </div>
      </div>
    </div>
    <div style="margin-top:120px"></div>
<div style="">
  <blog style="display:inline-block"></blog>
 <div style="display:inline-block;width:20px;height:260px;"></div>
<blog style="display:inline-block"></blog>
 <div style="display:inline-block;width:20px;height:260px;"></div>
<blog style="display:inline-block"></blog>
 <div style="display:inline-block;width:20px;height:260px;"></div>

</div>
<div style="margin-top:120px"></div>


    <h2>Essential Links</h2>
    <ul>
 
      <li>
        <a href="https://forum.vuejs.org" target="_blank">Forum</a>
      </li>
      <li>
        <a href="https://chat.vuejs.org" target="_blank">Community Chat</a>
      </li>
      <li>
        <a href="https://twitter.com/vuejs" target="_blank">Twitter</a>
      </li>
      <br>

    </ul>
  </div>
</template>

<script>
import blog from "./Blog.vue";
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Hack not only for function but for fun"
    };
  },
  components:{
    blog
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
  font-family: 'Franklin Gothic Medium';
  color:rgb(99, 91, 111);
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.blog {
  display: inline-block;
}
</style>
