/* ===== BODY / SLATE THEME BASE ===== */
html, body {
  height: 100%;
  margin: 0;
  font-family: 'Roboto Mono', monospace;
  font-size: 0.8em;
  line-height: 1.6;
  background-color: #f2f2f2; /* grey behind content and bottom banner */
  position: relative;
}

/* Vertical black bars using pseudo-elements */
body::before,
body::after {
  content: "";
  position: fixed;
  top: 0;
  width: calc((100% - 960px) / 2); /* space on sides outside content wrapper */
  height: 100%;
  background-color: #0e0e0e; /* black bars */
  z-index: 0;
}
body::before {
  left: 0;
}
body::after {
  right: 0;
}

/* Content wrapper sits above bars */
.content-wrapper {
  max-width: 960px;
  margin: 0 auto;
  padding: 20px;
  position: relative;
  z-index: 1;
  background: none; /* keep content area transparent if needed */
}

/* Bottom signoff and banner styling */
.bottom-signoff {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 12px;
  margin-bottom: 0;
  color: #6eaaff;
  font-size: 0.9em;
  text-align: center;
}
.bottom-signoff img {
  max-height: 100px;
  width: auto;
  border-radius: 50%;
}

.breakout-banner {
  background-color: #f2f2f2; /* grey behind bottom image */
  width: 100%;
  margin-top: 0;
}
.breakout-banner img {
  display: block;
  width: 100%;
  height: auto;
}
