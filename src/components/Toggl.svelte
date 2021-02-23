<script>
    import WiMoonAltThirdQuarter from 'svelte-icons/wi/WiMoonAltThirdQuarter.svelte'

    let dark = false;
    function toggle(e) {
        e.preventDefault();
        dark = !dark;
        document.getElementById('main').classList.toggle('dark')
    }
</script>

<button class="icon btn" on:click={e => toggle(e)}>
    <WiMoonAltThirdQuarter />
</button>

<style>
    .icon {
        width: 64px;
        height: 64px;
        color: white;
    }
</style>