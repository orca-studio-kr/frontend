<template>
	<footer class="footer">
		<div class="left black-text">© 2025. ORCA STUDIO All rights reserved.</div>

		<div class="right">
			<a href="#">
				<img src="@/assets/kakao.svg" alt="카톡 문의" class="kakao-btn" />
			</a>
		</div>
	</footer>
</template>

<script setup></script>

<style scoped>
.footer {
	width: 100%;
	height: 50px;
	display: flex;
	justify-content: space-between;
	align-items: center;
	padding: 0 20px;
	background-color: white;
	box-sizing: border-box;
}

.left {
	color: black;
}

.kakao-btn {
	width: 30px;
	height: 30px;
	object-fit: contain;
}
</style>
