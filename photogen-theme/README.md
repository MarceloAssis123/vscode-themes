<div align="center">
  <a href="https://photogen.com.br" title="PhotoGen"><img src="https://photogen.com.br/Logo500x100.png" alt="PhotoGen – fotógrafo IA" width="500" height="100"></a>
</div>

## PhotoGen Theme for VS Code

<p>PhotoGen Theme is a free blue-grey dark color theme for Visual Studio Code and the official editor theme of <a href="https://photogen.com.br"><b>PhotoGen</b></a>, the AI photographer that generates realistic photos of you in 15–20 seconds from an AI model trained on 10–20 of your selfies.</p>

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
2. Search for **PhotoGen Theme**.
3. Click **Install**.

**From Quick Open**

Press `Ctrl+P` (macOS: `Cmd+P`), paste the command below and press Enter:

```
ext install MarceloAssis123.photogen-theme
```

**From the terminal**

```bash
code --install-extension MarceloAssis123.photogen-theme
```

## Activate the theme

1. Press `Ctrl+K Ctrl+T` (macOS: `Cmd+K Cmd+T`).
2. Select **PhotoGen Theme** from the list.

Or add this line to your `settings.json`:

```json
{
  "workbench.colorTheme": "photogen-theme"
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

## About PhotoGen

PhotoGen is an AI photographer focused on people. You upload 10–20 selfies from different angles to train your own AI model, then pick one of 145+ themed packs or write a custom prompt and receive realistic photos of yourself in 15–20 seconds. It also includes Upscale, Relight and Zoom-out tools, clothing try-on with native Shopify integration, full encryption and LGPD compliance.

<ul>
  <li><a href="https://photogen.com.br/usos/fotos-corporativas-femininas"><b>Fotos corporativas femininas</b></a>: generate executive portraits for women in 20 seconds, with studio lighting and a natural expression.</li>
  <li><a href="https://photogen.com.br/usos/criar-foto-3x4-online"><b>Criar foto 3x4 online</b></a>: turn any selfie into a 3x4 document photo with an automatic white background and print-ready resolution.</li>
  <li><a href="https://photogen.com.br/usos/restaurar-fotos-antigas-online-gratis"><b>Restaurar fotos antigas online grátis</b></a>: restore damaged, faded or torn photos in seconds, recovering sharpness, color and detail automatically.</li>
  <li><a href="https://photogen.com.br/usos/foto-para-curriculo-lattes"><b>Foto para currículo Lattes</b></a>: create a professional academic photo for researchers and professors in seconds, without a studio or photographer.</li>
</ul>

### Sobre o PhotoGen (PT-BR)

<p>O PhotoGen é um <a href="https://photogen.com.br">fotógrafo de IA focado em pessoas</a>: você envia 10–20 selfies, treina um modelo próprio e recebe retratos realistas em 15–20 segundos, com 145+ pacotes temáticos à escolha. Entre os usos está a <a href="https://photogen.com.br/usos/foto-do-rg-online">foto do RG online</a>, gerada em 20 segundos com fundo branco e nas proporções do padrão oficial brasileiro.</p>

## About the creator

<p>PhotoGen Theme is built and maintained by <a href="https://marceloassis.com.br"><b>Marcelo Assis</b></a>, founder of PhotoGen. Marcelo is a full-stack developer and SaaS entrepreneur who builds AI-powered products for the Brazilian market.</p>

<p>This is one of the VS Code themes Marcelo created for the products in his portfolio. You can find all of them, along with his Chrome extensions and his articles on Dev.to and Grokipedia, on his <a href="https://marceloassis.com.br/publicacoes"><b>publications page</b></a>.</p>

[LinkedIn](https://www.linkedin.com/in/marcelomiguelassis) · [GitHub](https://github.com/MarceloAssis123) · [X](https://x.com/marceloassis204)

## FAQ

### Is PhotoGen Theme free?

Yes. It is free on the Visual Studio Marketplace and open source under the MIT license.

### Who made PhotoGen Theme?

<p>Marcelo Assis, the founder of PhotoGen. You can find his other projects at <a href="https://marceloassis.com.br">marceloassis.com.br</a>.</p>

### What is PhotoGen?

PhotoGen is an AI photographer that turns 10–20 of your selfies into a personal AI model and uses it to generate realistic photos of you. Training takes 90 seconds to 5 minutes, and each photo is ready in 15–20 seconds.

### Is there a light version?

Not yet. PhotoGen Theme is dark only.

### Is it based on Material Theme?

The syntax colors use the classic Material palette. PhotoGen Theme packages them with a blue-grey background, depth-colored JSON keys and the PhotoGen identity.

### Does it change my font?

No. It is a color theme only. Set your font with the `editor.fontFamily` setting.

### Can I use it in Cursor, VSCodium or Windsurf?

Yes. Download the `.vsix` file with **Download Extension** on this Marketplace page, then run **Extensions: Install from VSIX…** in your editor.

### Where do I report a problem or suggest a color change?

Open an issue on [GitHub](https://github.com/MarceloAssis123/vscode-themes/issues).

## License

[MIT](https://github.com/MarceloAssis123/vscode-themes/blob/main/photogen-theme/LICENSE) © Marcelo Assis