<template>
  <div class="slide-inner">
    <div class="chrome">
      <span class="tag"><span class="dot"></span>definition</span>
      <span class="idx">05 / 21</span>
    </div>
    <div class="split-2" style="margin-top:20px;">
      <div>
        <div class="eyebrow">Definición</div>
        <h2 class="title" style="font-size:88px!important;">Un agente<br>en tu shell.</h2>
        <p class="lede">
          Gemini CLI es una herramienta <span class="mono" style="color:var(--text)">open-source</span> que trae
          el modelo Gemini directo a tu terminal —
          con acceso a tus archivos, a tu git y a tu entorno real.
        </p>
        <div style="margin-top:32px; display:flex; gap:10px; flex-wrap:wrap;">
          <span class="pill"><span class="pd"></span>Apache 2.0</span>
          <span class="pill"><span class="pd"></span>Node 18+</span>
          <span class="pill"><span class="pd"></span>Gemini 2.5 Pro</span>
        </div>
      </div>
      <div>
        <div class="terminal">
          <div class="tbar">
            <span class="c r"></span><span class="c y"></span><span class="c g"></span>
            <span class="title">~/projects — gemini</span>
          </div>
          <div class="tbody">
            <div><span class="prompt">$</span> gemini</div>
            <div style="color:var(--text-mute); margin:8px 0;">Connected to gemini-2.5-pro · 1M context</div>
            <div style="margin-top:14px;"><span style="color:var(--accent-2)">›</span> Refactoriza <span class="str">UserService.ts</span> para usar Result&lt;T&gt;</div>
            <div style="color:var(--text-mute); margin-top:8px; font-size:16px;">› Leyendo 3 archivos…<br>› Propuesta generada (diff + tests)</div>
            <div style="margin-top:12px;"><span class="prompt">$</span><span class="caret"></span></div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer"><span>04 / definición</span><span>cristhian recalde</span></div>
  </div>
</template>
