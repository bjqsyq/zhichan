<template>
	<view>
		<view>
			<image src="../../static/logo.png" mode=""></image>
		</view>
		<view>
			<button type="primary" size="mini" @tap="test">TEST</button>
		</view>
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			test(){
				console.log("this is a test!")
			}
		}
	}
</script>

<style>

</style>
