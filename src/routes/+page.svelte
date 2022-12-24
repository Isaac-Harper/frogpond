<script lang="ts">
	import Icon from '@iconify/svelte';
</script>



<img src="/photo.jpeg" alt="title"/>




<div class="flex">
	<a href="https://www.etsy.com/shop/lazyfrogpond">
		<Icon icon="simple-icons:etsy" />
	</a>	
	
	<a href="https://instagram.com/lazyfrogpond?igshid=NTdlMDg3MTY=">
		<Icon icon="simple-icons:instagram" />
	</a>
</div>


<style>
	img {
		width: 100vw;
	}
	
	.flex {
		display: flex;
		justify-content: space-between;
		width: 5rem;
		
	}
	
	a {
		color: black;
		text-decoration: none;
	}
</style>