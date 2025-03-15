<script lang="ts">
  // Component logic goes here
</script>

<main>
  <div class="content">
    seanamoroso.com
    <p>
      <a href="mailto:me@seanamoroso.com">email me</a>
    </p>
    <p>
      <a href="/resume.pdf" target="_blank" rel="noopener noreferrer">
        resume
      </a>
    </p>
  </div>
</main>

<style>
  :global(body) {
    margin: 0;
    padding: 0;
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  main {
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0;
    padding: 0;
  }

  .content {
    text-align: center;
  }

  /* We'll import global styles in the main.ts file */
</style> 