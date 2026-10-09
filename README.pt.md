# Cola de referência: comandos do FFmpeg · FFmpeg Cheatsheet

> 🌍 [中文](README.md) · [Español](README.es.md)

Uma **cola de uma página só** com os comandos do FFmpeg que você realmente vai usar: 28 comandos, e cada um responde a apenas duas perguntas — **o que ele faz e um comando pronto para copiar e colar**. Transcodificação, compressão, extração de áudio, GIF, cortes, marcas d'água, streaming e processamento em lote. Sem enrolação.

## Para quem é

Criadores de vídeo, desenvolvedores, engenheiros de operações e qualquer pessoa que já sofreu com formatos de áudio e vídeo. Se toda vez que você usa o FFmpeg precisa pesquisar os parâmetros, esta cola devolve o seu copiar-e-colar.

## Como usar

1. Vá direto ao **[CHEATSHEET.md](CHEATSHEET.md)** — o corpo da referência, legível para desenvolvedores de qualquer idioma.
2. Instale o FFmpeg primeiro:
   ```bash
   brew install ffmpeg          # macOS
   sudo apt install ffmpeg     # Debian/Ubuntu
   ```
3. Cada comando pode ser copiado e executado como está; troque apenas `input.mp4` / `output.mp4` pelos seus arquivos.

## O que está incluído

| Categoria | Conteúdo |
|---|---|
| 📦 Instalação | Instalação e verificação de versão e codecs |
| 🔄 Transcodificação | Qualquer formato→MP4, MP4→WebM, MKV→MP4 sem recodificar |
| 🗜️ Compressão | Compressão CRF, presets, codificação em duas passadas |
| 🎵 Extrair áudio | Para MP3 / M4A, extração sem recodificar |
| 🖼️ Vídeo para GIF | Método de paleta em duas etapas, adeus GIF serrilhado |
| ✂️ Cortar e juntar | Corte rápido e preciso, concatenação sem perdas |
| 📐 Redimensionar e cortar | `scale`, proporção automática, `crop` |
| 🎞️ Frames | Miniatura, vídeo para sequência de imagens, trocar áudio |
| 💧 Marcas d'água e legendas | Logo com `overlay`, legendas embutidas, texto |
| 📡 Streaming | Modelo de publicação RTMP |
| 🔁 Em lote | Loops `for` para transcodificar ou extrair áudio em massa |

Todos os comandos usam sintaxe real do FFmpeg, verificada parâmetro por parâmetro.

## Documentação oficial

- https://ffmpeg.org/documentation.html

## Contribuições são bem-vindas

Achou um comando errado, uma tradução a melhorar ou uma receita melhor? *Pull requests* são bem-vindos. Mantenha o formato (o que faz / comando / etiquetas) e **verifique se o comando funciona antes de enviar**.

## Licença

MIT © 2026 Guangyi Zhao. Veja [LICENSE](LICENSE).
