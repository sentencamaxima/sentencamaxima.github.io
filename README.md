# Sentença Máxima — Votação do Júri

Página de votação (**Culpado / Inocente**) para a peça *Sentença Máxima*, publicada via GitHub Pages.
O público escaneia um QR, vota na câmara do Tribunal de Lasten, e cada voto é enviado a um **Google Form privado** (a apuração fica só com a produção).

## Antes do espetáculo
Abra `index.html` e preencha, no topo do `<script>`, os 2 valores que o gerador do Form imprime:

```js
const FORM_ACTION = "https://docs.google.com/forms/d/e/XXXX/formResponse";
const ENTRY_ID    = "entry.XXXXXXXXX";
```

Enquanto vazios, a página exibe a cena normalmente, mas não registra votos.

## Publicação
GitHub Pages · branch `main` · raiz `/` → `https://larissamarchioto-create.github.io/sentencamaxima/`
