<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>How to Use VET</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    background: #03060f;
    color: #fff;
    line-height: 1.7;
    padding: 40px 20px;
  }
  .container { max-width: 720px; margin: 0 auto; }

  /* Header */
  .hero { text-align: center; padding: 60px 0 48px; }
  .hero-badge { display: inline-flex; align-items: center; justify-content: center; width: 80px; height: 80px; border-radius: 22px; background: linear-gradient(135deg, #0a1628, #0d2240); border: 1px solid rgba(0,212,255,.25); margin-bottom: 20px; }
  .hero-badge span { color: #00d4ff; font-weight: 900; font-size: 28px; letter-spacing: 2px; }
  .hero h1 { font-size: 34px; font-weight: 800; background: linear-gradient(135deg, #fff 0%, #00d4ff 60%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
  .hero p { font-size: 16px; color: rgba(255,255,255,.55); margin-top: 10px; }

  /* Section */
  .section { margin-bottom: 48px; }
  .section-label { font-size: 11px; font-weight: 700; letter-spacing: 3px; color: #00d4ff; text-transform: uppercase; margin-bottom: 20px; }
  h2 { font-size: 20px; font-weight: 700; margin-bottom: 8px; }

  /* Steps */
  .step { display: flex; gap: 20px; margin-bottom: 28px; }
  .step-num { flex-shrink: 0; width: 36px; height: 36px; border-radius: 50%; background: rgba(0,212,255,.12); border: 1px solid rgba(0,212,255,.3); display: flex; align-items: center; justify-content: center; font-size: 14px; font-weight: 700; color: #00d4ff; }
  .step-body h3 { font-size: 16px; font-weight: 600; margin-bottom: 4px; }
  .step-body p { font-size: 14px; color: rgba(255,255,255,.55); }

  /* Cards */
  .cards { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
  @media (max-width: 500px) { .cards { grid-template-columns: 1fr; } }
  .card { background: rgba(255,255,255,.04); border: 1px solid rgba(255,255,255,.08); border-radius: 16px; padding: 20px; }
  .card-icon { font-size: 24px; margin-bottom: 10px; }
  .card h3 { font-size: 15px; font-weight: 600; margin-bottom: 6px; }
  .card p { font-size: 13px; color: rgba(255,255,255,.5); }

  /* Score table */
  .score-row { display: flex; align-items: center; gap: 14px; padding: 14px 0; border-bottom: 1px solid rgba(255,255,255,.06); }
  .score-row:last-child { border-bottom: none; }
  .score-pill { font-size: 13px; font-weight: 700; padding: 4px 10px; border-radius: 20px; min-width: 56px; text-align: center; }
  .green { background: rgba(0,200,100,.15); color: #00c864; }
  .yellow { background: rgba(255,200,0,.12); color: #ffc800; }
  .orange { background: rgba(255,130,0,.12); color: #ff8200; }
  .red { background: rgba(255,50,50,.15); color: #ff4444; }
  .score-row p { font-size: 14px; color: rgba(255,255,255,.65); }

  /* Verdict badges */
  .verdicts { display: flex; flex-wrap: wrap; gap: 10px; margin-top: 16px; }
  .vbadge { font-size: 12px; font-weight: 600; padding: 6px 14px; border-radius: 20px; }

  /* Danger box */
  .danger-box { background: rgba(255,30,30,.08); border: 1px solid rgba(255,30,30,.25); border-radius: 16px; padding: 20px 24px; }
  .danger-box h3 { color: #ff4444; font-size: 16px; font-weight: 700; margin-bottom: 8px; }
  .danger-box p { font-size: 14px; color: rgba(255,255,255,.6); }

  /* Tips */
  .tip { display: flex; gap: 12px; margin-bottom: 16px; }
  .tip-icon { flex-shrink: 0; font-size: 18px; margin-top: 2px; }
  .tip p { font-size: 14px; color: rgba(255,255,255,.6); }

  footer { text-align: center; padding: 40px 0 20px; font-size: 13px; color: rgba(255,255,255,.2); }
  a { color: #00d4ff; text-decoration: none; }
</style>
</head>
<body>
<div class="container">

  <div class="hero">
    <div class="hero-badge"><span>VET</span></div>
    <h1>How to Use VET</h1>
    <p>Verified Evaluated Truth — Fact Check Everything</p>
  </div>

  <!-- What is VET -->
  <div class="section">
    <div class="section-label">Overview</div>
    <p style="color:rgba(255,255,255,.65);font-size:15px;">VET uses AI to fact-check social media posts, news headlines, images, and video claims in seconds. It returns three scores and a verdict so you know whether to trust — or share — what you're seeing.</p>
  </div>

  <!-- The 4 tabs -->
  <div class="section">
    <div class="section-label">The Four Tabs</div>
    <div class="cards">
      <div class="card">
        <div class="card-icon">🛡️</div>
        <h3>VET Tab</h3>
        <p>Paste any post, headline, or claim and tap "VET This Post" for instant analysis.</p>
      </div>
      <div class="card">
        <div class="card-icon">🌐</div>
        <h3>Browser Tab</h3>
        <p>Browse the web inside VET. Tap "VET This" on any page to fact-check its content.</p>
      </div>
      <div class="card">
        <div class="card-icon">🕐</div>
        <h3>History Tab</h3>
        <p>Every analysis you run is saved here automatically. Tap any entry to review it.</p>
      </div>
      <div class="card">
        <div class="card-icon">⚙️</div>
        <h3>Settings Tab</h3>
        <p>View your monthly usage, upgrade to Pro, and customize danger alerts.</p>
      </div>
    </div>
  </div>

  <!-- How to VET a post -->
  <div class="section">
    <div class="section-label">VET Tab — Step by Step</div>
    <div class="step">
      <div class="step-num">1</div>
      <div class="step-body">
        <h3>Paste the content</h3>
        <p>Copy a post, headline, claim, or URL and paste it into the text box. VET auto-detects the platform (Instagram, Twitter/X, TikTok, Facebook) from the URL.</p>
      </div>
    </div>
    <div class="step">
      <div class="step-num">2</div>
      <div class="step-body">
        <h3>Select the content type</h3>
        <p>Choose <strong>Text Claim</strong>, <strong>News Headline</strong>, <strong>Video Claim</strong>, or <strong>Image / AI</strong>. VET adjusts its scoring criteria based on what type of content it's analyzing. For images, a photo picker opens instead of the text box.</p>
      </div>
    </div>
    <div class="step">
      <div class="step-num">3</div>
      <div class="step-body">
        <h3>Tap "VET This Post"</h3>
        <p>VET searches the web for live context, then runs it through Claude AI to generate scores, flags, and sources.</p>
      </div>
    </div>
    <div class="step">
      <div class="step-num">4</div>
      <div class="step-body">
        <h3>Read your results</h3>
        <p>Three score rings appear alongside a verdict, red flags, and sources checked. If any score is below 20, a DANGER alert fires automatically.</p>
      </div>
    </div>
  </div>

  <!-- Browser -->
  <div class="section">
    <div class="section-label">Browser Tab — Step by Step</div>
    <div class="step">
      <div class="step-num">1</div>
      <div class="step-body">
        <h3>Navigate to any page</h3>
        <p>Type a URL in the address bar or use the back/forward buttons to browse normally.</p>
      </div>
    </div>
    <div class="step">
      <div class="step-num">2</div>
      <div class="step-body">
        <h3>Optional: highlight text</h3>
        <p>Long-press and highlight specific text on the page. VET will use your selection instead of the full page.</p>
      </div>
    </div>
    <div class="step">
      <div class="step-num">3</div>
      <div class="step-body">
        <h3>Tap "VET This"</h3>
        <p>The floating blue button at the bottom right opens an analysis sheet pre-filled with the page content. Tap "VET This" in the sheet to run the analysis.</p>
      </div>
    </div>
  </div>

  <!-- Share Extension -->
  <div class="section">
    <div class="section-label">Share Extension</div>
    <div class="step">
      <div class="step-num">1</div>
      <div class="step-body">
        <h3>Share from any app</h3>
        <p>In Safari, Twitter, Instagram, or any app — tap the Share button, scroll to find <strong>VET</strong>, and tap it.</p>
      </div>
    </div>
    <div class="step">
      <div class="step-num">2</div>
      <div class="step-body">
        <h3>Auto-analysis</h3>
        <p>VET opens and immediately begins analyzing the shared text or URL. No pasting required.</p>
      </div>
    </div>
  </div>

  <!-- Scores -->
  <div class="section">
    <div class="section-label">Understanding Your Scores</div>
    <div class="score-row">
      <div class="score-pill green">75–100</div>
      <p>Strong. The claim is well-supported, accurately framed, and from a credible source.</p>
    </div>
    <div class="score-row">
      <div class="score-pill yellow">50–74</div>
      <p>Moderate. Some truth but possibly missing context, unverified details, or a weak source.</p>
    </div>
    <div class="score-row">
      <div class="score-pill orange">20–49</div>
      <p>Low. Significant issues with accuracy, framing, or source credibility. Treat with caution.</p>
    </div>
    <div class="score-row">
      <div class="score-pill red">0–19</div>
      <p>Critical. DANGER alert fires. Do not share this content.</p>
    </div>

    <div style="margin-top:24px;">
      <p style="font-size:14px;color:rgba(255,255,255,.5);margin-bottom:10px;">The three scores measure different things:</p>
      <div class="score-row"><div class="score-pill" style="background:rgba(0,212,255,.1);color:#00d4ff;min-width:100px;">Truth</div><p>How accurately the claim is stated and framed.</p></div>
      <div class="score-row"><div class="score-pill" style="background:rgba(0,212,255,.1);color:#00d4ff;min-width:100px;">Factual</div><p>Whether the underlying facts are verifiable and correct.</p></div>
      <div class="score-row"><div class="score-pill" style="background:rgba(0,212,255,.1);color:#00d4ff;min-width:100px;">Source Trust</div><p>The credibility of the account or outlet that posted it.</p></div>
    </div>
  </div>

  <!-- Verdicts -->
  <div class="section">
    <div class="section-label">Verdicts</div>
    <div class="verdicts">
      <span class="vbadge" style="background:rgba(0,200,100,.12);color:#00c864;">✓ Verified</span>
      <span class="vbadge" style="background:rgba(0,200,150,.1);color:#00c896;">✓ Mostly True</span>
      <span class="vbadge" style="background:rgba(255,160,0,.1);color:#ffa000;">⚠ Misleading</span>
      <span class="vbadge" style="background:rgba(150,150,150,.1);color:#aaa;">? Unverified</span>
      <span class="vbadge" style="background:rgba(255,60,60,.12);color:#ff4444;">✗ False</span>
      <span class="vbadge" style="background:rgba(160,0,255,.1);color:#b060ff;">🎭 Satire</span>
      <span class="vbadge" style="background:rgba(0,120,255,.1);color:#4499ff;">🤖 AI Generated</span>
      <span class="vbadge" style="background:rgba(255,0,0,.15);color:#ff2222;">⚠ DANGER</span>
    </div>
  </div>

  <!-- Danger -->
  <div class="section">
    <div class="danger-box">
      <h3>⚠ DANGER Alert</h3>
      <p>When any single score drops below 20, VET fires a full DANGER alert: your screen flashes red, haptics pulse, and an audio sting plays. A modal appears with the scores and flags. This means the content is potentially harmful misinformation — do not share it.</p>
    </div>
  </div>

  <!-- Tips -->
  <div class="section">
    <div class="section-label">Tips</div>
    <div class="tip"><div class="tip-icon">💡</div><p>The more text you give VET, the better the analysis. Paste the full post rather than just the headline.</p></div>
    <div class="tip"><div class="tip-icon">🌐</div><p>If you paste a URL in the VET tab, switch to the Browser tab and use "VET This" instead — it captures the full page content.</p></div>
    <div class="tip"><div class="tip-icon">📸</div><p>For images, select the Image / AI content type. VET looks for AI generation artifacts like unnatural hands, background inconsistencies, and distorted text.</p></div>
    <div class="tip"><div class="tip-icon">🔁</div><p>VET Pro gives you unlimited analyses. Free tier includes 25 per month, resetting on the 1st of each month.</p></div>
  </div>

  <footer>
    © 2026 TrevBeats Multimedia · <a href="privacy-policy.html">Privacy Policy</a>
  </footer>

</div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>VET – Privacy Policy</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    background: #f9f9f9;
    color: #111;
    line-height: 1.7;
    padding: 40px 20px;
  }
  .container { max-width: 720px; margin: 0 auto; background: #fff; border-radius: 16px; padding: 48px; box-shadow: 0 2px 20px rgba(0,0,0,.06); }
  .logo { display: flex; align-items: center; gap: 12px; margin-bottom: 32px; }
  .logo-badge { width: 52px; height: 52px; border-radius: 14px; background: linear-gradient(135deg, #0a1628, #0d2240); display: flex; align-items: center; justify-content: center; }
  .logo-badge span { color: #00d4ff; font-weight: 900; font-size: 20px; letter-spacing: 1px; }
  .logo-text h1 { font-size: 22px; font-weight: 700; }
  .logo-text p { font-size: 13px; color: #888; }
  h2 { font-size: 16px; font-weight: 700; margin: 32px 0 10px; color: #111; }
  p { font-size: 15px; color: #333; margin-bottom: 12px; }
  ul { padding-left: 20px; margin-bottom: 12px; }
  li { font-size: 15px; color: #333; margin-bottom: 6px; }
  .updated { font-size: 13px; color: #aaa; margin-bottom: 32px; }
  .highlight { background: #f0f8ff; border-left: 3px solid #00a8e8; padding: 14px 18px; border-radius: 8px; margin: 20px 0; }
  a { color: #007aff; text-decoration: none; }
  footer { margin-top: 48px; font-size: 13px; color: #aaa; text-align: center; }
</style>
</head>
<body>
<div class="container">

  <div class="logo">
    <div class="logo-badge"><span>VET</span></div>
    <div class="logo-text">
      <h1>VET – Fact Check Everything</h1>
      <p>Privacy Policy</p>
    </div>
  </div>

  <p class="updated">Last updated: March 2026</p>

  <div class="highlight">
    <strong>Short version:</strong> VET does not sell your data, does not store your photos on our servers, and does not track you. The text and images you submit are sent to AI models for analysis only.
  </div>

  <h2>1. Who We Are</h2>
  <p>VET is developed and operated by TrevBeats Multimedia. If you have questions about this policy, contact us at <a href="mailto:trevbeatsmultimedia@gmail.com">trevbeatsmultimedia@gmail.com</a>.</p>

  <h2>2. What Data We Collect</h2>
  <p>VET collects only what is necessary to provide fact-checking services:</p>
  <ul>
    <li><strong>Text you submit:</strong> Posts, headlines, claims, and URLs you paste into the app for analysis.</li>
    <li><strong>Images you select:</strong> Photos chosen from your library when using the Image/AI detection feature.</li>
    <li><strong>Usage count:</strong> The number of analyses you've performed this month, stored locally on your device to enforce the free tier limit.</li>
    <li><strong>Purchase status:</strong> Whether you have an active VET Pro subscription, managed by Apple's App Store.</li>
  </ul>

  <h2>3. Photo Library Access</h2>
  <p>When you select the <strong>Image / AI</strong> content type, VET requests access to your photo library. This access is used solely to let you choose an image for fact-checking analysis.</p>
  <ul>
    <li>Photos are sent to our AI analysis service only when you explicitly tap "VET This".</li>
    <li>Images are processed in memory and are <strong>not stored</strong> on our servers after analysis is complete.</li>
    <li>We do not scan, index, or access any photos other than the one you explicitly select.</li>
    <li>You can revoke photo access at any time in iOS Settings → Privacy & Security → Photos → VET.</li>
  </ul>

  <h2>4. How We Use Your Data</h2>
  <p>Text and images you submit are sent to our backend (Firebase Cloud Functions) which forwards them to:</p>
  <ul>
    <li><strong>Anthropic Claude</strong> – primary AI analysis engine</li>
    <li><strong>Google Gemini</strong> – backup AI engine (used only if Claude is unavailable)</li>
    <li><strong>Brave Search API</strong> – live web search to provide real-time context for fact-checking</li>
  </ul>
  <p>These services process your content to generate fact-check scores and verdicts. We do not use your submitted content to train AI models.</p>

  <h2>5. Data Storage</h2>
  <ul>
    <li><strong>Analysis history</strong> is stored locally on your device using UserDefaults. It is never uploaded to our servers.</li>
    <li><strong>No account is required.</strong> We do not store personal profiles or user accounts.</li>
    <li><strong>Submitted text and images</strong> are not retained after analysis. They are processed in real time and discarded.</li>
  </ul>

  <h2>6. Third-Party Services</h2>
  <p>VET uses the following third-party services, each governed by their own privacy policies:</p>
  <ul>
    <li><a href="https://www.anthropic.com/privacy">Anthropic Privacy Policy</a></li>
    <li><a href="https://policies.google.com/privacy">Google Privacy Policy</a></li>
    <li><a href="https://brave.com/privacy/search/">Brave Search Privacy Policy</a></li>
    <li><a href="https://firebase.google.com/support/privacy">Firebase (Google) Privacy Policy</a></li>
  </ul>
  <p>In-app purchases are handled entirely by Apple. We do not receive or store your payment information.</p>

  <h2>7. Children's Privacy</h2>
  <p>VET is not directed at children under 13. We do not knowingly collect personal information from children.</p>

  <h2>8. Changes to This Policy</h2>
  <p>We may update this policy as VET's features evolve. The "last updated" date at the top of this page will reflect any changes. Continued use of the app after changes constitutes acceptance of the updated policy.</p>

  <h2>9. Contact</h2>
  <p>Questions or concerns? Email us at <a href="mailto:trevbeatsmultimedia@gmail.com">trevbeatsmultimedia@gmail.com</a>.</p>

  <footer>© 2026 TrevBeats Multimedia · VET – Fact Check Everything</footer>
</div>
</body>
</html>
