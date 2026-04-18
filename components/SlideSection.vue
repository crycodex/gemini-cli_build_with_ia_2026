<template>
  <div class="slide-inner divider-slide">
    <div class="chrome">
      <span class="tag"><span class="dot"></span>section.{{ number }}</span>
      <span class="idx">{{ idx }} / 21</span>
    </div>
    <div class="spacer"></div>
    <div class="accent-line"></div>
    <div class="eyebrow">{{ eyebrow }}</div>
    <h2>{{ title }}</h2>
    <p class="lede" style="margin-top:28px;">{{ subtitle }}</p>
    <div class="spacer"></div>
    <div class="ghostword" :style="`font-size:520px; bottom:20px; right:40px;`" aria-hidden="true">{{ number }}</div>
  </div>
</template>

<script setup>
defineProps({
  number: { type: String, default: '01' },
  title: { type: String, default: 'Sección' },
  subtitle: { type: String, default: '' },
  eyebrow: { type: String, default: 'Capítulo uno' },
  idx: { type: String, default: '04' },
})
</script>

<style scoped>
.divider-slide {
  align-items: flex-start;
  justify-content: center;
}
.divider-slide .eyebrow { font-size: 18px; }
.divider-slide h2 {
  font-size: 128px; line-height: 0.95; font-weight: 700;
  letter-spacing: -0.04em; margin: 0; max-width: 1500px;
}
.divider-slide .accent-line {
  width: 120px; height: 4px;
  background: var(--accent); margin-bottom: 32px;
}
.ghostword {
  position: absolute;
  font-family: var(--mono);
  font-weight: 300;
  letter-spacing: -0.05em;
  color: var(--text);
  opacity: 0.025;
  line-height: 0.8;
  pointer-events: none;
  user-select: none;
}
</style>
