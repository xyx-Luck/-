<template>
	<view class="musichead">
		<view class="musicIcon" v-if="showIcon" showIcon>
			<text class="iconfont icon-zuojiantou" @click="back"></text> |  <text class="iconfont icon-shouye" @click="backHome"></text>
		</view>
		<view class="musicTitle">{{title}}</view>
	</view>
</template>

<script>
	export default {
		props:{
			title:{
				type:String,
				default:''
			},
			showIcon:{
				type:Boolean,
				default:false
			}
		},
		data() {
			return {
				
			}
		},
		methods: {
			back(){
				uni.navigateTo();
			},
			backHome(){
				uni.navigateTo({
					url: '/pages/index/index'
				});
			}
		}
	}
</script>

<style scoped>
.musichead{
	 width:100%;
	 height:75px;
	 line-height:80px;
	 /* background:rgba(0,0,255,.4); */
	
	 position:relative;
}
.musicTitle{
	text-align:center;
	 color:#000;
}
.musicIcon{
	position: absolute;
	top:23px;
	left:15px;
	padding:0px 15px;
	height:30px;
	line-height:30px;
	background:#b6b3b4;
	border-radius: 15px;
	color:#fff;
}
</style>
