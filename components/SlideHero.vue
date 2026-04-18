<template>
  <div class="slidev-layout hero">
    <div class="inner">
      <div class="gemini-mark">
        <svg viewBox="0 0 28 28" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M14 2 L15.5 12.5 L26 14 L15.5 15.5 L14 26 L12.5 15.5 L2 14 L12.5 12.5 Z" fill="url(#g1)"/>
          <defs>
            <linearGradient id="g1" x1="0" y1="0" x2="28" y2="28">
              <stop offset="0%" stop-color="#8ab4f8"/>
              <stop offset="50%" stop-color="#c58af9"/>
              <stop offset="100%" stop-color="#fdd663"/>
            </linearGradient>
          </defs>
        </svg>
        <span>gemini-cli · workshop</span>
      </div>

      <div>
        <h1>
          Antigravity<br>
          con <span class="amp">Gemini CLI</span>
        </h1>
        <p class="lede" style="margin-top:32px; font-size:26px;">
          Dominando la alternativa a Claude Code.<br>
          <span style="color:var(--text-mute)">Una sesión práctica para developers.</span>
        </p>
      </div>

      <div class="meta">
        <div>
          <label>Speaker</label>Cristhian Recalde<br>
          <span style="color:var(--text-mute)">Mobile Developer</span>
        </div>
        <div>
          <label>Formato</label>Workshop · 60 min<br>
          <span style="color:var(--text-mute)">Hands-on + demo</span>
        </div>
        <div>
          <label>Audiencia</label>Google · Engineers<br>
          <span style="color:var(--text-mute)">Abril 2026</span>
        </div>
      </div>
    </div>
    <div class="ghostword" aria-hidden="true">cli</div>
  </div>
</template>

<style scoped>
.slidev-layout.hero {
  padding: 0 !important;
}
.inner {
  position: absolute; inset: 0;
  padding: 96px 112px 112px;
  display: flex; flex-direction: column; justify-content: space-between;
}
.gemini-mark {
  display: inline-flex; align-items: center; gap: 14px;
  font-family: var(--mono); font-size: 16px; color: var(--text-dim);
  letter-spacing: 0.02em;
}
.gemini-mark svg { width: 28px; height: 28px; }
h1 {
  font-size: 148px;
  line-height: 0.92;
  letter-spacing: -0.045em;
  font-weight: 700;
  margin: 0;
}
.amp { color: var(--accent-2); font-weight: 300; }
.meta {
  display: grid; grid-template-columns: auto auto auto; gap: 48px;
  font-family: var(--mono); font-size: 15px; color: var(--text-dim);
  padding-top: 36px; border-top: 1px solid var(--line);
}
.meta label {
  display: block; color: var(--text-mute); font-size: 11px;
  letter-spacing: 0.15em; text-transform: uppercase; margin-bottom: 8px;
}
.ghostword {
  position: absolute;
  bottom: 40px; right: 60px;
  font-family: var(--mono);
  font-size: 440px;
  font-weight: 300;
  letter-spacing: -0.05em;
  color: var(--text);
  opacity: 0.025;
  line-height: 0.8;
  pointer-events: none;
  user-select: none;
}
</style>
