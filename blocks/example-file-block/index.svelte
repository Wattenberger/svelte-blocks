<script lang="ts">
  import { FileBlockProps } from '@githubnext/blocks';
  let { content } = $$props as FileBlockProps;
</script>

<h1>Hello from Svelte!</h1>
<pre>
{content}
</pre>

<style>
  h1 {
    color: red;
  }
</style>
