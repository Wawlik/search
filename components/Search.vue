<template>
	<div class="Search">
			<input type="text" @keyup.13="search()"class="Search__input" v-model="query" placeholder="Type to search in Wikipedia" />
		<button class="Search_button" @click="search()">Найти</button>
	</div>
</template>

<script>
	export default {
		name: 'search',
		data() {
			return {
				query: ''
			}
		},
		methods: {
			search()
{
	this.$store.dispatch('search', this.query)
}		}
	}
</script>