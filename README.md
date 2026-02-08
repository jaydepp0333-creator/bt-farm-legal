<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover" />
  <title>Privacy Policy • BT Farm – Cloud Miner</title>
  <style>
    :root{
      --bg:#050210;
      --card: rgba(255,255,255,.08);
      --stroke: rgba(255,255,255,.12);
      --txt: rgba(255,255,255,.88);
      --muted: rgba(255,255,255,.62);
      --neon: #BFA6FF;
      --p1:#6D28FF;
      --p2:#3B1DFF;
    }
    body{
      margin:0;
      font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display", "SF Pro Text", Segoe UI, Roboto, Arial;
      background: radial-gradient(1200px 900px at 20% 10%, rgba(109,40,255,.22), transparent 60%),
                  radial-gradient(1000px 700px at 80% 30%, rgba(59,29,255,.18), transparent 60%),
                  linear-gradient(135deg, rgba(5,2,16,.96), rgba(5,2,16,.98));
      color: var(--txt);
      overflow-x:hidden;
    }
    .stars{
      position:fixed; inset:0;
      background:
        radial-gradient(2px 2px at 10% 20%, rgba(255,255,255,.25), transparent 40%),
        radial-gradient(1px 1px at 30% 70%, rgba(255,255,255,.18), transparent 40%),
        radial-gradient(1px 1px at 60% 40%, rgba(255,255,255,.22), transparent 40%),
        radial-gradient(2px 2px at 80% 60%, rgba(255,255,255,.16), transparent 40%);
      animation: drift 8s ease-in-out infinite alternate;
      opacity:.55;
      pointer-events:none;
    }
    @keyframes drift{ from{ transform:translate3d(0,0,0)} to{ transform:translate3d(-10px, -14px, 0)} }

    .wrap{ max-width: 880px; margin: 0 auto; padding: 22px 16px 36px; }
    .title{
      font-size: 34px; font-weight: 900; letter-spacing: .2px;
      margin: 8px 0 14px;
      background: linear-gradient(135deg, rgba(255,255,255,.92), rgba(191,166,255,.95));
      -webkit-background-clip:text; background-clip:text; color: transparent;
      transform: translateY(8px);
      opacity: 0;
      animation: pop .55s ease-out forwards;
    }
    @keyframes pop{ to{ transform:translateY(0); opacity:1 } }

    .card{
      border-radius: 22px;
      background: linear-gradient(135deg, rgba(255,255,255,.10), rgba(59,29,255,.10), rgba(0,0,0,.10));
      border: 1px solid var(--stroke);
      box-shadow: 0 18px 40px rgba(0,0,0,.45);
      backdrop-filter: blur(14px);
      padding: 16px 16px;
      position: relative;
      overflow:hidden;
    }
    .sheen{
      position:absolute; inset:-40%;
      background: linear-gradient(135deg, transparent 40%, rgba(255,255,255,.08), transparent 60%);
      transform: translateX(-40%);
      animation: sheen 3.2s ease-in-out infinite;
    }
    @keyframes sheen{ 0%{ transform:translateX(-40%) } 50%{ transform:translateX(40%) } 100%{ transform:translateX(-40%) } }

    h3{ margin: 14px 0 8px; font-size: 14px; letter-spacing:.6px; color: rgba(255,255,255,.95); }
    p, li{ color: var(--muted); line-height: 1.55; font-weight: 600; font-size: 14px; }
    ul{ padding-left: 18px; margin: 8px 0 10px; }
    .accent{ color: var(--neon); }
    .small{ font-size: 12px; color: rgba(255,255,255,.56); font-weight: 700; }
  </style>
</head>
<body>
  <div class="stars"></div>
  <div class="wrap">
    <div class="title">Privacy Policy</div>

    <div class="card">
      <div class="sheen"></div>
      <div class="small">BT Farm – Cloud Miner • Last updated: 2026-02-07</div>
      <p><span class="accent">Simulation Notice:</span> This app is a simulator/entertainment app. Mining, balances, and withdrawals are simulated and do not represent real cryptocurrency mining or real-world financial services.</p>

      <h3>1) Overview</h3>
      <p>We respect your privacy. This policy explains what we collect and how we use it.</p>

      <h3>2) Information We Collect</h3>
      <ul>
        <li>Account information (email/password) used for authentication (Firebase Authentication).</li>
        <li>Profile details you provide (name; optional mobile/country).</li>
        <li>In-app activity such as mining sessions, game sessions, and simulated wallet history.</li>
        <li>Device/diagnostics information (crash logs) when enabled by platform services.</li>
      </ul>

      <h3>3) How We Use Information</h3>
      <ul>
        <li>To manage accounts and allow sign-in.</li>
        <li>To save and display your simulated balances and history.</li>
        <li>To respond to support and feedback.</li>
        <li>To improve performance and stability.</li>
      </ul>

      <h3>4) Data Storage</h3>
      <p>We may store data using Firebase services (Google) and may cache some data locally on your device for performance.</p>

      <h3>5) Sharing</h3>
      <p>We do not sell personal information. We may share data with service providers used to operate the app (e.g., Firebase) or when required by law.</p>

      <h3>6) Children</h3>
      <p>This app is not intended for children under 13 (or the minimum age required in your country).</p>

      <h3>7) Security</h3>
      <p>We use reasonable safeguards, but no method is 100% secure.</p>

      <h3>8) Contact</h3>
      <p>Email: <span class="accent">jaydeeplathiya@icloud.com</span></p>

      <p class="small">By using the app, you agree to this Privacy Policy.</p>
    </div>
  </div>
</body>
</html>
