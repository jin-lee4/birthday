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
        class="doodle"
      />
    </div>
    <div style="margin-top: 10px;">
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
    font-size: 3em;
    color: red;
  }

  .info-title {
    color: red;
  }

  table {
    width: 100%;
  }

  .details {
    text-align: right;
  }

  @media only screen and (min-width: 720px) {
    .doodle {
      width: 480px;
      height: auto;
    }

    p,
    table {
      font-size: 1.5em;
    }
  }

  @media only screen and (max-width: 720px) {
    .doodle {
      width: 340px;
      height: auto;
    }

    p,
    table {
      font-size: 1.5em;
    }
  }
</style>
