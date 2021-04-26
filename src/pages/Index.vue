<template>
    <div class="container">
        <userInfo class="left-box"></userInfo>
        <experience class="right-box"></experience>
    </div>

</template>

<script>
import userInfo from '../components/userInfo'
import experience from '../components/experience'

export default({
  name: 'Index',
  data () {
    return {

    }
  },
  components: {
    'userInfo': userInfo,
    'experience': experience
  }
})
</script>

<style>
@import url('https://at.alicdn.com/t/font_2482271_6rmru0awo2l.css');
html,body{
    width: 100%;
    height: 100%;
    margin: 0;
    padding: 0;
    background-color: #ebebeb;
  }
  #app{
    width: 80%;
    margin: 0px auto;
    box-sizing: border-box;
    background-color: #ebebeb;
  }
  .container{
    position: relative;
    width: 100%;
    height: auto;
    margin: 10px auto;
    /* box-sizing: border-box; */
    box-shadow: 0 0 3px 0 #999;
    background-color: #ebebeb;
  }
  .left-box{
    position: absolute;
    width: 350px;
    height: 100%;
    top: 0;
    bottom: 0;
    background-color: #394A5A;
    color: white;
    box-sizing: border-box;
    border-top-left-radius: 5px;
    border-bottom-left-radius: 5px;
  }
  .right-box{
    width: 100%;
    height: auto;
    padding:0px 30px 0px 400px;
    box-sizing: border-box;
    background-color: white;
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
  }

@media screen and (min-width:961px) {
    .container{
      width: 100%;
    }
}

@media screen and (max-width:960px) and (min-width:820px) {
    .container{
      box-shadow: none;
      width: 100%;
    }
}

@media screen and (max-width:819px) {
    .container{
      width: 100%;
      box-shadow: none;
    }
    .left-box{
      position: relative;
      width: 100%;
      border-top-left-radius: 5px;
      border-top-right-radius: 5px;
      border-bottom-left-radius: 0px;
    }
    .right-box{
      width: 100%;
      padding: 30px;
      border-bottom-left-radius: 5px;
      border-bottom-right-radius: 5px;
      border-top-right-radius: 0px;
    }
}
</style>
