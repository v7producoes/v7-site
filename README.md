# v7-site

Site de uma página da V7 Produções. HTML, CSS e JS num único arquivo (`index.html`), sem framework nem build — pronto pra publicar direto no Netlify (deploy de pasta estática).

Identidade seguida de `v7-base-fundacao.md`: paleta corporativa (azul profundo/azul ação/ciano/grafite/névoa), tipografia Inter, frase-âncora, as 4 frentes de oferta e a tabela de 3 planos.

## Seções
- Topo: frase-âncora + CTA WhatsApp
- 4 ofertas
- 3 planos (Essencial, Crescimento, Exclusivo)
- Prova: dado da HBR (1 em cada 4 empresas nunca responde quem pede orçamento)
- Rodapé: WhatsApp + Cal.com

## Deploy no Netlify
1. New site from Git → conecte este repositório.
2. Build command: (vazio). Publish directory: `.` (raiz).
3. Sem variáveis de ambiente — não há backend.

## Editar o número de WhatsApp
Constante `WHATSAPP_NUMBER` no `<script>` no fim de `index.html`.
