<script lang="js">
    import '../scss/app.scss';
</script>

<main>
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