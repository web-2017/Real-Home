<template>
	<div class="home">
		<Carusel />
	</div>
</template>

<script>
	// @ is an alias to /src
	import Carusel from '../components/Carusel'

	export default {
		name: 'Home',
		components: {
			Carusel,
		},
	}
</script>
