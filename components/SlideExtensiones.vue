<template>
  <div class="slide-inner">
    <div class="chrome">
      <span class="tag"><span class="dot"></span>extensions</span>
      <span class="idx">18 / 21</span>
    </div>
    <h2 class="title">Extensiones<br>&amp; MCP.</h2>
    <p class="lede">El CLI por sí mismo ya es potente. Con MCP, se conecta a todo lo demás.</p>

    <div class="feat-grid" style="margin-top:56px; grid-template-columns:repeat(4,1fr);">
      <div class="feat"><span class="n">·github</span><h4>GitHub MCP</h4><p>Issues, PRs, reviews desde la terminal.</p></div>
      <div class="feat"><span class="n">·db</span><h4>Postgres / BigQuery</h4><p>Query directo, resultados estructurados.</p></div>
      <div class="feat"><span class="n">·web</span><h4>Web fetch</h4><p>Lee páginas, docs, RFCs por URL.</p></div>
      <div class="feat"><span class="n">·custom</span><h4>Custom tools</h4><p>Exponé un script tuyo como herramienta.</p></div>
    </div>

    <div style="margin-top:40px; display:flex; gap:16px; align-items:center;">
      <div class="terminal" style="flex:1; font-size:16px;">
        <div class="tbar"><span class="c r"></span><span class="c y"></span><span class="c g"></span><span class="title">~ gemini</span></div>
        <div class="tbody" style="padding:20px 26px;">
          <div><span class="prompt">$</span> gemini extensions install <span class="str">@github/mcp</span></div>
          <div style="color:var(--accent-4); margin-top:6px;">✓ installed · 14 tools available</div>
        </div>
      </div>
    </div>
    <div class="footer"><span>17 / extensiones</span><span>mcp · model context protocol</span></div>
  </div>
</template>
