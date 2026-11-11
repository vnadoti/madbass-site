# MADBASS — Official Landing Page & Web Simulator

Landing page de alta conversão e simulador interativo em tempo real para o **MADBASS by Nadoti (NLabs)**, plugin gerador de basslines MIDI para Tech House (VST3, Windows 10/11 64-bit).

## 🚀 Tecnologias

- **HTML5 & Tailwind CSS**: Layout responsivo, tema industrial escuro, painel CRT fosforescente e faixas de alerta hazard.
- **Web Audio API**: Sintetizador analógico de bassline Tech House, sub-bass, 4-on-the-floor kick, hi-hat e efeitos mecânicos da alavanca com cancelamento de estalos (*anti-click envelope*).
- **HTML5 Canvas**: Piano roll CRT estilo monitor fosfórico dos anos 80/90 com taxa de 60 FPS, playhead sincronizado e visualização de notas travadas em âmbar (*STABILIZE*).
- **Standard MIDI Format 0**: Motor gerador de arquivos `.mid` binários em tempo real para download direto na DAW (Ableton, FL Studio, Logic, Reaper, etc.).
- **Vercel Edge Network**: Otimizado para distribuição global com compressão, cache estático e cabeçalhos de segurança HTTP.

## 📦 Estrutura de Arquivos para Produção

```
├── index.html           # Página principal com simulador e checkout
├── bundle.min.js        # Script de produção otimizado e minificado
├── styles.css           # Estilos customizados (CRT scanlines, brilhos neon)
├── vercel.json          # Configuração de headers e cache do Vercel
├── images/              # Assets visuais oficiais do plugin e interface
└── fonts/               # Tipografia técnica (Saira Stencil, Share Tech Mono)
```

## 🛠️ Deploy no Vercel

1. Importe este repositório no seu dashboard da [Vercel](https://vercel.com).
2. Deixe o Framework Preset como **Other** (projeto estático puro).
3. Clique em **Deploy**.

© 2026 NLabs by Nadoti. Todos os direitos reservados.

