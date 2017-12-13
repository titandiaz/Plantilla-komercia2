<template>
  <nav class="menu-nav">
		<div class="container-menu-nav">
			<ul class="main-menu">
				<li v-for="item in items" class="main-menu__item">
					<a href="#" class="main-menu__link">{{item.item}}</a>
				</li>
			</ul>
		</div>	
  </nav>
</template>

<script>
export default {
  name: 'Menu',
    data () {
      return {
      	items: [
					{item: 'Inicio'},
					{item: 'Nosotros'},
					{item: 'Galeria'},
					{item: 'Contacto'}
					]
    }
  }
}
</script>
	
<style scoped>
	.menu-nav {
		display: flex;
		justify-content: center;
	}
	.main-menu {
		width: 800px;
		height: 60px;
		font-weight: 500;
		display: flex;
		justify-content: space-around;
		text-transform: uppercase;
	}
	.main-menu__item {
		list-style: none;
		letter-spacing: .7px;
		font-size: 15px;
		display: flex;
		align-items: center;
	}
	.main-menu__link {
		text-decoration: none;
		color: #000;
		padding-bottom: 10px;
	}
	.main-menu__link:hover {
		border-bottom: solid 1px gainsboro;
	}
</style>
