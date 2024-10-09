<script>
    import "tailwindcss/tailwind.css";

    let { children } = $props();
</script>

<div class="px-4 py-8 mx-auto max-w-96">
    {@render children()}
</div>