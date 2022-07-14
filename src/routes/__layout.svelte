<script>
    import Title from "$lib/title.svelte";
    import '../styles/global.css'
</script>

<header>
<Title/>
</header>

<main>
<!-- Page content -->
<slot></slot>
</main>

<footer>
    <p> <b>Copyright By Me</b> </p>
</footer>

<style>
    header{
        display: flex;
        justify-content: center;
    }

    main{
        max-width: 960;
        margin: 20px auto;

    }

    footer{
        text-align: center;
    }
</style>