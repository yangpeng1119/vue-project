<template>
  <div>
  	<div class="header">
  		<div class="header-left"><</div>
  		<div class="header-center">输入城市/景点/游玩主题</div>
  		<div class="header-right">北京<span></span></div>
  	</div>

  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'header'
    }
  }
}
</script>

<style scoped>
	.header{
		display:flex;
		box-sizing: border-box;
		height:.88rem;
		width:100%;
		background:#00bcd4;
	}
	.header-left{
		float:left;
		width: .4rem;
	    line-height: .88rem;
	    padding: 0 .2rem;
	    color: #fff;
	    font-size: .36rem;
	    text-align: left;
	}
	.header-center{
		box-sizing: border-box;
		float:left;
		height: .6rem;
		flex:1;
	    margin: .14rem 0;
	    background: #fff;
	    line-height: .6rem; 
	    float:left;
	    padding:0 .2rem;
	    border-radius: .1rem;
	}
	.header-right{
		float:right ;
		line-height: .88rem;
		color:#fff;
		margin:0 .3rem;
	}
	.header-right span{
		float:right;
		margin-top:.3rem;
		margin-left:.1rem;
		display:block;
		width: 0;
	    height: 0;
	    border-left: .15rem solid transparent;
	    border-right: .15rem solid transparent;
	    border-top: .25rem solid #fff;
	}
</style>