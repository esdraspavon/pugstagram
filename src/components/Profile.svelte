<script>
  export let nickname;
  export let name;
</script>

<style>
  .Profile-content {
    display: flex;
    align-items: center;
  }
  .Profile-avatar img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
  }
  .Profile-info {
    margin: 0 0 0 0.5em;
  }
  .Profile-info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .Profile-info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>

<div class="Profile">
  <div class="Profile-content">
    <div class="Profile-avatar">
      <img src="https://avatars2.githubusercontent.com/u/18061371?s=460&u=15514a1b80843453d3e66c6a28c7ec672ae6b5a2&v=4" alt="" />
    </div>
    <div class="Profile-info">
      <h2>{nickname}</h2>
      <span>{name}</span>
    </div>
  </div>
</div>