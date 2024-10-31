<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<div class="flex h-screen w-full bg-slate-800 text-slate-200">
	<div class="fixed left-0 flex h-full w-80 flex-col items-center justify-center bg-slate-900">
		<ul class="list-none text-center">
			<li class="mb-4 text-2xl font-bold">ovaphlow</li>
			<li>MES</li>
		</ul>
	</div>
	<div class="ml-80 flex flex h-full w-full flex-col p-16">
		<div class="flex flex-1 flex-col items-center justify-center gap-4">
			{@render children()}
		</div>
		<footer class="mt-8 bg-slate-800 p-2 text-center">咨询电话 18246068342</footer>
	</div>
</div>
