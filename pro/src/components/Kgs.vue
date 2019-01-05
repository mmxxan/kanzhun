<template>
  <div class="kgs">
    <header>
      <div>
        <span>&lt;</span>
        <span>看公司</span>
        <span>搜索</span>
      </div>   
    </header>
    <section>
        <div class="kgs-i">
            <img src="../assets/3.jpeg" alt="">
            <div id="g-r">
                <h4>贞元集团<span>5.0分</span><span>+关注</span></h4>
                <p>安阳|房地产开发|1000-9999人</p>
                <p>30条信息</p>
            </div>
        </div>
        <div class="kgs-i">
            <img src="../assets/3.jpeg" alt="">
            <div id="g-r">
                <h4>贞元集团<span>5.0分</span><span>+关注</span></h4>
                <p>安阳|房地产开发|1000-9999人</p>
                <p>30条信息</p>
            </div>
        </div>
        <div class="kgs-i">
            <img src="../assets/3.jpeg" alt="">
            <div id="g-r">
                <h4>贞元集团<span>5.0分</span><span>+关注</span></h4>
                <p>安阳|房地产开发|1000-9999人</p>
                <p>30条信息</p>
            </div>
        </div>
        <div class="kgs-i">
            <img src="../assets/3.jpeg" alt="">
            <div id="g-r">
                <h4>贞元集团<span>5.0分</span><span>+关注</span></h4>
                <p>安阳|房地产开发|1000-9999人</p>
                <p>30条信息</p>
            </div>
        </div>
        <div class="kgs-i">
            <img src="../assets/3.jpeg" alt="">
            <div id="g-r">
                <h4>贞元集团<span>5.0分</span><span>+关注</span></h4>
                <p>安阳|房地产开发|1000-9999人</p>
                <p>30条信息</p>
            </div>
        </div>
        <div class="kgs-i">
            <img src="../assets/3.jpeg" alt="">
            <div id="g-r">
                <h4>贞元集团<span>5.0分</span><span>+关注</span></h4>
                <p>安阳|房地产开发|1000-9999人</p>
                <p>30条信息</p>
            </div>
        </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Kgs",
  data() {
    return {};
  }
};
</script>

<style>
.kgs {
  height: 100vh;
  display: flex;
  flex-direction: column;
}
header {
  height: 100px;
  background: pink;
  flex-shrink: 0;
  border-bottom: 2px solid #dcdcdc;
}
header span:first-child {
  margin-left: 2vh;
  margin-right: 18vh;
}
header span:nth-child(2) {
  margin-right: 18vh;
}
section{
    flex: 1;
    overflow: auto;
}
.kgs-i{
    height: 128px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-left: 2vh;
    border-bottom: 2px solid #cacaca;
}
.kgs-i img{
    width: 12vh;
    height: 60px;
}
#g-r{
    width: 60vh;
    padding-left: 2vh;
}
#g-r span:nth-of-type(1),#g-r span:nth-of-type(2){
    display: block;
    width: 66px;
    height: 26px;
    border: 1px solid #bfbfbf;
    border-radius: 20px;
    text-align: center;
    line-height: 26px;
    font-size: 10px;
    color: #a8aeb6;
}
#g-r span:nth-of-type(1){
     margin-left: 1.5vh;
}
#g-r span:nth-of-type(2){
    margin-left: 7vh;
}
#g-r h4{
    font-size: 16px;
    display: flex;
    flex-direction: row;
    color: #757586;
}
#g-r p{
    font-size: 12px;
    color: #a8aeb6;
}
</style>


