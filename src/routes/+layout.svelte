<script>
    let { children } = $props();

    export const ssr = false;
</script>

<link href="https://cdn.jsdelivr.net/npm/daisyui@4.12.10/dist/full.min.css" rel="stylesheet" />

{@render children()}