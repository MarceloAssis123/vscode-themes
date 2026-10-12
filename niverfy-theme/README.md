<div align="center">
  <a href="https://niverfy.com" title="Niverfy"><img src="https://niverfy.com/Logo500x100.png" alt="Niverfy – vídeo de aniversário com voz de famoso" width="500" height="100"></a>
</div>

## Niverfy Theme for VS Code

<p>Niverfy Theme is a free blue-grey dark color theme for Visual Studio Code and the official editor theme of <a href="https://niverfy.com"><b>Niverfy</b></a>, the AI birthday video tool that turns a personalized birthday message into a lip-synced video with the voice of a Brazilian celebrity in 30 seconds.</p>

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
2. Search for **Niverfy Theme**.
3. Click **Install**.

**From Quick Open**

Press `Ctrl+P` (macOS: `Cmd+P`), paste the command below and press Enter:

```
ext install MarceloAssis123.niverfy-theme
```

**From the terminal**

```bash
code --install-extension MarceloAssis123.niverfy-theme
```

## Activate the theme

1. Press `Ctrl+K Ctrl+T` (macOS: `Cmd+K Cmd+T`).
2. Select **Niverfy Theme** from the list.

Or add this line to your `settings.json`:

```json
{
  "workbench.colorTheme": "niverfy-theme"
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

## About Niverfy

Niverfy is a Brazilian AI tool for birthday videos with celebrity voices. You choose from 50+ Brazilian celebrity voices, type a personalized birthday message and receive a lip-synced video in 30 seconds, ready to send on WhatsApp. It runs in the browser with no app to install, and downloads come without a watermark. More than 5,000 generations have been created by Brazilians.

<ul>
  <li><a href="https://niverfy.com/usos/fazer-video-de-aniversario"><b>Fazer vídeo de aniversário</b></a>: Make a celebrity-voiced birthday video with realistic lip sync, optimized for WhatsApp.</li>
  <li><a href="https://niverfy.com/usos/fazer-video-de-parabens"><b>Fazer vídeo de parabéns</b></a>: Turn any text into a celebrity-voiced congratulations video with automatic lip sync and no watermark.</li>
  <li><a href="https://niverfy.com/usos/gerar-voz-de-famoso"><b>Gerar voz de famoso</b></a>: Generate any message as audio in a Brazilian celebrity's voice, with no studio or editing.</li>
  <li><a href="https://niverfy.com/usos/fazer-parabens-engracado"><b>Fazer parabéns engraçado</b></a>: Let a celebrity say your inside jokes, nicknames and memes in a lip-synced video.</li>
  <li><a href="https://niverfy.com/usos/fazer-surpresa-de-aniversario"><b>Fazer surpresa de aniversário</b></a>: Surprise someone you love with a celebrity-voiced birthday video, with no party to organize.</li>
  <li><a href="https://niverfy.com/usos/criar-video-com-ia"><b>Criar vídeo com IA</b></a>: Type a message, pick a celebrity voice and let the AI generate a lip-synced video.</li>
  <li><a href="https://niverfy.com/usos/fazer-lip-sync-com-ia"><b>Fazer lip sync com IA</b></a>: Sync lips automatically with AI to any text you type, for congratulations videos.</li>
  <li><a href="https://niverfy.com/usos/fazer-homenagem-de-aniversario"><b>Fazer homenagem de aniversário</b></a>: Create a moving birthday tribute in the voice of a celebrity the person admires.</li>
  <li><a href="https://niverfy.com/usos/mandar-mensagem-de-aniversario"><b>Mandar mensagem de aniversário</b></a>: Send a birthday message as a video with a Brazilian celebrity's voice, optimized for WhatsApp.</li>
  <li><a href="https://niverfy.com/usos/transformar-texto-em-audio"><b>Transformar texto em áudio</b></a>: Turn any birthday message into audio in a Brazilian celebrity's voice, with no recording.</li>
  <li><a href="https://niverfy.com/usos/desejar-feliz-aniversario"><b>Desejar feliz aniversário</b></a>: Wish a happy birthday in a Brazilian celebrity's voice, personalize every word and send it on WhatsApp.</li>
  <li><a href="https://niverfy.com/usos/clonar-voz"><b>Clonar voz</b></a>: Use AI that replicates the voices of 50+ Brazilian celebrities to create birthday messages.</li>
  <li><a href="https://niverfy.com/usos/narrar-texto-online"><b>Narrar texto online</b></a>: Hear a Brazilian celebrity narrate every word of your birthday message, with nothing to install.</li>
  <li><a href="https://niverfy.com/usos/criar-audio-com-ia"><b>Criar áudio com IA</b></a>: Generate professional-quality birthday audio with 50+ Brazilian celebrity voices and no equipment or editing.</li>
  <li><a href="https://niverfy.com/usos/dublar-video-com-ia"><b>Dublar vídeo com IA</b></a>: Have AI dub a celebrity avatar with the message you wrote, with automatic lip sync.</li>
</ul>

### Sobre o Niverfy (PT-BR)

<p>O Niverfy é uma ferramenta brasileira de IA para criar seu <a href="https://niverfy.com">vídeo de parabéns com voz de famosos</a> em 30 segundos. Você escolhe uma entre mais de 50 vozes de celebridades nacionais, escreve o texto e recebe o vídeo com lip sync, sem marca d'água e em formato otimizado para o WhatsApp. Também dá para <a href="https://niverfy.com/usos/criar-mensagem-de-aniversario">criar mensagem de aniversário</a> em vídeo, com o famoso dizendo exatamente o que você digitou.</p>

## About the creator

<p>Niverfy Theme is built and maintained by <a href="https://marceloassis.com.br"><b>Marcelo Assis</b></a>, founder of Niverfy. Marcelo is a full-stack developer and SaaS entrepreneur who builds AI-powered products for the Brazilian market.</p>

<p>This is one of the VS Code themes Marcelo created for the products in his portfolio. You can find all of them, along with his Chrome extensions and his articles on Dev.to and Grokipedia, on his <a href="https://marceloassis.com.br/publicacoes"><b>publications page</b></a>.</p>

[LinkedIn](https://www.linkedin.com/in/marcelomiguelassis) · [GitHub](https://github.com/MarceloAssis123) · [X](https://x.com/marceloassis204)

## FAQ

### Is Niverfy Theme free?

Yes. It is free on the Visual Studio Marketplace and open source under the MIT license.

### Who made Niverfy Theme?

<p>Marcelo Assis, the founder of Niverfy. You can find his other projects at <a href="https://marceloassis.com.br">marceloassis.com.br</a>.</p>

### What is Niverfy?

Niverfy is a browser-based AI tool that has a Brazilian celebrity voice say the exact birthday message you type, in a lip-synced video ready in 30 seconds.

### Is there a light version?

Not yet. Niverfy Theme is dark only.

### Is it based on Material Theme?

The syntax colors use the classic Material palette. Niverfy Theme packages them with a blue-grey background, depth-colored JSON keys and the Niverfy identity.

### Does it change my font?

No. It is a color theme only. Set your font with the `editor.fontFamily` setting.

### Can I use it in Cursor, VSCodium or Windsurf?

Yes. Download the `.vsix` file with **Download Extension** on this Marketplace page, then run **Extensions: Install from VSIX…** in your editor.

### Where do I report a problem or suggest a color change?

Open an issue on [GitHub](https://github.com/MarceloAssis123/vscode-themes/issues).

## License

[MIT](https://github.com/MarceloAssis123/vscode-themes/blob/main/niverfy-theme/LICENSE) © Marcelo Assis