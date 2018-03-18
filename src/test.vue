<template>
	<ul>
		<li v-for="fruit in fruits">{{ fruit }}</li>
	</ul>
</template>

<script>
	export default{
		data(){
			return{
				fruits: ['apple', 'banana', 'melon', 'more']
			}
		}
	}
</script>

<style>
	
</style>