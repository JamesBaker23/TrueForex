# TrueForex
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Privacy Policy — TRUE FOREX</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#ffffff;
      --muted:#6b7280;
      --text:#0f1724;
      --accent:#0ea5a3;
      --accent-600:#059e99;
      --card:#f8fafc;
      --glass: rgba(14,165,163,0.08);
      --radius:14px;
      font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
      --max-width:1100px;
    }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:var(--text);-webkit-font-smoothing:antialiased}
    .wrap{max-width:var(--max-width);margin:0 auto;padding:48px 24px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#6ee7b7);display:flex;align-items:center;justify-content:center;font-weight:700;color:#043033}
    nav{display:flex;gap:20px;align-items:center}
    nav a{color:var(--muted);text-decoration:none;font-weight:600}
    nav a:hover{color:var(--accent-600)}
    h1{font-size:36px;line-height:1.1;margin:24px 0 16px}
    h2{margin-top:24px}
    p{color:var(--muted);line-height:1.6}
    footer{margin-top:72px;padding:28px 0;border-top:1px solid #f1f5f9;color:var(--muted);font-size:14px}
    @media (max-width:980px){.logo{width:48px;height:48px}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="logo">TF</div>
        <div>
          <div style="font-weight:800">TRUE FOREX</div>
          <div style="font-size:13px;color:var(--muted);margin-top:2px">Forex & Stock Market Investments • Focused on returns</div>
        </div>
      </div>
      <nav>
        <a href="index.html#services">Services</a>
        <a href="index.html#approach">Approach</a>
        <a href="index.html#education">Education</a>
        <a href="index.html#pricing">Pricing</a>
        <a href="index.html#about">About</a>
        <a href="index.html#contact">Contact</a>
        <a href="terms.html">Terms</a>
        <a href="privacy.html">Privacy</a>
      </nav>
    </header>

    <main>
      <h1>Privacy Policy</h1>
      <p>TRUE FOREX values your privacy. This policy outlines how we collect, use, and protect your information.</p>

      <h2>Information We Collect</h2>
      <p>We may collect personal details such as your name, email address, and any information you submit via contact forms.</p>

      <h2>Use of Information</h2>
      <p>Your information is used only to respond to inquiries, provide updates, and improve our services. We will not sell or share your information with third parties without consent.</p>

      <h2>Data Security</h2>
      <p>We implement reasonable safeguards to protect your personal information from unauthorized access or disclosure.</p>

      <h2>Cookies</h2>
      <p>Our website may use cookies to enhance user experience. You can adjust browser settings to refuse cookies if preferred.</p>

      <h2>Contact</h2>
      <p>If you have questions about this policy, contact us at <a href="mailto:hello@trueforex.com">hello@trueforex.com</a>.</p>
    </main>

    <footer>
      <div style="display:flex;justify-content:space-between;gap:12px;align-items:center;flex-wrap:wrap">
        <div>© <strong>TRUE FOREX</strong> <span id="year"></span></div>
        <div class="muted">Designed with a focus on returns.</div>
      </div>
    </footer>
  </div>
  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
