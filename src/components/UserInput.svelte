<script lang="ts">
  let currentPrompt: string = '';
</script>

<form class=" input-group flex rounded-container-token w-3/4 ">
  <input bind:value={currentPrompt} placeholder="Prompt..." class=" flex-1 resize-none bg-transparent border-0 ring-0" />
  <button class="variant-filled-primary">Send</button>
</form>

