# 📷 Ângelo AI - Pose + Hands Tracker

Aplicação de deteção de corpo e mãos em tempo real usando **MediaPipe Holistic**, com visual neon fullscreen.

## ✨ Funcionalidades

- **Deteção de Pose** 🦾 — Esqueleto completo do corpo (33 landmarks) a verde neon
- **Deteção de Mãos** 🤚 — Mão esquerda e direita (21 landmarks cada) a azul ciano
- **Modo Espelho** 🪞 — Inverte horizontalmente para uma experiência natural (como um espelho)
- **Captura de Screenshots** 📸 — Guarda o frame atual como PNG
- **Pausa/Retoma** ⏸️ — Poupa bateria quando não está a ser usado
- **Contador de FPS** — Monitoriza a performance em tempo real
- **Design Responsivo** — Funciona em mobile e desktop
- **Efeitos Glow** — Landmarks com brilho neon para um visual futurista

## 🚀 Como Usar

1. Abre o `index.html` num browser moderno (Chrome, Edge, Firefox).
2. **Permite o acesso à câmara** quando o browser pedir.
3. 
   - **⏸ Pausar** — Para/retoma a deteção
   - **🪞 Espelho** — Ativa/desativa o modo espelho
   - **📸 Capturar** — Tira um screenshot
   - **Tecla Espaço** — Atalho para pausar/retomar

## 🛠️ Tecnologias

| Tecnologia | Versão | Uso |
|------------|--------|-----|
| [MediaPipe Holistic](https://google.github.io/mediapipe/solutions/holistic) | via CDN | Deteção de pose, mãos e face |
| [MediaPipe Drawing Utils](https://google.github.io/mediapipe/solutions/drawing_utils) | via CDN | Desenho dos landmarks |
| [MediaPipe Camera Utils](https://google.github.io/mediapipe/solutions/camera_utils) | via CDN | Gestão da câmara |
| HTML5 Canvas | — | Renderização em tempo real |

## ⚙️ Otimizações

- **modelComplexity: 0** — Máxima velocidade (ideal para mobile)
- **Resolução adaptativa**: 640×480 em mobile, 1280×720 em desktop
- **enableFaceGeometry: false** — Desativa deteção facial para poupar CPU
- **smoothLandmarks: true** — Suaviza os movimentos para evitar tremor

## 📱 Compatibilidade

| Dispositivo | Browser | Funciona? |
|-------------|---------|-----------|
| Desktop | Chrome / Edge | ✅ |
| Desktop | Firefox | ✅ |
| Desktop | Safari | ⚠️ Parcial (testar) |
| Android | Chrome | ✅ |
| iOS | Safari | ⚠️ Pode exigir permissões |



## 📄 Licença

Este projeto está sob a licença MIT.

---

Feito com 💚 por Ângelo
