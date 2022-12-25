
<script lang="ts">
	import Icon from '@iconify/svelte';
</script>

<div class="container">	
	<div class="page">
		<img class="title" src="/photo.jpeg" alt="title"/>
		
		<p>Cute things made here</p>
		
		<div class="space"/>
		
		<img class="item" src="/froggies.jpg" alt="froggies"/>
		<img class="item" src="/arson.jpg" alt="arson"/>
		<img class="item" src="/bowl.jpg" alt="bowl"/>

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
	.title {
		width: 100vw;
	}
	
	.container {
		display: flex;
		justify-content: center;
	}	
	
	.item {
		width: 100%;
		border: 4px solid #54B101;	
		border-radius: 1rem;
		overflow: hidden;
	}
	
	.page {
		display: flex;
		flex-direction: column;
		align-items: center;
		gap: 1rem;
		
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