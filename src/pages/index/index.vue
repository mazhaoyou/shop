<template>
	<view>
    <swiper class="swiper" :indicator-dots="indicatorDots" :autoplay="autoplay" :circular="circular" :interval="interval" :duration="duration">
	<swiper-item>
		<view class="img-view">
		<image src="../../static/banner/banner_min_1.png"></image>
		</view>
	</swiper-item>
	<swiper-item>
		<view class="img-view">
		<image src="../../static/banner/banner_min_2.png"></image>
		</view>
	</swiper-item>
	<swiper-item>
		<view class="img-view">
		<image src="../../static/banner/banner_min_3.png" mode=""></image>
		</view>
	</swiper-item>
   </swiper>
	</view>
</template>

<script>
export default {
	data() {
		return {
			indicatorDots: true,
			autoplay: true,
			interval: 2000,
			duration: 500,
			circular: true
		};
	},
	onLoad() {},
	methods: {}
};
</script>


<style>
image,
swiper,
.img-view {
	width: 100%;
	height: 340upx;
}
</style>
