<script>
    import { Greet } from '$lib/wailsjs/go/main/App'
    let name = "";
    let response = "";

    const onClick = () => {
        Greet(name).then((greeting) => response = greeting);
    }
</script>

<main>
    <h1>Welcome to Wails Sveltekit SASS Template</h1>

    <div>Please enter your name below 👇</div>
        <input type="text" bind:value={name}/>
        <button on:click={onClick}>Great</button>
    <div>

    <div>
        <p>{ response }</p>
    </div>
</main>

<style lang="scss">

</style>