<template>
	<view class="content">
		<musicHead :title="title" :showIcon="showIcon"></musicHead>
		<view class="indexContent">
			<scroll-view scroll-y='true'>
				<!-- 搜索 -->
				<view class="indexSearch">
					<text class="iconfont icon-fangdajing"></text>
					<input type="text" placeholder="搜索歌曲">
				</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
				<view>ssssssssss</view>
			</scroll-view>
		</view>
	</view>
</template>

<script>
	import '@/common/iconfont.css'
	import musicHead from '../../component/musicHeade/musicHeade.vue'
	export default {
		components:{musicHead},
		data() {
			return {
				title: '网易云音乐',
				showIcon:false
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
	.indexContent{
		width:100%;
		height:calc(100vh - 75px);
		overflow: scroll;
	}
	.indexSearch{
		margin:0 30upx;
		background:#F7F7F7;
		height:60upx;
		line-height:60upx;
		border-radius: 30upx;
		display:flex;
		padding-left:10px;
	}
	.indexSearch>text{
		width:30upx;
		height:30upx;
	}
	.indexSearch>input{
		height:60upx;
		line-height:60upx;
		margin-left:8px;
	}
</style>
