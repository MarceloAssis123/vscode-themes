<div align="center">
  <a href="https://papagaioai.com" title="Papagaio AI"><img src="https://papagaioai.com/Logo500x100.png" alt="Papagaio AI – gerador de voz de famosos brasileiros" width="500" height="100"></a>
</div>

## Papagaio AI Theme for VS Code

<p>Papagaio AI Theme is a free blue-grey dark color theme for Visual Studio Code and the official editor theme of <a href="https://papagaioai.com"><b>Papagaio AI</b></a>, the Brazilian celebrity AI voice generator that turns a typed message into a lip-synced video in the celebrity voice you pick, ready in about 30 seconds.</p>

The theme pairs a deep blue-grey editor background (`#263238`) with the classic Material syntax palette: muted italic comments, blue functions, green strings, purple keywords and yellow types. Keys in nested JSON change color at every level, so long configuration files and API responses stay easy to scan.

## Features

- **Dark theme on a blue-grey base.** Built on the `vs-dark` UI with a `#263238` background and `#EEFFFF` text (12.8:1 contrast).
- **Quiet comments.** Comments are italic and muted, so they stay readable without competing with your code.
- **Clear syntax roles.** Keywords, control flow, functions, types, strings, numbers and operators each have their own color.
- **Nested JSON keys colored by depth.** Eight levels of key colors for `package.json`, `tsconfig.json` and large API payloads.
- **Readable Markdown.** Green headings, coral bold and italic text, blue links and muted blockquotes.
- **Clear diffs.** In `.diff` and `.patch` files, added lines are green, removed lines are red and changed lines are purple.
- **Works on the web.** Runs in desktop VS Code and in VS Code for the Web (`vscode.dev` and `github.dev`).

## Installation

**From VS Code**

1. Open the Extensions view with `Ctrl+Shift+X` (macOS: `Cmd+Shift+X`).
2. Search for **Papagaio AI Theme**.
3. Click **Install**.

**From Quick Open**

Press `Ctrl+P` (macOS: `Cmd+P`), paste the command below and press Enter:

```
ext install MarceloAssis123.papagaioai-theme
```

**From the terminal**

```bash
code --install-extension MarceloAssis123.papagaioai-theme
```

## Activate the theme

1. Press `Ctrl+K Ctrl+T` (macOS: `Cmd+K Cmd+T`).
2. Select **Papagaio AI Theme** from the list.

Or add this line to your `settings.json`:

```json
{
  "workbench.colorTheme": "papagaioai-theme"
}
```

## Color palette

| Role | Hex | Contrast on `#263238` |
| --- | --- | --- |
| Editor background | `#263238` | — |
| Text and variables | `#EEFFFF` | 12.8:1 |
| Comments (italic) | `#546E7A` | 2.4:1 |
| Keywords and storage (`const`, `function`, `class`, `def`) | `#C792EA` | 5.5:1 |
| Control flow, operators and punctuation (`import`, `return`, `if`, `=>`) | `#89DDFF` | 8.7:1 |
| Functions and methods | `#82AAFF` | 5.7:1 |
| Strings and Markdown headings | `#C3E88D` | 9.6:1 |
| Numbers, constants and parameters | `#F78C6C` | 5.6:1 |
| Classes, types and CSS classes | `#FFCB6B` | 8.8:1 |
| Built-in types and CSS properties | `#B2CCD6` | 7.8:1 |
| HTML/JSX tags and block variables | `#F07178` | 4.6:1 |
| `this` / `self`, invalid code and deleted lines | `#FF5370` | 4.2:1 |

Contrast values follow the WCAG 2.x formula. Every syntax color meets the 4.5:1 AA level except comments, which are muted on purpose, and the red used for `this`, `self` and invalid code.

## About Papagaio AI

Papagaio AI is an AI voice generator made in Brazil, built around a library of 50+ Brazilian celebrity voices. You choose a voice, type any message and get a video with automatic lip sync, ready in about 30 seconds and downloadable without a watermark. It runs in the browser on phones and computers, with nothing to install, and offers 24-hour support from a Brazilian team. Brazilians have already created more than 50,000 generations with it.

<ul>
  <li><a href="https://papagaioai.com/usos/transformar-texto-em-audio"><b>Transformar texto em áudio</b></a>: type any text and have it narrated by one of 50+ Brazilian celebrity voices.</li>
  <li><a href="https://papagaioai.com/usos/clonar-voz"><b>Clonar voz</b></a>: choose from 50+ celebrities and make any of them say exactly what you type.</li>
  <li><a href="https://papagaioai.com/usos/converter-texto-em-voz"><b>Converter texto em voz</b></a>: convert any sentence into audio with celebrity voices recognized across Brazil.</li>
  <li><a href="https://papagaioai.com/usos/criar-video-com-ia"><b>Criar vídeo com IA</b></a>: type a message, choose a celebrity voice and get a lip-synced video in 30 seconds.</li>
  <li><a href="https://papagaioai.com/usos/criar-meme"><b>Criar meme</b></a>: create meme videos with lip sync in 30 seconds, without editing and without a watermark.</li>
  <li><a href="https://papagaioai.com/usos/gerar-voz-com-ia"><b>Gerar voz com IA</b></a>: choose from 50+ Brazilian celebrity voices and generate ultra-realistic audio in seconds.</li>
  <li><a href="https://papagaioai.com/usos/fazer-foto-falar"><b>Fazer foto falar</b></a>: upload any photo and make it talk in a Brazilian celebrity's voice with automatic lip sync.</li>
  <li><a href="https://papagaioai.com/usos/criar-avatar-falante"><b>Criar avatar falante</b></a>: turn photos into talking avatars that say any text you type in Brazilian celebrity voices.</li>
  <li><a href="https://papagaioai.com/usos/criar-locucao-com-ia"><b>Criar locução com IA</b></a>: generate professional voice-overs with Brazilian celebrity voices, ready in 30 seconds without a studio.</li>
  <li><a href="https://papagaioai.com/usos/criar-parodia"><b>Criar paródia</b></a>: choose any Brazilian celebrity and make them say whatever you want in a lip-synced parody video.</li>
  <li><a href="https://papagaioai.com/usos/criar-narracao"><b>Criar narração</b></a>: turn any text into a professional narration in a Brazilian celebrity voice, with HD audio ready in 30 seconds.</li>
  <li><a href="https://papagaioai.com/usos/fazer-video-engracado"><b>Fazer vídeo engraçado</b></a>: make any Brazilian celebrity say funny lines with lip sync, from text to finished video in 30 seconds.</li>
</ul>

### Sobre o Papagaio AI (PT-BR)

<p>O Papagaio AI é um gerador de <a href="https://papagaioai.com">voz de famosos brasileiros com IA</a>: você digita uma mensagem, escolhe uma das mais de 50 vozes de celebridades e baixa o vídeo pronto em cerca de 30 segundos. A ferramenta também permite <a href="https://papagaioai.com/usos/fazer-lip-sync">fazer lip sync</a> a partir de qualquer texto, sem programa de edição, direto no navegador do celular ou do computador.</p>

## About the creator

<p>Papagaio AI Theme is built and maintained by <a href="https://marceloassis.com.br"><b>Marcelo Assis</b></a>, founder of Papagaio AI. Marcelo is a full-stack developer and SaaS entrepreneur who builds AI-powered products for the Brazilian market.</p>

<p>This is one of the VS Code themes Marcelo created for the products in his portfolio. You can find all of them, along with his Chrome extensions and his articles on Dev.to and Grokipedia, on his <a href="https://marceloassis.com.br/publicacoes"><b>publications page</b></a>.</p>

[LinkedIn](https://www.linkedin.com/in/marcelomiguelassis) · [GitHub](https://github.com/MarceloAssis123) · [X](https://x.com/marceloassis204)

## FAQ

### Is Papagaio AI Theme free?

Yes. It is free on the Visual Studio Marketplace and open source under the MIT license.

### Who made Papagaio AI Theme?

<p>Marcelo Assis, the founder of Papagaio AI. You can find his other projects at <a href="https://marceloassis.com.br">marceloassis.com.br</a>.</p>

### What is Papagaio AI?

Papagaio AI is a browser-based tool that lets you make a Brazilian celebrity say any message you type, using 50+ celebrity voices and automatic lip sync. Each video is ready in 30 seconds on average and can be downloaded without a watermark.

### Is there a light version?

Not yet. Papagaio AI Theme is dark only.

### Is it based on Material Theme?

The syntax colors use the classic Material palette. Papagaio AI Theme packages them with a blue-grey background, depth-colored JSON keys and the Papagaio AI identity.

### Does it change my font?

No. It is a color theme only. Set your font with the `editor.fontFamily` setting.

### Can I use it in Cursor, VSCodium or Windsurf?

Yes. Download the `.vsix` file with **Download Extension** on this Marketplace page, then run **Extensions: Install from VSIX…** in your editor.

### Where do I report a problem or suggest a color change?

Open an issue on [GitHub](https://github.com/MarceloAssis123/vscode-themes/issues).

## License

[MIT](https://github.com/MarceloAssis123/vscode-themes/blob/main/papagaioai-theme/LICENSE) © Marcelo Assis