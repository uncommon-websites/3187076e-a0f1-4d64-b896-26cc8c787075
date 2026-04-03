<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="page">
	<h1>Error {page.status}</h1>
	<p>{page.error?.message ?? "Something went wrong. Your digital clone is standing by — let's get you back on track."}</p>
	<a href="/">Go back home</a>
</main>
