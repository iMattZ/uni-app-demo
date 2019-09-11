<template>
	
	<view>
	<!-- 	<view class="view-box animated " hover-class="view-box-hover rubberBand" hover-stay-time="800">
			这个一个view
		</view> -->
		
		
		<view class="uni-padding-wrap uni-common-mt">
			
			<view class="uni-title uni-common-mt">
				flex-direction: row
				<text>\n横向布局</text>
			</view>
			
			<view class="uni-flex uni-row">
				<view class="uni-flex-item uni-bg-blue">A</view>
				<view class="uni-flex-item uni-bg-red">B</view>
				<view class="uni-flex-item uni-bg-green">C</view>
			</view>
			
			<view class="uni-title uni-common-mt">
				flex-direction: column
				<text>\n纵向布局</text>
			</view>
			
			<view class="uni-flex uni-column">
				<view class="uni-flex rowHeight uni-bg-blue">A</view>
				<view class="uni-flex rowHeight uni-bg-red">B</view>
				<view class="uni-flex rowHeight uni-bg-green">C</view>
			</view>
			
			
		</view>
		
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
.view-box {
	width: 200upx;
	height: 200upx;
	background-color: #007AFF;
	margin: 100px;
}
.view-box-hover {
	background-color: red;
}

.uni-row {
	height: 100upx;
	text-align: center;
}

.rowHeight {
	height: 100upx;
	text-align: center;
	line-height: center;
}

</style>
