<script>
    import 'normalize.css';
    import '../global.css';
</script>

<main>
    <!-- page content -->
    <slot></slot>
</main>

<footer>
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank" rel="noopener noreferrer">Frontend Mentor</a>. Coded by <a href="https://twitter.com/bwalkermills" target="_blank" rel="noopener noreferrer">Byron</a>.
</footer>

<style>
    main {
        min-height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    footer {
        display: none;
    }
</style>
