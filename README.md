# Fretus

Compact, lightweight Windows utility for **real-time game color enhancement** (with saveable presets) and **live aspect-ratio stretching** without changing your monitor resolution.

> **[English](#english) · [Português](#portugu%C3%AAs)**

---

## English

### Download & Usage
1. Download **`Fretus.exe`** from this repository.
2. Double-click **`Fretus.exe`** — it is completely standalone (no Python, extra folders, or installers required).
   - If Windows SmartScreen appears on first launch, click **More info → Run anyway**.
3. Custom presets are saved automatically to `presets.json` next to `Fretus.exe` (or in `%APPDATA%\Fretus\presets.json` if the folder is read-only).

### Features
- **Real-Time Color Filter (Anti-Cheat Safe):** Uses native Windows `Magnification.dll` 5×5 color matrices + 16-bit hardware LUTs (`SetDeviceGammaRamp`) with zero DLL injection.
  - Controls: **Saturation** (`0–350%`), **Vibrance / Pop**, **Deep Contrast (S-Curve)**, **Black eQualizer**, **Exposure**, **Contrast**, **Brightness**, **Gamma**, **Black Level**, **Highlights**, **Temperature**, **Tint**, **Hue**, **RGB Channels**, and **6 Color Modes** (`Normal`, `Vivid+`, `Protan`, `Deutan`, `Tritan`, `Noir`).
  - **NVIDIA Digital Vibrance (Optional):** Direct GPU driver control that restores your original driver level when disabled or closed.
  - **Presets:** Includes 8 built-in presets + save/apply/delete your own presets.
- **Aspect Ratio Stretch (No Resolution Change):**
  - **Crop + Stretch:** Crops to your chosen aspect ratio (`4:3`, `5:4`, `16:10`, `3:2`, `1:1`, `21:9`, or `Custom`) and stretches it fullscreen without changing Windows resolution — works even in games without native stretched support (set the game to **Windowed** or **Borderless**).
  - **Full Window / Borderless Modes:** Stretch an entire window or strip window borders into fullscreen, plus black-bar trimming.

### Global Hotkeys
| Shortcut | Action |
|---|---|
| `F8` | Show / Hide Fretus |
| `F9` | Toggle Color Filter |
| `F10` | Toggle Screen Stretch |
| `Ctrl + Shift + R` | Instant Reset (Color & Screen) |

---

## Português

### Download & Como Usar
1. Baixe o arquivo **`Fretus.exe`** neste repositório.
2. Dê duplo clique em **`Fretus.exe`** — ele é totalmente portátil e independente (não precisa de Python nem de pastas extras).
   - Se o Windows SmartScreen aparecer na primeira vez, clique em **Mais informações → Executar assim mesmo**.
3. Seus presets personalizados são salvos automaticamente em `presets.json` ao lado do `Fretus.exe` (ou em `%APPDATA%\Fretus\presets.json` caso a pasta seja somente leitura).

### Funcionalidades
- **Filtro de Cor em Tempo Real (Anti-Cheat Safe):** Usa a matriz 5×5 nativa do Windows (`Magnification.dll`) + LUT hardware de 16 bits (`SetDeviceGammaRamp`), sem injetar DLLs nos jogos.
  - Controles: **Saturação** (`0–350%`), **Vibrance / Pop**, **Contraste Profundo (S-Curve)**, **Black eQualizer** (clareia sombras sem lavar as cores), **Exposição**, **Contraste**, **Brilho**, **Gamma**, **Nível de Preto**, **Realces**, **Temperatura**, **Tonalidade (Tint)**, **Matiz (Hue)**, **Canais RGB** e **6 Modos de Cor** (`Normal`, `Vivid+`, `Protan`, `Deutan`, `Tritan`, `Noir`).
  - **NVIDIA Digital Vibrance (Opcional):** Controle direto do driver da GPU, restaurando automaticamente seu nível original ao desativar ou sair.
  - **Presets:** 8 presets prontos + criação e gerenciamento dos seus próprios presets.
- **Aspect Ratio / Stretch (Sem Mudar Resolução):**
  - **Recorte + Esticar:** Recorta para a proporção desejada (`4:3`, `5:4`, `16:10`, `3:2`, `1:1`, `21:9` ou `Custom`) e estica em tela cheia sem mexer na resolução do monitor — funciona até em jogos que não suportam resoluções esticadas (use o jogo em **Modo Janela** ou **Sem Bordas**).
  - **Janela Inteira / Sem Bordas:** Estica toda a janela ou remove bordas em tela cheia, com opção de corte de faixas pretas (*Trim*).

### Atalhos Globais
| Atalho | Ação |
|---|---|
| `F8` | Mostrar / Esconder Fretus |
| `F9` | Ligar / Desligar Filtro de Cor |
| `F10` | Ligar / Desligar Stretch de Tela |
| `Ctrl + Shift + R` | Reset Geral Imediato |
