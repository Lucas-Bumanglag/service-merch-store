<script lang="ts">
    import Card from "$lib/components/Card/Card.svelte"; // for Card testing
</script>

<h1>This is the HomePage</h1>
<p>TODO</p>

<!-- For Card testing -->
<div class="flex gap-10">
{#each [1, 2, 3, 4] as _}
    <Card image="./csi_logo.png" price={19.99} name="CSI Merchandise" />
{/each}
</div>
