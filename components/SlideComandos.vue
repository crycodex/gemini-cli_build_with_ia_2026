<template>
  <div class="slide-inner">
    <div class="chrome">
      <span class="tag"><span class="dot"></span>commands.list</span>
      <span class="idx">12 / 21</span>
    </div>
    <h3 class="title">Los que vas a usar.</h3>

    <div style="margin-top:48px;">
      <div class="kv"><span class="k">/help</span><span class="v">Lista todo lo disponible. Empieza aquí.</span></div>
      <div class="kv"><span class="k">/chat save &lt;nombre&gt;</span><span class="v">Guarda la conversación actual. Retoma cuando quieras.</span></div>
      <div class="kv"><span class="k">/memory add</span><span class="v">Contexto persistente entre sesiones (GEMINI.md).</span></div>
      <div class="kv"><span class="k">@archivo.ts</span><span class="v">Inyecta un archivo específico en el prompt.</span></div>
      <div class="kv"><span class="k">!<span style="color:var(--text-mute)">cmd</span></span><span class="v">Ejecuta un comando shell sin salir del chat.</span></div>
      <div class="kv"><span class="k">/tools</span><span class="v">Lista las herramientas MCP conectadas.</span></div>
    </div>
    <div class="footer"><span>11 / comandos</span><span>gemini /help</span></div>
  </div>
</template>
