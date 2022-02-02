<script>
    
</script>

<svelte:head>
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
    <title>Frontend Mentor | QR code component</title>
</svelte:head>

<div>
    <img src="/image-qr-code.png" alt="qr code">
    <h1>Improve your front-end skills by building projects</h1>

    <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
</div>

<style>
    div {
        width: 20rem;
        padding: 1rem;
        background-color: var(--white);
        border-radius: 1.125rem;
        text-align: center;
        box-shadow: 0 1.5rem 1.5rem hsla(0, 0%, 50%, 12%);
    }

    img {
        display: block;
        width: 100%;
        height: auto;
        border-radius: 0.625rem;
        margin-bottom: 1.5rem;
    }

    h1 {
        font-size: 1.375rem;
        line-height: 1.3;
        margin-top: 0;
        margin-bottom: 0.875rem;
        color: var(--dark-blue);
    }

    p {
        font-size: 0.9375rem;
        line-height: 1.3;
        max-width: 250px;
        margin: 0 auto 1.5rem;
        color: var(--grayish-blue);
    }
</style>
