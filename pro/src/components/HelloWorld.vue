<template>
  <div class="hello">
    <section>
      <mt-swipe :auto="4000" style="height:200px; padding-left: 4.5%;">
        <mt-swipe-item style="background: red; width:96%;">1</mt-swipe-item>
        <mt-swipe-item style="background: yellow; width:96%;">2</mt-swipe-item>
        <mt-swipe-item style="background: pink; width:96%;">3</mt-swipe-item>
        <mt-swipe-item style="background: purple; width:96%;">4</mt-swipe-item>
		  </mt-swipe>
      <mt-search id="sou"></mt-search>
      <div id="c-p">
        <router-link to="/" tag="p">看公司</router-link>
        <router-link to="/" tag='p'>人脉</router-link>
        <router-link to='/' tag="p">面试</router-link>
        <router-link to='/' tag="p">问答</router-link>
      </div>
      
      <div id="introduce">
        <h1>推荐<span>换一批</span></h1>
        <div id="i-d">
          <div id="i-l">
            <span id="a">广东咏声文化传播有限公司</span>
            <span id="b">广州-影视/媒体</span>
            <span id="c">点评13　面经11　问答10</span>
            <router-link to="" tag="span" id="d">在影视/媒体行业排名111</router-link>
          </div>
          <img src="../assets/3.jpeg" alt="">
        </div>
      </div>
      <div id="introduce">
        <h1>推荐<span>换一批</span></h1>
        <div id="i-d">
          <div id="i-l">
            <span id="a">广东咏声文化传播有限公司</span>
            <span id="b">广州-影视/媒体</span>
            <span id="c">点评13　面经11　问答10</span>
            <router-link to="" tag="span" id="d">在影视/媒体行业排名111</router-link>
          </div>
          <img src="../assets/3.jpeg" alt="">
        </div>
      </div>

      <div id="tuijian">
        <h1>推荐</h1>
        <div id="t-d">
          <dl>
            <dt><img src="../assets/zhao.jpg" alt=""></dt>
            <dd>员工心中最靠谱的公司首选首选</dd>
            <dd>26207查看 50家公司</dd>
          </dl>
          <dl>
            <dt><img src="../assets/zhao.jpg" alt=""></dt>
            <dd>员工心中最靠谱的公司首选首选</dd>
            <dd>26207查看 50家公司</dd>
          </dl>
          <dl>
            <dt><img src="../assets/zhao.jpg" alt=""></dt>
            <dd>员工心中最靠谱的公司首选首选</dd>
            <dd>26207查看 50家公司</dd>
          </dl>
          <dl>
            <dt><img src="../assets/zhao.jpg" alt=""></dt>
            <dd>员工心中最靠谱的公司首选首选</dd>
            <dd>26207查看 50家公司</dd>
          </dl>
        </div>
        <div id="see">查看更多排行榜<span>&gt;</span></div>
      </div>

      <div class="zhuanti">
        <h2>企业专题</h2>
        <div id="z-d">
          <div id="z-l">
            <span id="aa">双十一还没到，这些电商公司已经躁动起来了</span>
            <span id="bb">26207查看 50家公司</span>
          </div>
          <img src="../assets/3.jpeg" alt="">
        </div>
        <div id="z-d">
          <div id="z-l">
            <span id="aa">双十一还没到，这些电商公司已经躁动起来了</span>
            <span id="bb">26207查看 50家公司</span>
          </div>
          <img src="../assets/3.jpeg" alt="">
        </div>
        <div id="z-d">
          <div id="z-l">
            <span id="aa">双十一还没到，这些电商公司已经躁动起来了</span>
            <span id="bb">26207查看 50家公司</span>
          </div>
          <img src="../assets/3.jpeg" alt="">
        </div>
        <div id="z-d">
          <div id="z-l">
            <span id="aa">双十一还没到，这些电商公司已经躁动起来了</span>
            <span id="bb">26207查看 50家公司</span>
          </div>
          <img src="../assets/3.jpeg" alt="">
        </div>
        <div id="see1">查看全部专题<span>&gt;</span></div>
      </div>
    </section> 
    <footer>
        <router-link to="/home" tag="span">首页</router-link>
        <router-link to="/bird" tag='span'>老鸟</router-link>
        <router-link to='/message' tag="span">消息</router-link>
        <router-link to='/my' tag="span">我的</router-link>
    </footer> 
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
     
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* .router-link-active{
		background: #dfdfdf;
	} */
.zhuanti{
  height: 475px;
  background: #fbfbfb;
} 
  .zhuanti h2{
    height: 25px;
    font-size: 12px;
    padding: 0 20px;
    line-height: 25px;
  }
  #z-d{
    height: 80px;
    display: flex;
    justify-content: space-between;
    padding: 10px 20px 10px 20px;
    border-bottom: 2px solid #d9d9d9;
  }
  #z-d img{
    width: 84px;
    height: 60px;
  }
  #z-d span{
    display: block;
    width: 150px;
    font-size: 10px;
  }
  #z-l{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  #see1{
    display: flex;
    justify-content: space-between;
    padding: 0 20px;
    font-size: 10px;
    margin-top: 10px;
    color: #757982;
  }
.hello{
		height: 100vh;
		display: flex;
		flex-direction: column;
	}
  
  section{flex: 1; overflow: auto;}
  footer{
    height: 60px;
    background: palegreen;
    display: flex;
    align-items: center;
    justify-content: space-around;
    flex-shrink: 0;
  }
  footer span{
    display: block;
    width: 40px;
    height: 40px;
    background: #f2f2f2;
    text-align: center;
    line-height: 40px;
    border-radius: 50%;
    font-size: 12px;

  }
  #introduce{
    height: 120px;
    background: #f4f4f4;
    margin-bottom: 10px;

  }
  #introduce h1{
    height: 42px;
    display: flex;
    justify-content: space-between;
    font-size: 16px;
    align-items: center;
    padding: 0 10px;
  }
#introduce h1 span{
  font-size: 10px;
  color: #afafaf;
}
#i-d{
  display: flex;
  justify-content: space-between;
  padding: 0 10px;
}
#i-d img{
  width: 68px;
  height: 56px;
}
#i-l{
  width: 60%;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}
#i-l h3{
  font-size: 18px;
  color: #d0d0d0;
  width: 150px;
  height: 14px;
}
#i-l span{
  font-size: 10px;
  line-height: 18px;
}
#d{
  border: 1px solid #e0e0e0;
  background: none;
  width: 160px;
}
#a{color: #666;}
#b,#c,#d{
  color: #acacac;
}
#c-p{
  height: 66px;
  display: flex;
  justify-content: space-around;
  flex-direction: row;
  align-items: center
}
#c-p p{
  width: 37px;
  height: 37px;
  background: #dddddd;
  border-radius: 50%;
  line-height: 37px;
  text-align: center; 
  color: #757575;
  font-size: 12px
}
#sou{
  height:52px;
}
#tuijian{
  height: 310px;
  background: #f4f4f4;
  margin-bottom: 10px;
}
#tuijian h1{
  height: 38px;
  font-size: 12px;
  line-height: 38px;
  padding-left: 10px; 
}
#t-d{display: flex; justify-content: space-around;flex-direction: row; flex-wrap: wrap}
#t-d dl{
  margin: 0 10px 15px 10px;
}
#t-d img{
  width: 130px;
  height: 75px;
}
#t-d dd{
  width: 130px;
}
#t-d dd:nth-of-type(1){
  font-size: 10px;
  text-indent: 2em;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
#t-d dd:nth-of-type(2){
  font-size: 0.08rem;
}
#see{
  display: flex;
  justify-content: space-between;
  padding: 0 20px;
  font-size: 10px;
}
</style>
