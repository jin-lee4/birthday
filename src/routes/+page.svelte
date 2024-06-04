<script>
  import image from "/src/images/doodle.png";
</script>

<body>
  <div>
    <div>
      <h1>You're Invited</h1>
      <p>Join Jin for a slice of cake and a yummy drink!</p>
    </div>
    <div>
      <enhanced:img
        src="/src/images/doodle.png"
        alt="birthday doodle"
        sizes="min(480, 100vw)"
      />
    </div>
    <div>
      <table>
        <tr>
          <td class="info-title">When</td>
          <td class="details">Friday, June Twenty Eighth, Seven PM</td>
        </tr>
        <tr>
          <td class="info-title">Where</td>
          <td class="details">TBD</td>
        </tr>
        <tr>
          <td class="info-title">What</td>
          <td class="details">Cozy birthday vibes</td>
        </tr>
      </table>
    </div>
    <p>Snacks and juicy conversation starters encouraged</p>
  </div>
</body>

<style>
  p,
  table {
    font-size: 2em;
  }

  h1 {
    font-size: 4em;
    color: red;
  }

  .info-title {
    color: red;
  }

  table {
    width: 100%;
  }
</style>
