<script>
  export let name;
  import Video from "./tutorial/binding6/VideoBinding.svelte";
  import Typewritter from "./tutorial/transitions10/Typewritter.svelte";
  import Custom from "./tutorial/transitions10/Custom.svelte";
</script>

<main>
  <h1>Hello {name}!</h1>
  <p>
    Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
    how to build Svelte apps.
  </p>
  <h2>This is another title</h2>
  <Typewritter />
  <Custom />
  <Video />
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
