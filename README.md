<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kayden Documentary</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: "Poppins", system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
      background: radial-gradient(circle at top, #2f5fff 0%, #050816 40%, #02030a 100%);
      color: #f5f7ff;
      line-height: 1.7;
      padding-bottom: 40px;
    }

    header {
      text-align: center;
      padding: 60px 20px 40px;
      background: radial-gradient(circle at top, rgba(117,182,255,0.35), transparent 55%);
    }

    header h1 {
      font-size: 2.7rem;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: #e4ecff;
      text-shadow: 0 0 18px rgba(80, 160, 255, 0.95);
    }

    header p {
      margin-top: 12px;
      max-width: 600px;
      margin-inline: auto;
      color: #c9d6ff;
    }

    .tagline {
      margin-top: 18px;
      font-style: italic;
      opacity: 0.9;
    }

    main {
      max-width: 960px;
      margin: 0 auto;
      padding: 0 20px;
    }

    section {
      background: linear-gradient(135deg, rgba(19,35,90,0.96), rgba(7,16,46,0.98));
      border-radius: 20px;
      padding: 26px 22px 26px;
      margin-top: 22px;
      border: 1px solid rgba(134, 189, 255, 0.35);
      box-shadow: 0 0 25px rgba(0, 0, 0, 0.45);
      position: relative;
      overflow: hidden;
    }

    section::before {
      content: "";
      position: absolute;
      inset: -40%;
      background-image: radial-gradient(circle at 10% 0%, rgba(93, 169, 255, 0.14) 0, transparent 55%),
                        radial-gradient(circle at 90% 100%, rgba(0, 255, 248, 0.09) 0, transparent 55%);
      opacity: 0.8;
      pointer-events: none;
    }

    .section-inner {
      position: relative;
      z-index: 1;
    }

    h2 {
      font-size: 1.4rem;
      margin-bottom: 10px;
      color: #f0f4ff;
      text-shadow: 0 0 12px rgba(112, 179, 255, 0.7);
    }

    h3 {
      font-size: 1.1rem;
      margin: 12px 0 6px;
      color: #d6e4ff;
    }

    p, li {
      font-size: 0.98rem;
      color: #d1dbff;
    }

    ul {
      margin-left: 18px;
      margin-top: 6px;
    }

    .pill-row {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 10px;
    }

    .pill {
      padding: 6px 11px;
      border-radius: 999px;
      border: 1px solid rgba(155, 199, 255, 0.7);
      font-size: 0.8rem;
      text-transform: uppercase;
      letter-spacing: 0.07em;
      color: #e4ecff;
      background: linear-gradient(135deg, rgba(60, 104, 173, 0.6), rgba(15, 37, 88, 0.95));
    }

    .facts-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 12px;
      margin-top: 10px;
    }

    .fact-box {
      background: linear-gradient(135deg, rgba(15, 26, 71, 0.9), rgba(6, 16, 49, 0.96));
      border-radius: 14px;
      padding: 10px 12px;
      border: 1px solid rgba(135, 186, 255, 0.4);
      font-size: 0.9rem;
    }

    .highlight {
      color: #7fd0ff;
      font-weight: 600;
    }

    .avatar-strip {
      margin-top: 10px;
      font-size: 0.94rem;
      border-left: 3px solid rgba(64, 180, 255,
