<div align="center">
  <a href="https://rastreiareceita.com" title="Rastreia Receita"><img src="https://rastreiareceita.com/Logo500x100.png" alt="Rastreia Receita – analytics de receita por canal" width="500" height="100"></a>
</div>

## Rastreia Receita Theme for VS Code

<p>Rastreia Receita Theme is a free blue-grey dark color theme for Visual Studio Code and the official editor theme of <a href="https://rastreiareceita.com"><b>Rastreia Receita</b></a>, the revenue analytics tool that connects to your payment processor and shows in real time which marketing channels generate paying customers, not just visitors.</p>

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
2. Search for **Rastreia Receita Theme**.
3. Click **Install**.

**From Quick Open**

Press `Ctrl+P` (macOS: `Cmd+P`), paste the command below and press Enter:

```
ext install MarceloAssis123.rastreiareceita-theme
```

**From the terminal**

```bash
code --install-extension MarceloAssis123.rastreiareceita-theme
```

## Activate the theme

1. Press `Ctrl+K Ctrl+T` (macOS: `Cmd+K Cmd+T`).
2. Select **Rastreia Receita Theme** from the list.

Or add this line to your `settings.json`:

```json
{
  "workbench.colorTheme": "rastreiareceita-theme"
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

## About Rastreia Receita

Rastreia Receita is a Brazilian revenue analytics tool built for info-product creators, SaaS companies, e-commerce stores and agencies. With a 4kb script on the site and a payment processor such as Stripe, Hotmart, Kiwify, AbacatePay or Cart Panda connected, it links every sale to the marketing channel that brought the customer. Its dashboard, fully in Portuguese, centers on revenue per visitor.

<ul>
  <li><a href="https://rastreiareceita.com/usos/calcular-roi"><b>Calcular ROI</b></a>: get each channel's real ROI, calculated automatically from its sales.</li>
  <li><a href="https://rastreiareceita.com/usos/calcular-roas"><b>Calcular ROAS</b></a>: calculate ROAS from sales, not clicks, tying each sale to its ad.</li>
  <li><a href="https://rastreiareceita.com/usos/rastrear-conversoes"><b>Rastrear conversões</b></a>: see where each visitor came from, which pages they visited and when they bought.</li>
  <li><a href="https://rastreiareceita.com/usos/criar-dashboard-de-vendas"><b>Criar dashboard de vendas</b></a>: get a sales-by-channel dashboard right after pasting the script, with no spreadsheets.</li>
  <li><a href="https://rastreiareceita.com/usos/gerar-utm"><b>Gerar UTM</b></a>: create standardized UTMs and see each link's real sales.</li>
  <li><a href="https://rastreiareceita.com/usos/analisar-funil-de-vendas"><b>Analisar funil de vendas</b></a>: see each funnel stage's conversion rate by source channel.</li>
  <li><a href="https://rastreiareceita.com/usos/medir-receita-por-visitante"><b>Medir receita por visitante</b></a>: find out each visitor's value in reais, by source channel.</li>
  <li><a href="https://rastreiareceita.com/usos/acompanhar-vendas-por-canal"><b>Acompanhar vendas por canal</b></a>: see in real time the sales each marketing channel generates.</li>
  <li><a href="https://rastreiareceita.com/usos/monitorar-visitantes-do-site"><b>Monitorar visitantes do site</b></a>: watch live who is on your site, their channel and their revenue value.</li>
  <li><a href="https://rastreiareceita.com/usos/gerar-relatorio-de-roi"><b>Gerar relatório de ROI</b></a>: generate automatic per-campaign ROI reports for agencies and traffic managers.</li>
  <li><a href="https://rastreiareceita.com/usos/calcular-taxa-de-conversao"><b>Calcular taxa de conversão</b></a>: get each channel's conversion rate based on sales, not clicks or leads.</li>
  <li><a href="https://rastreiareceita.com/usos/calcular-cac"><b>Calcular CAC</b></a>: see each channel's customer acquisition cost with real revenue data.</li>
  <li><a href="https://rastreiareceita.com/usos/criar-funil-de-vendas"><b>Criar funil de vendas</b></a>: build custom funnels with goals per stage and revenue by channel.</li>
  <li><a href="https://rastreiareceita.com/usos/calcular-ltv"><b>Calcular LTV</b></a>: compare customer lifetime value and CAC per traffic source.</li>
  <li><a href="https://rastreiareceita.com/usos/analisar-trafego-do-site"><b>Analisar tráfego do site</b></a>: see how much each traffic source generates in real sales.</li>
  <li><a href="https://rastreiareceita.com/usos/monitorar-site"><b>Monitorar site</b></a>: follow active visitors, source channels and today's revenue in real time.</li>
  <li><a href="https://rastreiareceita.com/usos/medir-resultados-marketing-digital"><b>Medir resultados marketing digital</b></a>: make real revenue, not pageviews or clicks, your central marketing metric.</li>
  <li><a href="https://rastreiareceita.com/usos/rastrear-vendas-online"><b>Rastrear vendas online</b></a>: see every sale in real time with its source channel attributed.</li>
  <li><a href="https://rastreiareceita.com/usos/configurar-analytics-no-site"><b>Configurar analytics no site</b></a>: set up revenue analytics with a 4kb script, without GTM or developers.</li>
</ul>

### Sobre o Rastreia Receita (PT-BR)

<p>O Rastreia Receita é uma ferramenta brasileira de <a href="https://rastreiareceita.com">analytics simples com atribuição automática</a> de receita: com um script de 4kb e a integração com Hotmart, Kiwify, Stripe ou AbacatePay, cada venda fica ligada ao canal de origem do cliente. Esses dados ajudam a <a href="https://rastreiareceita.com/usos/otimizar-investimento-em-marketing">otimizar investimento em marketing</a>, levando o budget para onde há retorno e cortando o desperdício.</p>

## About the creator

<p>Rastreia Receita Theme is built and maintained by <a href="https://marceloassis.com.br"><b>Marcelo Assis</b></a>, founder of Rastreia Receita. Marcelo is a full-stack developer and SaaS entrepreneur who builds AI-powered products for the Brazilian market.</p>

<p>This is one of the VS Code themes Marcelo created for the products in his portfolio. You can find all of them, along with his Chrome extensions and his articles on Dev.to and Grokipedia, on his <a href="https://marceloassis.com.br/publicacoes"><b>publications page</b></a>.</p>

[LinkedIn](https://www.linkedin.com/in/marcelomiguelassis) · [GitHub](https://github.com/MarceloAssis123) · [X](https://x.com/marceloassis204)

## FAQ

### Is Rastreia Receita Theme free?

Yes. It is free on the Visual Studio Marketplace and open source under the MIT license.

### Who made Rastreia Receita Theme?

<p>Marcelo Assis, the founder of Rastreia Receita. You can find his other projects at <a href="https://marceloassis.com.br">marceloassis.com.br</a>.</p>

### What is Rastreia Receita?

Rastreia Receita is an analytics tool focused on revenue that automatically attributes each sale on Hotmart, Kiwify, Stripe or AbacatePay to its marketing channel, with custom goals, funnels and a real-time visitor map.

### Is there a light version?

Not yet. Rastreia Receita Theme is dark only.

### Is it based on Material Theme?

The syntax colors use the classic Material palette. Rastreia Receita Theme packages them with a blue-grey background, depth-colored JSON keys and the Rastreia Receita identity.

### Does it change my font?

No. It is a color theme only. Set your font with the `editor.fontFamily` setting.

### Can I use it in Cursor, VSCodium or Windsurf?

Yes. Download the `.vsix` file with **Download Extension** on this Marketplace page, then run **Extensions: Install from VSIX…** in your editor.

### Where do I report a problem or suggest a color change?

Open an issue on [GitHub](https://github.com/MarceloAssis123/vscode-themes/issues).

## License

[MIT](https://github.com/MarceloAssis123/vscode-themes/blob/main/rastreiareceita-theme/LICENSE) © Marcelo Assis