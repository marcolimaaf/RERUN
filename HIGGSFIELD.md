# Vídeo de abertura — roteiros para o Higgsfield

O site já tem um espaço para um vídeo de fundo no topo da página. Basta gerar o vídeo,
salvar como `assets/hero.mp4` e publicar: ele aparece sozinho por cima da animação das
raias (com 55% de opacidade, mudo e em loop). Sem o arquivo, a animação em canvas assume.

**Especificações recomendadas**
- Proporção 16:9, 1280×720 ou 1920×1080, 8–12 s, loop limpo (início ≈ fim)
- Sem texto e sem logotipos na imagem (o título é HTML por cima)
- Tons escuros, com laranja (#E8622B) como cor de luz dominante
- Comprimir para menos de 4 MB: `ffmpeg -i in.mp4 -an -vcodec libx264 -crf 28 -preset slow -movflags +faststart assets/hero.mp4`

Use um modelo de vídeo (ex.: Seedance, Kling ou Veo) no Higgsfield.

---

## Opção A — "O bastão" (recomendada)

> Cinematic close-up, night, an empty urban running track lit by warm sodium streetlights.
> Two hands in a relay exchange: an older hand passes a worn pair of running shoes forward
> to a younger hand, in slow motion. Shallow depth of field, anamorphic lens flare in
> orange, film grain, deep shadows, 35mm film look. Camera slowly tracks forward along the
> lane lines. No text, no logos. Seamless loop.

## Opção B — "A segunda volta"

> Slow dolly shot along a dark athletics track at dawn, lane lines converging to the
> horizon. A pair of used sneakers sits on the starting line, dust particles floating in a
> warm orange backlight. Gentle camera push-in, moody contrast, cinematic color grade
> (teal shadows, orange highlights), film grain. No people, no text, no logos.

## Opção C — "Comunidade"

> Golden hour on a community football pitch in a Brazilian neighborhood, silhouettes of
> kids running and passing a ball, long shadows, backlit by the setting sun, warm orange
> haze, handheld cinematic camera, shallow depth of field, slow motion 60fps. Faces not
> identifiable. No text, no logos.

> Observação: o vídeo é ilustrativo. Se no futuro houver fotos e vídeos reais de entregas
> do RERUN (com autorização de imagem), prefira-os: transmitem mais confiança que imagens
> geradas.
