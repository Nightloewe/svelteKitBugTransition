<script>
    import { navigating } from "$app/stores"
</script>
{#if $navigating}
    Lade...
{:else}
    <slot></slot>
{/if}