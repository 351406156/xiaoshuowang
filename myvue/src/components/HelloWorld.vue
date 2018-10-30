<template>
  <div class="hello">
   <div class="dhl">
<img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1540814399485&di=51bea46bbd9e6e4c628c81ffa6ffdfbc&imgtype=0&src=http%3A%2F%2Fimg.aso.aizhan.com%2Ficon%2F8f%2F32%2F9e%2F8f329e7be7624f5d7b155493c16ceaa7.jpg" alt="">
    
    <div class="xsw">小说网</div>
    <div class="ssk">
      <input class="ssl" type="text">
    </div>

     <div class="ssk1">
       <img id="img2" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1540819038760&di=f9da10be0e1e3a9506dbd13f877378b6&imgtype=0&src=http%3A%2F%2Fimage.tupian114.com%2F20140424%2F13472458.png" alt="">
     </div>
     <div class="wdsj">我的书架1</div>
      <div class="grzx">个人中心</div>
   </div>

   <div class="flh">
      <div class="ns1">男生</div>
      <div class="ns2">女生</div>
      <div class="xh">玄幻</div>
       <div class="yq">言情</div>
        <div class="gd">古代</div>
        <div class="xd">现代</div>
         <div class="cy">穿越</div>
        
   </div>
  
  </div>
</template>

<script>
import Luobo from './Luobo';
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.dhl{
  width: 100%;
  height: 80px;
  background-color:white;
  position: relative;
}

.dhl img{
  width: 60px;
  height: 60px;
  position: absolute;
  top: 9px;
  left: 147px;
}

.dhl .ssk{
 width: 244px;
    height: 34px;
  position: absolute;
  top: 20px;
  left: 485px;
      border: 2px solid #4fb53d;
    border-right: none;
    border-radius: 100px 0 0 100px;
  
}
.dhl .ssk1{
 width: 46px;
    height: 34px;
  position: absolute;
  top: 20px;
  left: 730px;
      border: 2px solid #4fb53d;
        border-left: none;
    border-radius: 0 100px 100px 0;
  
}
.ssl{
  width: 200px;
  height: 30px;
  outline: none;
   outline-color: white;
       border: none;
  position: absolute;
  top: 0px;
  left: 16px;
}

#img2{
  width: 32px;
  height: 32px;
   position: absolute;
  top: 0px;
  left: -2px;
}

.wdsj{
  color: #4fb53d;
      font-size: 16px;
      font-weight: 300;
      line-height: 80px;
      display: inline-block;
       position: absolute;
       left: 900px;
    
}
.xsw{
  color: #08b6eb;
  font-size: 28px;
      font-weight: 800;
      line-height: 80px;
      display: inline-block;
       position: absolute;
       left: 215px;
}
.grzx{
  color: #4fb53d;
      font-size: 16px;
      font-weight: 300;
      line-height: 80px;
      display: inline-block;
       position: absolute;
       left: 1000px;
    
}

.flh{
  width: 100%;
  height: 50px;
  background-color: #4fb53d;
  position: relative;
}

.flh .ns1{
  font-size: 16px;
    line-height: 50px;
    display: inline-block;
    color: #fff;
    position:absolute;
    left: 330px;
}

.flh .ns2{
  font-size: 16px;
    line-height: 50px;
    display: inline-block;
    color: #fff;
    position:absolute;
    left: 430px;
}

.flh .xh{
  font-size: 16px;
    line-height: 50px;
    display: inline-block;
    color: #fff;
    position:absolute;
    left: 530px;
}

.flh .yq{
  font-size: 16px;
    line-height: 50px;
    display: inline-block;
    color: #fff;
    position:absolute;
    left: 630px;
}
.flh .gd{
  font-size: 16px;
    line-height: 50px;
    display: inline-block;
    color: #fff;
    position:absolute;
    left: 730px;
}
.flh .xd{
  font-size: 16px;
    line-height: 50px;
    display: inline-block;
    color: #fff;
    position:absolute;
    left: 830px;
}

.flh .cy{
  font-size: 16px;
    line-height: 50px;
    display: inline-block;
    color: #fff;
    position:absolute;
    left: 930px;
}
</style>
