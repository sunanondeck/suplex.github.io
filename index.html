<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Plex Server Status</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body { font-family: Arial, sans-serif; margin:0; background:#111; color:#eee; }
    header { padding:20px; text-align:center; background:#202020; }
    h1 { margin:0; }
    .container { max-width:800px; margin:40px auto; padding:0 20px; }
    .status { padding:20px; border-radius:10px; margin-bottom:20px; }
    .operational { background:#1f6f3e; }
    .maintenance { background:#8a6d1f; }
    .outage { background:#7a1f1f; }
    .card { background:#1a1a1a; padding:20px; border-radius:10px; margin-bottom:20px; }
    .time { opacity:0.7; font-size:0.9em; }
    footer { text-align:center; padding:20px; opacity:0.6; }
  </style>
</head>
<body>

<header>
  <h1>Plex Server Status</h1>
</header>

<div class="container">

  <div id="statusBox" class="status">
    <h2 id="statusTitle"></h2>
    <p id="statusMessage"></p>
  </div>

  <div class="card">
    <h3>Maintenance Window</h3>
    <p id="maintenanceWindow"></p>
  </div>

  <div class="card">
    <h3>Updates</h3>
    <ul id="updates"></ul>
  </div>

</div>

<footer>
  Last updated: <span id="lastUpdated"></span>
</footer>

<script>
const statusData = {
  status: "operational", // operational | maintenance | outage
  title: "All Systems Operational",
  message: "The Plex server is running normally.",
  maintenanceWindow: "None scheduled",
  updates: [
    { time: "2026-04-06 10:00", text: "Server rebooted after library update." }
  ]
}

const statusBox = document.getElementById("statusBox")
const statusTitle = document.getElementById("statusTitle")
const statusMessage = document.getElementById("statusMessage")
const maintenanceWindow = document.getElementById("maintenanceWindow")
const updates = document.getElementById("updates")

statusBox.classList.add(statusData.status)
statusTitle.textContent = statusData.title
statusMessage.textContent = statusData.message
maintenanceWindow.textContent = statusData.maintenanceWindow

statusData.updates.forEach(u => {
  const li = document.createElement("li")
  li.innerHTML = `<span class="time">${u.time}</span> — ${u.text}`
  updates.appendChild(li)
})

document.getElementById("lastUpdated").textContent = new Date().toLocaleString()
</script>

</body>
</html>
