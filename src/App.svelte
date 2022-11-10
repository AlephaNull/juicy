<script>
  import Section from './lib/Section.svelte'
  import ModeToggle from './lib/ModeToggle.svelte'
  /* import Emoji from './lib/Emoji.svelte' */
</script>

<main>

  <ModeToggle> Light </ModeToggle> 
  <Section title={"Happy"} picture1={"wTgcIn7.jpg"} picture2={"AwSUZBL.jpg"}/> <!-- shop and turf2 -->
  <Section title={"Birthday"} picture1={"VyX2a2u.jpg"} picture2={"SysfYZa.jpg"} /> <!-- shop2 an turf3 -->
  <Section title={"Arhaan"} picture1={"zrLqDTG.jpg"} picture2={"BIiWfq7.jpg"}/> <!-- shop3 and turf1 -->
  <Section title={"Have"} picture1={"FHoUONZ.jpg"} picture2={"CH3XAqk.jpg"}/> <!-- nike,jpg and selfie1.jpg -->
  <Section title={"A"} picture1={"1s0CByS.jpg"} picture2={"Gj2VbR3.jpg"}/> <!-- selfie2.jpg and anand.jpg --> 
  <Section title={"Great"} picture1={"4f1NYTm.jpg"} picture2={"LaqMact.jpg"}/> <!-- king.jpg and shop4.jpg -->
  <Section title={"One"} picture1={"CEG0nlh.jpeg"} picture2={"gOloET9.jpg"}/> <!-- sixth.jpg and fav.jpg -->

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
		transition: background-color 2s
	}
	:global(body.dark-mode) {
		background-color: #1d3040;
		color: #bfc2c7;
  }

  main {
    transition: background 0.2s linear;

  }

  /* .dark { */
  /*   background: #292c35; */
  /* } */

</style>
