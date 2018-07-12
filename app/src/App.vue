<template>
	<div id="app">
		<div class="weui-tab">
			<!--  <div class="weui-navbar">
    <div class="weui-navbar__item weui-bar__item--on">
      选项一
    </div>
    <div class="weui-navbar__item">
      选项二
    </div>
    <div class="weui-navbar__item">
      选项三
    </div>
  </div>-->
  dsasdsds
			<div class="weui-tab__bd">

				<input type="text" id="a">

			</div>

			<div class="weui-tabbar">
				<a href="javascript:;" class="weui-tabbar__item weui-bar__item--on">
					<span class="weui-badge" style="position: absolute;top: -.4em;right: 1em;">8</span>
					<div class="weui-tabbar__icon">
						&#xe618;
					</div>
					<p class="weui-tabbar__label">微信&#xe618;</p>
				</a>
				<a href="javascript:;" class="weui-tabbar__item">
					<div class="weui-tabbar__icon">
						<!-- <img src="./images/icon_nav_msg.png" alt="">-->
					</div>
					<p class="weui-tabbar__label">通讯录</p>
				</a>
				<a href="javascript:;" class="weui-tabbar__item">
					<div class="weui-tabbar__icon">
						<!-- <img src="./images/icon_nav_article.png" alt="">-->
					</div>
					<p class="weui-tabbar__label">发现</p>
				</a>
				<a href="javascript:;" class="weui-tabbar__item">
					<div class="weui-tabbar__icon">
						<!-- <img src="./images/icon_nav_cell.png" alt="">-->
					</div>
					<p class="weui-tabbar__label">我</p>
				</a>
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
	#app {
		font-family: 'Avenir', Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
		position: absolute;
    bottom: 0;
    width: 100%;
	}
	
	@font-face {
		font-family: 'fonts';
		src: url("assets/font/iconfont.eot");
		src: url("assets/font/iconfont.ttf");
		src: url("assets/font/iconfont.woff");
	}
	.weui-tabbar__label{
		font-family: 'fonts';
	}
</style>