# v-deo-e-edi-o

## Related resources

- [ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill)
- [awesome-video-automation](https://github.com/renezander030/awesome-video-automation)
- [claude-motion-design](https://github.com/howseen-ai/claude-motion-design)

## Motion design

[claude-motion-design](https://github.com/howseen-ai/claude-motion-design) (MIT, Howseen AI) é uma skill do Claude Code que faz vídeos de motion design só com código: uma página HTML calculada quadro a quadro, renderizada pelo Playwright e montada no ffmpeg, sem After Effects nem app de edição.

O que ela traz:

- Fluxo fixo: briefing, mapa de batidas da música, 4 quadros de teste aprovados, render completo, checagem de "pulos" de quadro, áudio e versão final.
- Animações sem cronômetro (tudo é função do tempo), então dá para refazer uma cena sem mexer no resto.
- Áudio: acha o drop da música pela energia, posiciona cada efeito sonoro no pico medido e normaliza em -14 LUFS.
- Só fontes gratuitas de mídia (Mixkit, Pexels, Unsplash) e scripts para buscá-las.
- Modo "remake", que refaz quadro a quadro um vídeo de referência com a nossa marca (sem reaproveitar música, voz ou fotos de pessoas do original).
- Regra de honestidade: dado ilustrativo aparece marcado como exemplo na tela.

Como usamos na Vilela Imóveis: referência para os nossos Reels de motion design, como o **Sábado de História** (série de sábado) e animações de abertura, números e textos. A skill foi escrita para os vídeos da Howseen (formatos 16:9 e 4:5, cores e pastas deles), então para o Reel precisamos adaptar para 1080×1920 e para a identidade da Vilela. Ela ainda não está instalada no projeto, e o repositório original não é alterado.
