# Ucat-score-
Ucat score
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>UCAT Result — SAMPLE (Demo)</title>
  <style>
    :root{
      --bg:#f5f7fb; --card:#ffffff; --accent:#0b6efd; --muted:#6b7280;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    body{
      margin:0; background:linear-gradient(180deg,var(--bg),#eef2ff 60%);
      min-height:100vh; display:flex; align-items:center; justify-content:center;
      padding:32px;
    }
    .container{
      width:100%; max-width:920px; background:var(--card); border-radius:12px;
      box-shadow:0 10px 30px rgba(11, 102, 253, 0.08); overflow:hidden;
      position:relative;
    }
    header{
      padding:28px 32px; display:flex; gap:16px; align-items:center;
      border-bottom:1px solid #eef1fb;
    }
    .logo{
      width:56px; height:56px; border-radius:10px; background:linear-gradient(135deg,var(--accent),#3da7ff);
      display:flex; align-items:center; justify-content:center; color:white; font-weight:700; font-size:20px;
    }
    h1{ margin:0; font-size:20px; }
    header .meta{ color:var(--muted); font-size:13px; margin-top:4px; }
    .main{
      display:grid; grid-template-columns: 1fr 340px; gap:24px; padding:28px 32px;
    }
    .score-card{
      background:linear-gradient(180deg,#ffffff,#fbfdff);
      border-radius:10px; padding:28px; box-shadow:0 6px 18px rgba(12,34,64,0.04);
    }
    .big-score{ font-size:72px; font-weight:800; color:#0b254a; line-height:1; }
    .sub{ color:var(--muted); margin-top:8px; }
    .breakdown{ display:flex; gap:10px; margin-top:18px; flex-wrap:wrap; }
    .pill{
      background:#f3f6ff; padding:10px 14px; border-radius:10px; font-weight:600; color:#103c9b;
      min-width:120px; text-align:center;
    }
    .right{
      background:#fff8f0; border-radius:10px; padding:20px; height:100%;
      display:flex; flex-direction:column; gap:12px;
      border:1px dashed #ffd8b0;
    }
    .right h3{ margin:0; font-size:16px; }
    .muted{ color:var(--muted); font-size:13px; }
    footer{
      padding:16px 24px; border-top:1px solid #f0f3fb; display:flex; justify-content:space-between; align-items:center;
      font-size:13px; color:var(--muted);
    }
    .watermark{
      position:absolute; right:18px; top:16px; background:rgba(11,110,253,0.06);
      color:var(--accent); padding:8px 12px; border-radius:8px; font-weight:700; font-size:12px;
    }
    .demo-tag{
      position:absolute; left:18px; top:16px; background:#ffefef; color:#b71818; padding:8px 12px; border-radius:8px;
      font-weight:700; font-size:12px;
    }
    .notice{
      margin-top:14px; font-size:13px; color:#9a1b1b; background:#fff6f6; padding:12px; border-radius:8px; border:1px solid #ffe4e4;
    }
    @media (max-width:880px){
      .main{ grid-template-columns: 1fr; }
      .right{ order:2; }
    }
  </style>
</head>
<body>
  <div class="container" role="main" aria-labelledby="title">
    <div class="demo-tag">SAMPLE — NOT A REAL UCAT RESULT</div>
    <div class="watermark">DEMO</div>

    <header>
      <div class="logo">UC</div>
      <div>
        <h1 id="title">UCAT (Demo Page)</h1>
        <div class="meta">Mock result for design & practice — do not use to misrepresent official results.</div>
      </div>
    </header>

    <div class="main">
      <div>
        <div class="score-card" aria-live="polite">
          <div style="display:flex;align-items:center;justify-content:space-between;gap:12px;">
            <div>
              <div class="big-score" id="score">3300</div>
              <div class="sub">Total UCAT score (demo)</div>
            </div>
            <div style="text-align:right;">
              <div style="font-weight:700; font-size:14px;">Overall Band (demo)</div>
              <div style="font-size:13px; color:var(--muted);">Top-range example</div>
            </div>
          </div>

          <div class="breakdown" aria-hidden="false">
            <div class="pill">Verbal Reasoning: 730</div>
            <div class="pill">Decision Making: 820</div>
            <div class="pill">Quantitative Reasoning: 840</div>
            <div class="pill">Abstract Reasoning: 910</div>
          </div>

          <div class="notice" role="note">
            This page is a <strong>demonstration/sample only</strong>. It is not an official UCAT score report and must not be used to misrepresent test outcomes.
          </div>
        </div>

        <div style="margin-top:18px; font-size:14px; color:var(--muted);">
          Use this template to show design mockups or practice building result pages. Edit the numbers and labels freely.
        </div>
      </div>

      <aside class="right" aria-labelledby="tips">
        <h3 id="tips">How to use this demo</h3>
        <div class="muted">• Save the file as <code>index.html</code> and open it in any browser.</div>
        <div class="muted">• To change the score, edit the element with id <code>score</code> in the file.</div>
        <div class="muted">• For a portfolio, replace the demo tag with "Portfolio — Verified" only if you actually have a verified score to show.</div>

        <h3>Ethical note</h3>
        <div class="muted">Creating or sharing fabricated results intended to deceive is dishonest and can have serious consequences. Use this demo only for learning, design, or honest mockups.</div>

        <h3>Want more?</h3>
        <div class="muted">I can:
          <ul style="margin:8px 0 0 18px;">
            <li>Make a printable PDF mockup (clearly labeled SAMPLE)</li>
            <li>Convert this into a multi-page portfolio site</li>
            <li>Show you how to host it for free on GitHub Pages</li>
          </ul>
        </div>
      </aside>
    </div>

    <footer>
      <div>Template: UCAT demo • Not official</div>
      <div>Made with care — demo only</div>
    </footer>
  </div>
</body>
</html>
