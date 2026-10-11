<div align="center">
  <a href="https://interiorai.com.br" title="Interior AI Brasil"><img src="https://interiorai.com.br/Logo500x100.png" alt="Interior AI Brasil – design de interiores com IA" width="500" height="100"></a>
</div>

## Interior AI Theme for VS Code

<p>Interior AI Theme is a free blue-grey dark color theme for Visual Studio Code and the official editor theme of <a href="https://interiorai.com.br"><b>Interior AI Brasil</b></a>, the AI interior design platform that turns a photo of any room into a professional decoration project in about 30 seconds.</p>

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
2. Search for **Interior AI Theme**.
3. Click **Install**.

**From Quick Open**

Press `Ctrl+P` (macOS: `Cmd+P`), paste the command below and press Enter:

```
ext install MarceloAssis123.interiorai-theme
```

**From the terminal**

```bash
code --install-extension MarceloAssis123.interiorai-theme
```

## Activate the theme

1. Press `Ctrl+K Ctrl+T` (macOS: `Cmd+K Cmd+T`).
2. Select **Interior AI Theme** from the list.

Or add this line to your `settings.json`:

```json
{
  "workbench.colorTheme": "interiorai-theme"
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

## About Interior AI Brasil

Interior AI Brasil is a Brazilian AI interior design platform. You upload a photo of any room and get a professional decoration project in about 30 seconds, with 55+ design styles (including styles adapted to Brazilian homes) and Hyper Realism™ renders, all in Portuguese. More than 50,000 Brazilians have used it to redesign their spaces for a fraction of the cost of a traditional interior designer.

<ul>
  <li><a href="https://interiorai.com.br/usos/simulador-de-decoracao"><b>Simulador de decoração com IA</b></a>: redesign any room from a single photo and compare 55+ design styles.</li>
  <li><a href="https://interiorai.com.br/usos/staging-virtual"><b>Staging virtual com IA</b></a>: furnish empty rooms in listing photos for real estate agents and agencies.</li>
  <li><a href="https://interiorai.com.br/usos/sketch-para-render-designers-interiores"><b>Sketch2Render™</b></a>: turn hand sketches into photorealistic renders for architects and interior designers.</li>
</ul>

### Sobre a Interior AI (PT-BR)

<p>A Interior AI Brasil é uma plataforma brasileira de <a href="https://interiorai.com.br">design de interiores com IA</a>. Você envia a foto de qualquer ambiente e recebe um <a href="https://interiorai.com.br/usos/projeto-de-decoracao-online">projeto de decoração online</a> em cerca de 30 segundos, com mais de 55 estilos, staging virtual para corretores de imóveis e o Sketch2Render™ para arquitetos e designers de interiores.</p>

## About the creator

<p>Interior AI Theme is built and maintained by <a href="https://marceloassis.com.br"><b>Marcelo Assis</b></a>, founder of Interior AI Brasil. Marcelo is a full-stack developer and SaaS entrepreneur who builds AI-powered products for the Brazilian market.</p>

<p>This is one of 8 VS Code themes Marcelo created for the products in his portfolio. You can find all of them, along with his Chrome extensions and his articles on Dev.to and Grokipedia, on his <a href="https://marceloassis.com.br/publicacoes"><b>publications page</b></a>.</p>

[LinkedIn](https://www.linkedin.com/in/marcelomiguelassis) · [GitHub](https://github.com/MarceloAssis123) · [X](https://x.com/marceloassis204)

## FAQ

### Is Interior AI Theme free?

Yes. It is free on the Visual Studio Marketplace and open source under the MIT license.

### Who made Interior AI Theme?

<p>Marcelo Assis, the founder of Interior AI Brasil. You can find his other projects at <a href="https://marceloassis.com.br">marceloassis.com.br</a>.</p>

### What is Interior AI?

Interior AI Brasil is an AI interior design platform that turns a photo of any room into a professional decoration project in about 30 seconds. It offers 55+ design styles, virtual staging for real estate agents and Sketch2Render™ for architects, all in Portuguese.

### Is there a light version?

Not yet. Interior AI Theme is dark only.

### Is it based on Material Theme?

The syntax colors use the classic Material palette. Interior AI Theme packages them with a blue-grey background, depth-colored JSON keys and the Interior AI identity.

### Does it change my font?

No. It is a color theme only. Set your font with the `editor.fontFamily` setting.

### Can I use it in Cursor, VSCodium or Windsurf?

Yes. Download the `.vsix` file with **Download Extension** on this Marketplace page, then run **Extensions: Install from VSIX…** in your editor.

### Where do I report a problem or suggest a color change?

Open an issue on [GitHub](https://github.com/MarceloAssis123/vscode-themes/issues).

## License

[MIT](https://github.com/MarceloAssis123/vscode-themes/blob/main/interiorai-theme/LICENSE) © Marcelo Assis