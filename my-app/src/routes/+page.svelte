<script>
import Message from './Message.svelte';

const msg = 'Hello from Parent';

let name = 'Hawari Muflih Munte'
</script>

<p>Hello there, my name is {name}</p>
<Message message={msg}></Message>

