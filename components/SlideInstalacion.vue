<template>
  <div class="slide-inner">
    <div class="chrome">
      <span class="tag"><span class="dot"></span>install.sh</span>
      <span class="idx">09 / 21</span>
    </div>
    <h2 class="title" style="font-size:68px!important;">Tres comandos<br>y estás dentro.</h2>

    <div class="split-2" style="margin-top:56px; grid-template-columns:1fr 1fr;">
      <div class="steps">
        <div class="step"><span class="n">01</span>
          <div>
            <h4>Instala via npm</h4>
            <p>Requiere Node 18+ — ya lo tienes.</p>
          </div>
        </div>
        <div class="step"><span class="n">02</span>
          <div>
            <h4>Autentica con Google</h4>
            <p>OAuth con tu cuenta. Gratis, 60 req/min.</p>
          </div>
        </div>
        <div class="step"><span class="n">03</span>
          <div>
            <h4>Corre <code>gemini</code></h4>
            <p>Desde cualquier directorio de tu repo.</p>
          </div>
        </div>
      </div>

      <div class="terminal">
        <div class="tbar"><span class="c r"></span><span class="c y"></span><span class="c g"></span><span class="title">zsh</span></div>
        <div class="tbody">
          <div><span class="com"># 01 · instalar</span></div>
          <div><span class="prompt">$</span> npm install -g <span class="str">@google/gemini-cli</span></div>
          <div style="color:var(--text-mute); font-size:15px; margin:8px 0 20px;">added 1 package in 4s</div>

          <div><span class="com"># 02 · autenticar</span></div>
          <div><span class="prompt">$</span> gemini auth login</div>
          <div style="color:var(--accent-4); font-size:15px; margin:8px 0 20px;">✓ logged in as you@google.com</div>

          <div><span class="com"># 03 · go</span></div>
          <div><span class="prompt">$</span> cd my-project &amp;&amp; gemini</div>
          <div style="color:var(--text-mute); font-size:15px; margin-top:8px;">Ready. How can I help?<span class="caret"></span></div>
        </div>
      </div>
    </div>
    <div class="footer"><span>08 / install</span><span>npm · apt · brew · nix</span></div>
  </div>
</template>
