<script>
  import Reciever from '../lib/reciever.svelte';
  import Sender from '../lib/sender.svelte';
  const title = 'Parcel App';
</script>

<svelte:head>
  <title>{title}</title>
</svelte:head>

<Reciever />
<Sender />
