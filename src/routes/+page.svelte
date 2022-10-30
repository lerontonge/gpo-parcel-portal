<script>
  import Reciever from '../lib/reciever.svelte';
  import Sender from '../lib/sender.svelte';
  import Navbar from '$lib/navbar.svelte';
  const title = 'Parcel App';
</script>

<svelte:head>
  <title>{title}</title>
</svelte:head>

<Navbar />
<Reciever />
<Sender />
