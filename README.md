

<html lang="hi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Brocool – Top 10 Mobile Tips</title>

  <!-- SEO Meta Tags -->
  <meta name="description" content="Top 10 mobile tips to boost speed, battery life, security and hidden features. Brocool smart mobile guide.">
  <meta name="keywords" content="mobile tips, android tips, phone speed, battery saving, hidden codes, brocool">
  <meta name="author" content="Brocool.in" />

  <!-- Open Graph -->
  <meta property="og:title" content="Top 10 Mobile Tips – Brocool" />
  <meta property="og:description" content="Mobile speed, battery, hidden codes, security – top 10 pro tips for Android users." />
  <meta property="og:type" content="article" />
  <meta property="og:site_name" content="Brocool" />

  <!-- JSON-LD Structured Data -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Article",
    "headline": "Top 10 Mobile Tips",
    "author": "Brocool.in",
    "description": "Top 10 secret and useful mobile tips for speed, battery, hidden settings and security.",
    "publisher": {
      "@type": "Organization",
      "name": "Brocool"
    }
  }
  </script>

  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #00000f, #0055ff);
      color: #fff;
    }

    header {
      text-align: center;
      padding: 20px;
      font-size: 28px;
      font-weight: bold;
    }

    .container {
      display: flex;
      gap: 15px;
      padding: 15px;
      height: 90vh;
    }

    .tips-list {
      width: 100%;
      background: rgba(255, 255, 255, 0.15);
      border-radius: 12px;
      overflow-y: scroll;
      padding: 100px;
    }

    .tips-list::-webkit-scrollbar {
      width: 100px;
    }

    .tip-btn {
      width: 1000%;
      padding: 12px;
      margin-bottom: 10px;
      background: #ffffffaa;
      color: #000;
      border: none;
      border-radius: 10px;
      font-size: 16px;
      cursor: pointer;
      font-weight: bold;
      transition: 0.3s;
    }
    .tip-btn:hover {
      background: #fff;
    }

    .content-box {
      width: 20%;
      background: #ffffffdd;
      color: #000;
      padding: 10px;
      border-radius: 12px;
      overflow-y: auto;
    }
  </style>
</head>
<body>

<header>Brocool – Top 10 Mobile Tips</header>

<div class="container">

  <!-- LEFT: TIP BUTTONS -->
  <div class="tips-list">
    <button class="tip-btn" onclick="showTip(1)">1. Mobile Hang Fix</button>
    <button class="tip-btn" onclick="showTip(2)">2. Hidden Wifi Test</button>
    <button class="tip-btn" onclick="showTip(3)">3. YouTube Ads Off</button>
    <button class="tip-btn" onclick="showTip(4)">4. Battery Health Boost</button>
    <button class="tip-btn" onclick="showTip(5)">5. Heating Fix</button>
    <button class="tip-btn" onclick="showTip(6)">6. Gaming Lag Fix</button>
    <button class="tip-btn" onclick="showTip(7)">7. Caller Name Announce</button>
    <button class="tip-btn" onclick="showTip(8)">8. Hidden Virus Scan</button>
    <button class="tip-btn" onclick="showTip(9)">9. Fast Charging Trick</button>
    <button class="tip-btn" onclick="showTip(10)">10. Deleted Photos Restore</button>
  </div>

  <!-- RIGHT: CONTENT -->
  <div class="content-box" id="content">
    <h2>Tip Select Karo</h2>
    <p>Left side वरून कोणतीही टिप क्लिक करा आणि इथे full माहिती दिसेल.</p>
  </div>

</div>

<script>
  function showTip(num) {
    const tips = {
      1: "Settings → Battery → Background activity off करा. Mobile 40% fast होतो.",
      2: "Dial करा: *#*#4636#*#* → WiFi Status → Real-time internet speed.",
      3: "YouTube Ads remove: NewPipe/Revanced browser वापरा + Background play free.",
      4: "Charge नेहमी 20%–80% ठेवा + Fast charging बंद करा. Battery health strong.",
      5: "Developer mode → Background process limit → 2 processes. Heating कमी.",
      6: "Developer mode → Force 4x MSAA ON + animations off = Gaming smooth.",
      7: "Accessibility → Caller Name Announcement ON करा.",
      8: "Google Files → Clean → Virus scan → Hidden malware delete.",
      9: "Airplane mode ON + Brightness कमी = Fast charging 25% जास्त.",
      10:"Google Photos → Bin → 60 days restore."
    };
    document.getElementById('content').innerHTML = `
      <h2>Tip ${num}</h2>
      <p>${tips[num]}</p>
    `;
  }
</script>

</body>
</html>
