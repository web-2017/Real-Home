<template>
	<div class="home">
		<Carusel />
		<MainContainer></MainContainer>
	</div>
</template>

<script>
	// @ is an alias to /src
	import MainContainer from '../components/MainContainer'
	import Carusel from '../components/Carusel'

	export default {
		name: 'Home',
		components: {
			MainContainer,
			Carusel,
		},
	}
</script>
