<script>
  const allowedDate = 7; // change per page
  const today = new Date();
  const day = today.getDate();
  const month = today.getMonth() + 1;

  if (month !== 2 || day < allowedDate) {
    document.body.innerHTML = `
      <div style="background:#111;color:white;height:100vh;
      display:flex;align-items:center;justify-content:center;
      text-align:center;font-family:sans-serif;padding:20px;">
        <div>
          <h1>⏳ Not yet, Maya ❤️</h1>
          <p>This surprise unlocks on <b>Feb ${allowedDate}</b> 🌹</p>
        </div>
      </div>`;
  }
</script># Love
This is a surprise website for my love
