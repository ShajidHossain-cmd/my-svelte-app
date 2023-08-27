<script>
	import { page } from '$app/stores';
	
</script>

<h1>{$page.status} {$page.error.message}</h1>
<div>
  <p>Looks like you lost your way</p>
  <a href="/">Go to home page</a>
</div>
