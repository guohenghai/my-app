<!--
 * @Author       : 郭恒海
 * @Date         : 2024-01-15 16:13:19
 * @LastEditors  : 郭恒海
 * @LastEditTime : 2024-01-16 14:15:39
 * @FilePath     : /my-app/src/App.vue
 * @Description  : 
 * guohenghai@126.com
-->
<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Greet from "./components/Greet.vue";
</script>

<template>
	<div class="container">
		<h1>Welcome!</h1>

		<div class="row">
			<a href="https://vitejs.dev" target="_blank">
				<img src="/vite.svg" class="logo vite" alt="Vite logo" />
			</a>
			<a href="https://vuejs.org/" target="_blank">
				<img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
			</a>
		</div>
		<p>
			Recommended IDE setup:
			<a href="https://code.visualstudio.com/" target="_blank">VS Code</a>
			+
			<a href="https://github.com/johnsoncodehk/volar" target="_blank">Volar</a>
			+
			<a href="https://github.com/rust-lang/rust-analyzer" target="_blank">rust-analyzer</a>
		</p>

		<Greet />
	</div>
</template>

<style scoped>
.logo.vite:hover {
	filter: drop-shadow(0 0 2em #747bff);
}

.logo.vue:hover {
	filter: drop-shadow(0 0 2em #249b73);
}
</style>
