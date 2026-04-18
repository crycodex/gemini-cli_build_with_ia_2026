<template>
  <div class="slide-inner">
    <div class="chrome">
      <span class="tag"><span class="dot"></span>tips.md</span>
      <span class="idx">19 / 21</span>
    </div>
    <h2 class="title">Lo que<br>no sale en los docs.</h2>

    <div class="split-4" style="margin-top:56px; grid-template-columns:repeat(2,1fr);">
      <div class="card">
        <span class="k">tip · 01</span>
        <h4><code class="mono" style="color:var(--accent-3)">GEMINI.md</code> en el root.</h4>
        <p>Convenciones del repo, stack, coding style. Gemini lo lee automáticamente.</p>
      </div>
      <div class="card">
        <span class="k">tip · 02</span>
        <h4>Checkpoints antes de editar.</h4>
        <p><code class="mono" style="color:var(--accent-3)">/chat save pre-refactor</code> para poder volver si algo explota.</p>
      </div>
      <div class="card">
        <span class="k">tip · 03</span>
        <h4>Usa Flash para iterar.</h4>
        <p>Pro para tareas pesadas, Flash para Q&amp;A. Se cambia con <code class="mono" style="color:var(--accent-3)">/model</code>.</p>
      </div>
      <div class="card">
        <span class="k">tip · 04</span>
        <h4>Compone con pipes.</h4>
        <p><code class="mono" style="color:var(--accent-3)">git diff | gemini -p "resumí este PR"</code> — es Unix, tratalo como tal.</p>
      </div>
    </div>
    <div class="footer"><span>18 / tips</span><span>field-tested</span></div>
  </div>
</template>
