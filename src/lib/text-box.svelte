<script lang="ts">
	export let title: string;
</script>

<div class="self-center bg-fuchsia-50 container p-4 rounded-xl basis-1/2 mx-2 flex flex-wrap">
	<span class="text-2xl font-black text-zinc-600">{title}</span>
	<span class="text-lg font-light text-zinc-800 mt-2"><slot /></span>
</div>
