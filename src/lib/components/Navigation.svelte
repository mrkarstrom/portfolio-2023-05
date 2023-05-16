<script lang="ts">
	import { drawerStore } from '@skeletonlabs/skeleton';

	function closeDrawer(): void {
		drawerStore.close();
	}
</script>

<nav class="list-nav p-4">
	<ul>
		<li><a href="/" on:click={closeDrawer}>Main</a></li>
		<li><a href="/blog" on:click={closeDrawer}>Blog</a></li>
		<li><a href="/games" on:click={closeDrawer}>Games</a></li>
		<li><a href="/projects" on:click={closeDrawer}>Projects</a></li>
		<li><a href="/help" on:click={closeDrawer}>Help</a></li>
	</ul>
</nav>
