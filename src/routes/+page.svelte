
<script>
    // import { MetaTags } from 'svelte-meta-tags';
    import Main from "../FrontendComponents/HomePage/Main.svelte";
    import WhySvARIA from "../FrontendComponents/HomePage/WhySvaria.svelte";
    import GettingStarted from "../FrontendComponents/HomePage/GettingStarted.svelte";
    import News from "../FrontendComponents/HomePage/News.svelte";
</script>

<main class="flex flex-col items-center w-full h-full">
    <Main />
    <WhySvARIA />
    <GettingStarted />
    <News />
</main>

<!-- <MetaTags
    title = 'Comprehensive Accessible Component Library and Toolkit'
    titleTemplate = '%s | Build Accessible UIs for Svelte'
    description = "SvARIA puts the power of building accessible UIs into the hands of any developer with an easy-to-use NPM package."
/> -->