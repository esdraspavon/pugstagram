<script>
  import Header from '../components/Header.svelte';
  import Main from '../components/Main.svelte';
  import TimeLine from '../components/TimeLine.svelte';
  import Sidebar from '../components/Sidebar.svelte';
</script>

<style>
  :global(body) {
    background: #676778;
    color: white;
  }
</style>

<Header />
<Main>
  <TimeLine />
  <Sidebar />
</Main>