
<script lang="ts">
	import Icon from '@iconify/svelte';
</script>

<div class="container">	
	<div class="page">
		<img src="/photo.jpeg" alt="title"/>
		
		<div class="space"/>

		<div class="flex">
			<a href="https://www.etsy.com/shop/lazyfrogpond">
				<Icon icon="simple-icons:etsy" />
			</a>		
			
			<a href="https://instagram.com/lazyfrogpond?igshid=NTdlMDg3MTY=">
				<Icon icon="simple-icons:instagram" />
			</a>
		</div>
	</div>
</div>	

<style>
	img {
		width: 100vw;
	}
	
	.page {
		display: flex;
		flex-direction: column;
		align-items: center;
		
		min-height: 100vh;
		min-height: 100dvh;
		
		max-width: 50rem;
		padding: 1rem;
	}
	
	.flex {
		display: flex;
		justify-content: space-between;
		width: 5rem;
		
	}
	
	.space {
		flex-grow: 1;
	}	
	
	a {
		color: black;
		text-decoration: none;
	}
</style>