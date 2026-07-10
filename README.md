# Autos nº 24CR180 — Tribunal de Lasten

Site da convocação. Publicado via GitHub Pages → `https://sentencamaxima.github.io/`

## Estrutura
- `index.html` — convocação pública (contagem regressiva para 08/08/2026, 20h).
  - Colar em `GRUPO_URL` (topo do `<script>`) o link de convite do WhatsApp.
  - `ENDPOINT` opcional para medição de acessos por origem (`?p=`).
- `votacao.html` — câmara de votação (uso interno; **não divulgar** antes da data).
  - Colar `FORM_ACTION` e `ENTRY_ID` do Google Form privado para registrar votos.

Os parâmetros `?p=` (ex.: `?p=porta`, `?p=espelho`) apenas identificam a origem do acesso.
