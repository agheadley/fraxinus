<script lang="ts">
	import '../../app.css';
	import {goto} from '$app/navigation';

	let { data,children } = $props();
	let { session, supabase } = $derived(data);


	const logout = async () => {
		goto('/auth/logout');
		/*
      const { error } = await supabase.auth.signOut()
      if (error) {
        console.error(error)
      } else {
        goto('/auth');
      }
		*/
      
    }

</script>

<div class="container">
	<header>
		<header>
			<p></p>
			<p><a class="brand" href={'/'}>Ailanthus</a></p>
			
		</header>
		<nav>
		<button onclick={logout}>Logout</button>
		</nav>
	</header>


	<main>
		{@render children()}
	</main>
	<footer>
		<p>
		</p>
	</footer>
</div>

<style>
    
.brand  {
	color:#0d47a1;
	font-size:2rem;
	font-weight:bold;
	text-decoration: none;
} 
</style>
