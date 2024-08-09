<script>
    import { fly } from 'svelte/transition'
</script>

<div style="height: 100%;" transition:fly={{y:200, duration: 500}}>
    Test
</div>
<a href="/test">Test</a>