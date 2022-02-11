<!--Box.svelte <div class="box">
	<slot></slot>
</div>

<style>
	.box {
		width: 300px;
		border: 1px solid #aaa;
		border-radius: 2px;
		box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
		padding: 1em;
		margin: 0 0 1em 0;
	}
</style> -->
<script>
  import Box from "./Box.svelte";
</script>

<Box>
  <h2>Hello!</h2>
  <p>This is a box. It can contain anything.</p>
</Box>
