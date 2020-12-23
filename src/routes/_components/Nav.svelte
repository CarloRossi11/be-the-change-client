<script>
	export let segment;
</script>

<style>
	nav {
	    background: #fff3ef;
	}
	nav div {
		max-width: 960px;
		padding: 0 10px;
		margin: 0 auto;
		display: grid;
		grid-template-columns: 1fr 1fr;
		align-items: center;
	}
	h1 {
		margin-top: 10px;
		font-size: 22px;
		font-weight: bold;
	}
	ul {
		padding: 0;
   		margin: 0;
    		text-align: right;
	}
	li {
		display: inline-block;
	}
	a {
		text-decoration: none;
		padding: 1em 0.5em;
		display: block;
	}
	a.current {
		border-bottom: 3px solid #ff3e00;
	}
</style>

<nav>
	<div>
		<h1>Be The Change</h1>
		<ul>
			<li><a class:current={segment === undefined} href=".">home</a></li>
			<li><a class:current={segment === 'about'} href="about">about</a></li>
			<li><a class:current={segment === 'register'} href="/register">register</a></li>
			<li><a class:current={segment === 'login'} href="/login">login</a></li>
			<!-- <li class="nav-item"><a rel='prefetch' href="/login" class="nav-link" class:active="{$page.path === '/login'}">Sign in</a></li>
			<li class="nav-item"><a rel='prefetch' href="/register" class="nav-link" class:active="{$page.path === '/register'}">Sign up</a></li> -->
		</ul>
	</div>
</nav>
