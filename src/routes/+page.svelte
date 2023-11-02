<script lang="ts">
    import UserInput from "../components/UserInput.svelte";
    import MessageList from "../components/MessageList.svelte"

    let messages: Array<string> = []

</script>

<body class="absolute inset-0">
  <div class="flex flex-col w-full items-center justify-between">
    <MessageList />
    <UserInput />
  </div>
</body> 

