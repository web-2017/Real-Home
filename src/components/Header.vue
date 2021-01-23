<template>
	<nav class="navbar navbar-expand-lg navbar-light bg-light">
		<div class="container">
			<a class="navbar-brand" href="#">Navbar</a>
			<div class="collapse navbar-collapse" id="navbarSupportedContent">
				<ul class="navbar-nav me-auto mb-2 mb-lg-0">
					<li class="nav-item" v-for="(menu, index) in headerMenuList" :key="index">
						<router-link class="nav-link active" aria-current="page" :to="menu.path">
							{{ menu.name }}
						</router-link>
					</li>
				</ul>
				<div>
					<a href="#"><img src="../assets/images/icons/f.png" alt="" /></a>
					<a href="#"><img src="../assets/images/icons/p.png" alt="" /></a>
					<a href="#"><img src="../assets/images/icons/insta.png" alt="" /></a>
					<a href="#"><img src="../assets/images/icons/g+.png" alt="" /></a>
				</div>
			</div>
		</div>
	</nav>
</template>

<script>
	export default {
		name: 'HelloWorld',
		props: {
			msg: String,
		},
		data() {
			return {
				headerMenuList: [
					{ name: 'home', path: '/' },
					{ name: 'About Us', path: '/about' },
					{ name: 'Property', path: '/property' },
					{ name: 'Our Blog', path: '/blog' },
					{ name: 'Contacts', path: '/contacts' },
				],
			}
		},
	}
</script>
