<script>
  import Section from './lib/Section.svelte'
  import ModeToggle from './lib/ModeToggle.svelte'
  import Emoji from './lib/Emoji.svelte'
</script>

<main>
  <ModeToggle> Light </ModeToggle> 
  <Section title={"Happy"} picture1={"shop.jpg"} picture2={"turf2.jpg"}/> 
  <Section title={"Birthday"} picture1={"shop2.jpg"} picture2={"turf3.jpg"} /> 
  <Section title={"Arhaan"} picture1={"shop3.jpg"} picture2={"turf1.jpg"}/>
  <Section title={"Have"} picture1={"nike.jpg"} picture2={"selfie1.jpg"}/>
  <Section title={"A"} picture1={"selfie2.jpg"} picture2={"anand.jpg"}/>
  <Section title={"Great"} picture1={"king.jpg"} picture2={"shop4.jpg"}/>
  <Section title={"One"} picture1={"sixth.jpg"}/>
  <ModeToggle />


</main>

<style>
  
    :root {
    font-family: Inter, Avenir, Helvetica, Arial, sans-serif;
    font-size: 3.2em;
    line-height: 1.1;
    font-size: 16px;
    line-height: 24px;
    font-weight: 400;

    color-scheme: light dark;
    /* color: rgba(255, 255, 255, 0.87); */
    /* background-color: red; */

    font-synthesis: none;
    text-rendering: optimizeLegibility;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    -webkit-text-size-adjust: 100%;
  }
  :global(body) {
		background-color: #f2eee2;
		color: #0084f6;
		transition: background-color 5s
	}
	:global(body.dark-mode) {
		background-color: #1d3040;
		color: #bfc2c7;
  }

  main {
    transition: background 0.2s linear;

  }

  main.dark {
    background: #292c35;
  }

</style>
