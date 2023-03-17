<script>
    import Header from '../lib/Header.svelte';
    import '../pico.min.css'
</script>

<Header />
<main>
    <slot></slot>
</main>

<style>
    main {
        padding: 1rem;
    }
</style>