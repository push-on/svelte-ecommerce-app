<script>
  let name = ""
</script>

<input bind:value={name} placeholder="enter your name" />
<p>Hello {name || "World"}!</p>
