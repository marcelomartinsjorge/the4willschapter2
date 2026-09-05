# Capítulo 2 — checklist de assets pendentes

`main.css` e `app.js` estão intactos, copiados direto do Cap 1 (confirmei com `diff`, zero alterações).

## Imagens — ✅ já estão no pacote
Já converti e coloquei dentro de `assets/images/` as 8 imagens que você mandou:
- `hero.webp` (a `lauracap2.png`)
- `og-cover.jpg` (também a partir da `lauracap2.png`)
- `codex-torneio-real.webp`
- `codex-general-rei.webp`
- `codex-mae-rainha.webp`
- `codex-cavaleiro.webp`
- `codex-juiza.webp`
- `codex-guerra-eterna.webp`
- `codex-apagar-das-luzes.webp`

Não precisa fazer nada com imagem — só falta áudio e vídeo.

## Áudio ambiente (loop por zona)
- `assets/audio/alfaiataria-loop.mp3`
- `assets/audio/oratorio-loop.mp3`
- `assets/audio/laranjal-loop.mp3`

## Áudio pontual (one-shot, toca de vez em quando dentro da zona)
- `assets/audio/tecido-farfalhar.mp3` (zona alfaiataria)
- `assets/audio/vela-tremular.mp3` (zona oratório)
- `assets/audio/espadas-metal.mp3` (zona laranjal)

## Narração (voz da Laura — mesmo arquivo serve pros dois idiomas, seguindo o padrão do Cap 1)
- `assets/audio/narration/line1.mp3`
- `assets/audio/narration/line2.mp3`
- `assets/audio/narration/line3.mp3`

## Vídeo (cenas)
- `assets/video/oratorio-justine.mp4`
- `assets/video/laranjal-duelo.mp4`

Nenhum desses nomes é obrigatório no sentido de "só pode ser esse" — são os que eu já cravei no `chapter-config.js` e no `index.html`. Se você quiser nomes diferentes, é só me avisar que eu ajusto os dois arquivos juntos, ou você mesmo troca (são só strings, não tem lógica escondida).

## Coisas que decidi e quero sua confirmação
1. **Neve desativada** (`disableSnow: true`) — Redom não tem clima gelado estabelecido como o Aheryn. Se quiser neve mesmo assim, é só eu trocar pra `false`.
2. **Subtítulo do capítulo**: "Sob a Seda" / "Beneath the Silk" — é só um placeholder meu, troque se tiver algo melhor.
3. **Zonas**: dividi o capítulo em 3 ambientes — Aposento do Alfaiate (dourado), Oratório (turquesa), Laranjal (dourado). Se você prefere separar a cena da mãe do Gideon num ambiente à parte, dá pra criar uma 4ª zona.
