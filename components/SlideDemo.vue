<template>
  <div class="slide-inner demo">
    <div class="demo-inner">
      <div class="rec"><span class="r-dot"></span>live · demo</div>
      <h2>Demo<br>en vivo.</h2>
      <div class="sub">cambiamos a la terminal · espero 3s</div>
    </div>
  </div>
</template>

<style scoped>
.slide-inner.demo {
  background: #000 !important;
  justify-content: center;
  align-items: center;
  padding: 0 !important;
}
.slide-inner.demo::before { display: none; }
.demo-inner { text-align: center; position: relative; z-index: 1; }
.rec {
  display: inline-flex; align-items: center; gap: 12px;
  font-family: var(--mono); font-size: 16px; color: var(--red);
  letter-spacing: 0.2em; text-transform: uppercase;
  margin-bottom: 32px;
}
.r-dot {
  width: 12px; height: 12px; border-radius: 50%;
  background: var(--red); animation: pulse 1.4s ease-in-out infinite;
}
@keyframes pulse { 0%, 100% { opacity: 1; transform: scale(1); } 50% { opacity: 0.4; transform: scale(0.7); } }
h2 { font-size: 180px; font-weight: 700; letter-spacing: -0.05em; line-height: 0.9; margin: 0; color: #fff; }
.sub { font-family: var(--mono); color: #666; font-size: 20px; margin-top: 40px; letter-spacing: 0.1em; }
</style>
