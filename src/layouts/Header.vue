<script setup>
import logo from "@/assets/logo.png";
</script>

<template>
	<header class="header">
		<div class="logo">
			<router-link to="/">
				<img :src="logo" alt="logo" class="logo-img" />
			</router-link>
		</div>
		<nav class="menu">
			<ul>
				<li>
					<a class="black-text" href="#">LOGIN</a>
				</li>
				<li>
					<a class="black-text" href="#">CART</a>
				</li>
				<li>
					<a class="black-text" href="#">Q&A</a>
				</li>
				<li>
					<img src="@/assets/search.png" alt="통합검색" class="search-btn" />
				</li>
			</ul>
		</nav>
	</header>
</template>

<style scoped>
.header {
	position: sticky;
	top: 0;
	left: 0;
	width: 100%;
	display: flex;
	justify-content: space-between;
	align-items: center;
	height: 60px;
	padding: 0 20px;
	background-color: transparent;
	box-sizing: border-box;
	z-index: 1000;
}

.logo-img {
	width: 60px;
	height: auto;
}

.menu ul {
	display: flex;
	gap: 24px;
	list-style: none;
	margin: 0;
	padding: 0;
}

.menu a {
	text-decoration: none;
	color: #333;
}

.menu a:hover {
	color: #535bf2;
}

.search-btn {
	width: 20px;
	height: 20px;
	object-fit: contain;
}
</style>
