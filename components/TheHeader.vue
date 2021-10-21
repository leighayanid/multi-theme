<template>
	<div>
		<div class="py-10">
			<div class="flex">
				<div class="flex space-x-6">
					<nuxt-link
						to="/"
						class="btn btn-primary btn-ghost btn-sm rounded-btn flex-1"
					>
						Home
					</nuxt-link>
					<nuxt-link
						to="/about"
						class="btn btn-primary btn-ghost btn-sm rounded-btn"
					>
						About
					</nuxt-link>
					<select-theme></select-theme>
				</div>
			</div>
		</div>
	</div>
</template>

<style scoped>
.nuxt-link-exact-active {
  @apply bg-yellow-500 text-black;
}
</style>
