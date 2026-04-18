<template>
  <div class="slide-inner">
    <div class="chrome">
      <span class="tag"><span class="dot"></span>whoami</span>
      <span class="idx">02 / 21</span>
    </div>

    <div class="split-2" style="flex:1; margin-top:16px; grid-template-columns:0.85fr 1.15fr; align-items:center;">
      <div style="position:relative; height:100%; display:flex; align-items:center; justify-content:center;">
        <div style="
          width:420px; height:520px;
          border-radius:20px;
          overflow:hidden;
          border:1px solid var(--line);
          box-shadow:0 40px 80px -20px rgba(0,0,0,0.5), 0 0 0 1px rgba(255,255,255,0.04);
          flex-shrink:0;
        ">
          <img src="/me.jpg" alt="Cristhian Recalde" style="width:100%; height:100%; object-fit:cover; object-position:top center;"/>
        </div>
      </div>

      <div style="padding-left:16px;">
        <div class="eyebrow">Speaker</div>
        <h2 class="title" style="font-size:72px; margin-bottom:8px!important;">Cristhian<br>Recalde</h2>
        <div style="font-family:var(--mono); font-size:16px; color:var(--accent); letter-spacing:0.06em; text-transform:uppercase; margin-bottom:36px;">Mobile Developer · Full Stack</div>

        <div style="display:flex; flex-direction:column; gap:20px;">
          <div style="display:grid; grid-template-columns:24px 1fr; gap:14px; align-items:baseline;">
            <span style="font-family:var(--mono); color:var(--accent-2); font-size:18px;">01</span>
            <p style="margin:0; color:var(--text-dim); font-size:19px; font-weight:300; line-height:1.5;">
              Desarrollador <span style="color:var(--text)">Full Stack</span> apasionado por crear soluciones digitales elegantes, funcionales y escalables.
            </p>
          </div>
          <div style="display:grid; grid-template-columns:24px 1fr; gap:14px; align-items:baseline;">
            <span style="font-family:var(--mono); color:var(--accent-2); font-size:18px;">02</span>
            <p style="margin:0; color:var(--text-dim); font-size:19px; font-weight:300; line-height:1.5;">
              He construido apps robustas de alto rendimiento para <span style="color:var(--text)">StartUps a nivel Global y Ecuador</span> con tecnologías modernas.
            </p>
          </div>
          <div style="display:grid; grid-template-columns:24px 1fr; gap:14px; align-items:baseline;">
            <span style="font-family:var(--mono); color:var(--accent-2); font-size:18px;">03</span>
            <p style="margin:0; color:var(--text-dim); font-size:19px; font-weight:300; line-height:1.5;">
              Aprendo continuamente, comparto conocimiento en <span style="color:var(--text)">comunidades tech</span> y contribuyo a proyectos open source.
            </p>
          </div>
        </div>

        <div style="margin-top:36px; display:flex; gap:10px; flex-wrap:wrap;">
          <span class="pill"><span class="pd"></span>Flutter · Dart</span>
          <span class="pill"><span class="pd"></span>React · Vue</span>
          <span class="pill"><span class="pd"></span>Node · Python</span>
          <span class="pill"><span class="pd"></span>Open Source</span>
        </div>
      </div>
    </div>

    <div class="footer"><span>Cristhian Recalde · Mobile Engineer</span><span>@cr.code</span></div>
  </div>
</template>
