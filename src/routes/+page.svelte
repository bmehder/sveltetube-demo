<script>
  import Sveltetube from 'sveltetube/Sveltetube.svelte'
  import Prism from '$lib/Prism/Prism.svelte'
</script>

<svelte:head>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/prism-themes/1.9.0/prism-a11y-dark.min.css"
  />
  <title>SvelteTube Demo</title>
</svelte:head>

<div>
  <h2>SvelteTube</h2>
  <Sveltetube
    id="XSK1Bt9O0Pw"
    title="Sondre Lerche - Alone In The Night (feat. AURORA)"
    color="rgba(255,255,255,0.9)"
    radius="1rem"
    shadow="0 10px 20px rgba(0,0,0,0.24)"
  />
  <Prism
    code={`<Sveltetube
    id="XSK1Bt9O0Pw"
    title="Sondre Lerche - Alone In The Night (feat. AURORA)"
    color="rgba(255,255,255,0.9)"
    radius="1rem"
    shadow="0 10px 20px rgba(0,0,0,0.24)"
  />`}
  />
</div>

<style>
  div {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    max-width: 800px;
    margin: auto;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }
</style>
