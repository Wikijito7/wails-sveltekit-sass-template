<script lang="js">
    import Header from '../components/Header.svelte';
import '../scss/app.scss';
</script>

<main>
    <Header />
    <div class="content">
        <slot />
    </div>
</main>

<style lang="scss">
    content {
        display: flex;
        flex-direction: column;
    }
</style>