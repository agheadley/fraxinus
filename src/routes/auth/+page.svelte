<script lang="ts">
import '../../app.css';
</script>


<div class="container">
    <header>
        <p></p>
		<p><a class="brand" href={'/'}>Ailanthus</a></p>
		
    </header>
    <p class="notice">Please sign in to use Ailanthus</p>



<form method="POST" action="?/login">
    <button >
      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 21 21"><title>MS-SymbolLockup</title><rect x="1" y="1" width="9" height="9" fill="#f25022"/><rect x="1" y="11" width="9" height="9" fill="#00a4ef"/><rect x="11" y="1" width="9" height="9" fill="#7fba00"/><rect x="11" y="11" width="9" height="9" fill="#ffb900"/></svg>
      Sign in with Microsoft
    </button>
    <!--<button formaction="?/signup">Sign up</button>-->
</form>

</div>

<style>
    
.brand  {
	color:#0d47a1;
	font-size:2rem;
	font-weight:bold;
	text-decoration: none;
} 
</style>