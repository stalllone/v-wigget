<template>
	<div id="app">
		<img alt="Vue logo" src="./assets/logo.png">
		<Demo />
		<m-card imgSrc='card1.jpeg' summary='vue2.5入门 '>
			<!-- <template v-slot:footer>
				<div class="footer">
					<div class="footer-top">进阶 · 141004人报名</div>
					<div class="footer-bottom">
						<div>免费</div>
						<div>收藏</div>
					</div>
				</div>
			</template> -->
		</m-card>
		<m-card imgSrc='card2.jpeg'>
			快速入门Web阅读器开发
			<template v-slot:footer>
				<div class="footer">
					<div class="footer-top">进阶 · 25206人报名</div>
					<div class="footer-bottom">
						<div>免费</div>
						<div>收藏</div>
					</div>
				</div>
			</template>
		</m-card>
		<m-card imgSrc='card3.jpeg' summary='0到1快速构建自己的后台管理系统 '>
			<template v-slot:footer>
				<div class="footer">
					<div class="footer-top">零基础 · 17718人报名</div>
					<div class="footer-bottom">
						<div>免费</div>
						<div>收藏</div>
					</div>
				</div>
			</template>
		</m-card>
		<m-card imgSrc='card4.png' :width="368" :imgHeight="90" summary='路线专为想学Vue却无从下手的人群设计，以实际项目为例，逐层深入，学透Vue。 '>
			<template v-slot:footer>
				<div class="footer">
					<!-- <div class="footer-top">零基础 · 17718人报名</div> -->
					<div class="footer-bottom">
						<div>· 4步骤 · 5门课</div>
						<div>19999人收藏</div>
					</div>
				</div>
			</template>
		</m-card>
	</div>
</template>

<script>

export default {
	name: 'App'
}
</script>

<style lang="scss">
.footer {
	padding: 0 8px;
	font-size: 12px;
	color: #9199a1;

	&-top {
		line-height: 18px;
		margin-bottom: 8px;
	}

	&-bottom {
		display: flex;
		justify-content: space-between;
	}
}
</style>
