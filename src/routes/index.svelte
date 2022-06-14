<script>
    import breakfastpicture from '../assets/breakfastpicture.jpg';
</script>

<svelte:head>
    <meta name="title" content="Breakfeast | Main">
<meta name="description" content="24/7 Breakfeast!">
    <title>Home</title>
</svelte:head>

<main>
    <div class="flex flex-col m-4">
        <span class="flex justify-center">
            <h1 class="text-2xl font-semibold">24/7 Breakfast</h1>
        </span>

        <div class="flex justify-center">
            <h2>Check out our <a href="/menu" class="underline">menu.</a></h2>
        </div>

        <div class="flex justify-center">
            <img alt="Some eggs scrambled on a piece of toast" class="object-contain h-50 w-60" src="{breakfastpicture}">
        </div>
    </div>
</main>
