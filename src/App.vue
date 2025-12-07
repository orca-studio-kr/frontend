<template>
	<div class="layout">
		<Header />
		<main class="content">
			<router-view />
		</main>
		<Footer />
	</div>
</template>

<script setup>
import Footer from "./layouts/Footer.vue";
import Header from "./layouts/Header.vue";
</script>

<style scoped>
.layout {
	display: flex;
	flex-direction: column;
	min-height: 100vh;
}

.content {
	flex: 1;
	padding: 16px;
	display: flex;
	align-items: center;
	justify-content: center;
}
</style>
