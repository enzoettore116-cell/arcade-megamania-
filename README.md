# 🚀 MEGAMANIA — Arcade Space Shooter

> Jogo de tiros espacial 8-bit de tela fixa, inspirado no clássico **MegaMania** do Atari 2600.
> Criado com HTML5 Canvas puro, pixel art via código e Web Audio API.

---

## 🎮 Como Jogar

Abra o arquivo `index.html` diretamente no navegador — **sem instalação necessária**.

**Ou acesse online via GitHub Pages** (se habilitado no repositório).

---

## ⌨️ Controles

| Ação | Teclado | Mobile |
|------|---------|--------|
| Mover esquerda | `←` ou `A` | Botão ◀ |
| Mover direita | `→` ou `D` | Botão ▶ |
| Atirar | `Espaço` | Botão FIRE |
| Iniciar jogo | Qualquer tecla | Toque na tela |

---

## ⚡ Mecânicas

- **Barra de Energia** — Drena continuamente. Se chegar a zero, você perde uma vida.
- **Limpar a Onda** — Destruir todos os inimigos restaura a energia e avança de fase.
- **3 Vidas** — Perde uma vida quando a energia acaba ou é atingido por inimigo.
- **Progressão** — Cada onda tem um inimigo diferente, mais rápido e agressivo.

---

## 👾 Ondas de Inimigos

| Onda | Inimigo | Cor |
|------|---------|-----|
| 1 | 🧟 Zumbi | Verde / Ciano |
| 2 | 💎 Diamante | Ciano / Magenta |
| 3 | 🕐 Relógio | Amarelo / Verde |
| 4 | 🫳 Ferro de Passar | Magenta / Amarelo |
| 5 | 🔫 Fuzil | Vermelho / Laranja |
| 6 | 🍪 Biscoito | Laranja / Amarelo |

---

## 🛠️ Tecnologias

- **HTML5 Canvas** — Renderização pixel-perfect `320×240` com escala inteira `3×`
- **JavaScript puro** — Sem frameworks, sem dependências
- **Web Audio API** — Efeitos sonoros 8-bit gerados por código (laser, explosão)
- **Pixel Art por código** — Sprites desenhados via matrizes de pixels
- **CSS** — `image-rendering: pixelated` para manter os pixels nítidos

---

## 📐 Especificações Técnicas

| Item | Valor |
|------|-------|
| Resolução lógica | 320 × 240 (4:3) |
| Escala de exibição | 3× → 960 × 720px |
| Fundo | `#000000` (preto sólido) |
| Paleta | Ciano, Magenta, Amarelo, Verde Neon, Vermelho |
| FPS | 60fps via `requestAnimationFrame` |
| Áudio | Web Audio API (inicia após interação) |
| Plataformas | Desktop + Mobile (touch) |

---

## 📁 Estrutura do Projeto

```
arcade-megamania/
├── index.html      ← Jogo completo (único arquivo)
└── README.md       ← Este arquivo
```

---

## 🚀 Deploy no GitHub Pages

1. Vá em **Settings → Pages** no seu repositório
2. Em **Source**, selecione `main` branch e pasta `/ (root)`
3. Clique em **Save**
4. Aguarde ~1 minuto e acesse: `https://enzoettore116-cell.github.io/arcade-megamania-/`

---

## 👨‍💻 Créditos

Desenvolvido como primeiro projeto com **Antigravity AI**.
Inspirado no clássico **MegaMania** (Activision, 1982) para Atari 2600.

---

*Feito com ❤️ e pixels*
