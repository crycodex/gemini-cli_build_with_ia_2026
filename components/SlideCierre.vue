<template>
  <div class="slide-inner">
    <div class="chrome">
      <span class="tag"><span class="dot"></span>end</span>
      <span class="idx">21 / 21</span>
    </div>
    <div class="split-2" style="flex:1; margin-top: 24px; margin-bottom: 40px; grid-template-columns: 1.2fr 0.8fr;">
      <div>
        <div class="eyebrow">Gracias</div>
        <h1 class="title" style="font-size:140px!important; line-height:0.95!important;">Preguntas.</h1>
        <p class="lede" style="font-size:32px; margin-top:28px;">
          Instala, rompe cosas, ven con dudas.<br>
          <span style="color:var(--text-mute)">El workshop sigue en el Q&amp;A.</span>
        </p>
      </div>

      <div style="display:flex; flex-direction:column; align-items:center;">
        <div style="background: white; padding: 24px; border-radius: 32px; box-shadow: 0 20px 60px rgba(0,0,0,0.5);">
          <img src="/meweb.png" alt="Sigue a @cry.code" style="width: 280px; height: 280px; display: block; border-radius: 12px;" />
        </div>
        <div style="margin-top: 36px; text-align: center;">
          <div style="font-family:var(--mono); font-size:32px; font-weight: 500; letter-spacing: 0.05em; color: var(--text);">@cry.code</div>
          <div style="display:flex; gap: 24px; justify-content: center; margin-top: 20px; color: var(--text-dim); font-size: 32px;">
            <carbon:logo-linkedin />
            <carbon:logo-github />
            <carbon:logo-instagram />
            <carbon:logo-youtube />
          </div>
        </div>
      </div>
    </div>
    <div style="display:grid; grid-template-columns:repeat(3,1fr); gap:32px; padding-top:36px; border-top:1px solid var(--line); font-family:var(--mono); font-size:15px;">
      <div>
        <div style="color:var(--text-mute); font-size:11px; letter-spacing:0.15em; text-transform:uppercase; margin-bottom:8px;">Speaker</div>
        <div>Cristhian Recalde</div>
        <div style="color:var(--text-mute); margin-top:2px;">Mobile Developer</div>
      </div>
      <div>
        <div style="color:var(--text-mute); font-size:11px; letter-spacing:0.15em; text-transform:uppercase; margin-bottom:8px;">Pruebalo tú mismo</div>
        <div style="color:var(--accent)">npm i -g @google/gemini-cli</div>
        <div style="color:var(--text-mute); margin-top:2px;">github.com/google-gemini/gemini-cli</div>
      </div>
      <div>
        <div style="color:var(--text-mute); font-size:11px; letter-spacing:0.15em; text-transform:uppercase; margin-bottom:8px;">Recursos</div>
        <div>ai.google.dev/gemini-api</div>
        <div style="color:var(--text-mute); margin-top:2px;">modelcontextprotocol.io</div>
      </div>
    </div>
  </div>
</template>
