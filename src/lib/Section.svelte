<script>
  export let title;
  export let picture1;
  export let picture2;
  /* let visible = true; */
</script>


<section id="one">
  <h1> {title} </h1>
  <img src="/public/{picture1}" alt={picture1} />
  <img src="/public/{picture2}" alt={picture2} /> 

</section>


<style>   
  section#one {
    height: 90vh;
    margin:0;
    padding:2.5rem 4rem;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    position: relative;
  }

  img {
    /* height: 20rem; */
    /* width: 10rem; */
    max-width: 30rem;
    max-height: 15rem;
  }
  h1 {
    animation: color-change 2.5s infinite;

    font-size: 3.2em;
    line-height: 1.1;

  } 

  @keyframes color-change {
    0% { color: #1a0033; }
    50% { color: #0000ff; }
    100% { color: #cc0099; }
  }

  @media screen and (max-width: 375px) {
    section#one {
      flex-direction: column;
      padding: 0;
    }
    img {
      max-width: 20rem;
      max-height: 10rem;
    }
  }



</style>
