<template>
	<view class="content">
		<u-search placeholder="日照香炉生紫烟" v-model="keyword"></u-search>		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello',
				keyword: ''
			}
		},
		onLoad() {
			console.log(uni.$u.config.v);
		},
		methods: {

		}
	}
</script>

<style >
	
	
</style>
